# Exercicio037.py

num = int(input('Digite um numero inteiro: '))
print('''escolha uma das bases para conversão:
[1] Binario
[2] Octal
[3] Hexadecimal''')
opcao = int(input('Sua opção: '))
if opcao == 1:
    print('Em binario: {}'.format(bin(num)[2:]))
elif opcao == 2:
    print('Em Octal: {}'.format(oct(num)[2:]))
elif opcao == 3:
    print('Em Hexadecimal: {}'.format(hex(num)[2:]))
else:
    print('Opção invalida')
