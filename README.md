# Cualificacion-de-triangulos-segun-sus-lados
El objetivo de este programa es cualificar de que tipo de triangulo se trata (Isoceles , Escaleno , Equilatero) tomando como input sus lados sin operadores logicos

A=int(input("Introduce el lado A el triangulo:"))

B=int(input("Introduce el lado B el triangulo:"))

C=int(input("Introduce el lado C el triangulo:"))

i=1

if A+B>C:
	i=i+1

if A+C>B:
	i=i+1

if C+B>A:
	i=i+1

if i==4:
   print("Es un triangulo")
else:
  print("No es un triangulo") 


