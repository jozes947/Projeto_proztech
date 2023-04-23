# Projeto_proztech

quant_rodas =int(imput("Quantidade de rodas: "))
peso = int(input("Qual o peso em Kg"))
quant_viajantes = int(input("Quantidade de pessoas no veículo"))

if (2 == quant_rodas <=3):
    print("Sua categoria é A")
elif (quant_rodas == 4 and quant_viajantes <= 8 and peso < 3500 ):
    print("Sua categoria é B")
elif (quant_rodas >= 4 and 3500 and peso <= 6000):
    print("Sua categoria é C")
elif (quant_rodas >= 4 and quant_viajantes > 8):
    print("Sua categoria é D")
elif (quant_rodas >= 4 and peso > 6000):
    print("Sua categoria é E")
else:
    print("Achar categoria")
