    # Opção 2: Resumo
    elif escolha == "2":
        if totalpessoas == 0:
            print("Nenhuma simulação realizada.")
        else:
            media_gasto = soma_gastos / totalpessoas
            print("\n RESUMO ")
            print(f"Total de pessoas: {totalpessoas}")
            print(f"Vale a pena pedir VT: {valepena}")
            print(f"Economia total: R$ {economiatotal:.2f}")
            print(f"Gasto médio mensal: R$ {mediagasto:.2f}")
            print(f"Maior gasto mensal: R$ {maiorgasto:.2f}")
