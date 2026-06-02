import os

opcao = 0
cod_produto = []
nome_produto = []
valor_produto = []
quantidade_produto = []


while opcao != 5:  
    print("=======MENU===========")
    print("1 - Cadastrar")
    print("2 - Listar")
    print("3 - Alterar usuário")
    print("4 - Excluir usuário")
    print("5 - Sair do programa")
    opcao = int(input("Escolha uma opção: "))
    print("======================")

    if opcao == 1:
        codigo = input("Digite o codigo do seu produto: ")
        nome = input("Digite o noem do seu produto: ")
        valor = input("Digite o valor do seu produto: ")
        quantidade = input("Digite a quantia do seu produto: ")
        

        cod_produto.append(codigo)
        nome_produto.append(nome) 
        valor_produto.append(valor)
        quantidade_produto.append(quantidade)           

        print("Produto cadastrado com sucesso!!")
        input()
        os.system("cls")

    elif opcao == 2:
        print("===== LISTA DE PRODUTOS =====")

        for i in range(len(codigo)):
            print("==============================")
            print(f"Codigo: {cod_produto[i]}")
            print(f"Nome: {nome_produto[i]}")
            print(f"Valor: {valor_produto[i]}")
            print(f"Quantidade: {quantidade_produto[i]}")

        input()
        os.system("cls")

    elif opcao == 3:
        print("====== ALTERAR PRODUTO ======")

        for i, nome in enumerate(cod_produto):
            print(f"{i} - {codigo}")

        indice = int(input("Escolha o número do produto: "))

        if indice < len(cod_produto):
            cod_produto[indice] = input("Codigo atualizado: ")
            nome_produto[indice] = input("Novo nome: ")
            valor_produto[indice] = input("Valor atualizado: ")
            quantidade_produto[indice] = input("Quantia atualizado: ")

            print("Produto atualizado com sucesso!")
        else:
            print("Índice inválido")

        input()
        os.system("cls")

    elif opcao == 4:
        print("====== EXCLUIR USUÁRIO ======")

        for i, nome in enumerate(cod_produto):
            print(f"{i} - {codigo}")

        indice = int(input("Digite o número do produto que deseja excluir: "))

        if indice < len(cod_produto):
            cod_produto.pop(indice)
            nome_produto.pop(indice)
            valor_produto.pop(indice)
            quantidade_produto.pop(indice)

            print("Produto excluído com sucesso!")
        else:
            print("Índice inválido")

        input()
        os.system("cls")

