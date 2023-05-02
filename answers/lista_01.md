1. Faça um programa que imprima a frase "Olá, mundo!" na tela.

```python
print("Olá, mundo!")
```

2. Faça um programa que receba o nome do usuário e imprima uma mensagem de boas-vindas.

```python
nome = input("Digite o seu nome: ")
print("Bem-vindo,", nome + "!")
```

3. Faça um programa que leia dois números inteiros e imprima a sua soma.

```python
num1 = int(input("Digite o primeiro número: "))
num2 = int(input("Digite o segundo número: "))
soma = num1 + num2
print("A soma de", num1, "e", num2, "é", soma)
```

4. Faça um programa que receba a nota de três provas de um aluno e calcule a média entre elas.

```python
nota1 = float(input("Digite a nota da primeira prova: "))
nota2 = float(input("Digite a nota da segunda prova: "))
nota3 = float(input("Digite a nota da terceira prova: "))
media = (nota1 + nota2 + nota3) / 3
print("A média do aluno é:", media)
```

5. Faça um programa que leia a base e a altura de um triângulo e calcule a sua área.

```python
base = float(input("Digite a base do triângulo: "))
altura = float(input("Digite a altura do triângulo: "))

area = (base * altura) / 2

print("A área do triângulo é:", area)
```

6. Faça um programa que leia um número inteiro e verifique se ele é par ou ímpar.

```python
num = int(input("Digite um número inteiro: "))

if num % 2 == 0:
    print(f"{num} é par.")
else:
    print(f"{num} é ímpar.")
```

7. Faça um programa que leia a idade de uma pessoa e verifique se ela é maior ou igual a 18 anos.

```python
idade = int(input("Digite sua idade: "))

if idade >= 18:
    print("Você é maior de idade!")
else:
    print("Você é menor de idade.")
```

8. Faça um programa que leia três números inteiros e imprima o maior deles.

```python
a = int(input("Digite o primeiro número: "))
b = int(input("Digite o segundo número: "))
c = int(input("Digite o terceiro número: "))

if a >= b and a >= c:
    print("O maior número é:", a)
elif b >= a and b >= c:
    print("O maior número é:", b)
else:
    print("O maior número é:", c)
```

9. Faça um programa que leia uma temperatura em graus Celsius e converta-a em graus Fahrenheit.

```python
celsius = float(input("Digite a temperatura em graus Celsius: "))
fahrenheit = (celsius * 9/5) + 32
print("A temperatura em Fahrenheit é:", fahrenheit, "graus")
```

10. Faça um programa que leia o peso e a altura de uma pessoa e calcule o seu índice de massa corporal (IMC).

```python
altura = float(input("Digite a sua altura em metros: "))
peso = float(input("Digite o seu peso em quilos: "))
imc = peso / (altura ** 2)
print("O seu IMC é:", imc)
```