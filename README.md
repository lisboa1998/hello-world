# hello-mundo
#Faça um programa que leia 3 números inteiros e após indique qual dos 3 é o maior, o menor e o do meio.


n1 = int(input("Digite o valor de n1: "))
n2 = int(input("Digite o valor de n2: "))
n3 = int(input("Digite o valor de n3: "))

if n1 > n2 and n1 > n3:
 maior=n1
 if n2 > n3:
   meio=n2
   menor=n3
 else:
   meio=n3
   menor=n2
   
if n2 > n1 and n2 > n3:
 maior=n2
 if n1 > n3:
   meio=n1
   menor=n3
 else:
   meio=n3
   menor=n1
   
if n3 > n1 and n3 > n2:
 maior=n3
 if n1 > n2:
   meio=n1
   menor=n2
 else:
   meio=n2
   menor=n1

print("Maior=",maior," Meio=",meio," Menor=",menor)   
