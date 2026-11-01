    # Opção 2: Resumo
    elif escolha == "2":
        if total_pessoas == 0:
            print("Nenhuma simulação realizada.")
        else:
            media_gasto = soma_gastos / total_pessoas
            print("\n--- RESUMO ---")
            print(f"Total de pessoas: {total_pessoas}")
            print(f"Vale a pena pedir VT: {vale_pena_count}")
            print(f"Economia total: R$ {economia_total:.2f}")
            print(f"Gasto médio mensal: R$ {media_gasto:.2f}")
            print(f"Maior gasto mensal: R$ {maior_gasto:.2f}")
