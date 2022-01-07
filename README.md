# Calculadora no Python
# Primeiro Projeto

print('Lets Calculate')

while True:

    operacao = input('''
    Please type in the math operation you would like to complete:
    + para somar
    - para subtrair
    * para multiplicar
    / para dividir
    ''')

    numero1 = int(input("Digite um numero: "))
    numero2 = int(input("Digite um numero: "))
    if operacao == '+':
        print(numero1 + numero2)
    elif operacao == '*':
        print(numero1 * numero2)
    elif operacao == '-':
        print(numero1 - numero2)
    elif operacao == '/':
        print(numero1 / numero2)
    else:
        print('Operação Invalida')
