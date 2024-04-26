print('Sistema de livros')
quantItens = int(input('Digite a quantidade de livros comprados: '))
valorTotal = float(input('Digite o valor total da compra: '))

if quantItens <= 10:
    print(f'Sem desconto, valor total da compra: R$ {valorTotal}')
elif quantItens <= 20:
    valorFinal = valorTotal * 0.95
    print(f'De 11 a 20 itens comprados, desconto de 5%, valor total da compra: R$ {valorFinal}')
elif quantItens <= 30:
    valorFinal = valorTotal * 0.90
    print(f'De 21 a 30 itens comprados, desconto de 10%, valor total da compra: R$ {valorFinal}')
else:
    valorFinal = valorTotal * 0.85
    print(f'Mais de 30 itens comprados, desconto de 15%, valor total da compra: R$ {valorFinal}')
