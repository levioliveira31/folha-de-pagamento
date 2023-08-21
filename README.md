# folha-de-pagamento
# desenvolvido em aula no 18/08/2023, descontando o inss e o vale transporte
salarioB = float(input("informe seu salario: "))
valetrans = input("descontar o vale transporte? ")

if salarioB <1302.00:
    inss = salarioB*0.075
    print (f"Calculo do INSS R${inss}")
    print ("Seu salario liquído sem INSS é de: R$", (salarioB-inss))
    
elif salarioB <2571.29:
    inss = salarioB*0.09
    print (f"Calculo do INSS R${inss}")
    print ("Seu salario liquído é de: R$", (salarioB-inss))
elif salarioB <3856.94:
    inss = salarioB*0.12
    print (f"Calculo do INSS R${inss}")
    print ("Seu salario liquído é de: R$", (salarioB-inss))
elif salarioB <7507.50:
    inss = salarioB*0.14
    print (f"Calculo do INSS R${inss}")
    print ("Seu salario liquído é de: R$", (salarioB-inss))
elif salarioB >3856.95:
    inss = salarioB-876.95
    print (f"Calculo do INSS R${inss}")
    print ("Seu salario liquído é de: R$", (salarioB-inss))
    
    
if valetrans == "s":
    salarioB - (salarioB*6/100+(salarioB))
    print ("salario bruto - o inss descontando vale transporte:", salarioB)  
