n1 = float(input('Digite um valor:'))
n2 = float(input('Digite um valor:'))

print('Operações disponíveis:')
print('\t 1 - soma')
print('\t 2 - subtração')
print('\t 3 - multiplicação')
print('\t 4 - divisão')

op = input ('Escolha a operção:')

if (op == '1'):
   print (n1,'+',n2,'=', n1+n2)
elif (op == '2'):
   print (n1,'-',n2,'=', n1-n2)
elif (op == '3'):
   print (n1,'*',n2,'=', n1*n2)
elif (op == '4'):
   print (n1,'/',n2,'=', n1/n2)
if n2 != 0:
    print(n1/n2)
else:
    print("divisão por zero")

else:
   print('Você digitou uma opção inválida!, tente novamente!')
   
