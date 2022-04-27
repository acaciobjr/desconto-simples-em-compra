# desconto-simples-em-compra.py
Desconto simples para compra entre preços

compra=float(input("quanto foi o valor da compra?"))
real=compra
print("====RESULTADO====")
print("Você comprou ", compra, "em nossa loja. Obrigado!")
if compra>=500 and compra<=999:
    desconto=compra*0.10
    print("por fazer mais de R$500 em compras \n você vai receber R$", desconto , " de desconto." )
    print("O valor a ser pago será de R$", compra-desconto)
elif compra>=1000:
    desconto2=compra*0.15
    print("em compras acima de R$1000 \n você vai receber R$", desconto2, " de desconto.")
    print("O valor a ser pago será de R$", compra-desconto2)
    print("VOLTE SEMPRE!")

