import random

def adivinhar_numero():
    numero_secreto = random.randint(1, 100)
    tentativas = 0

    while True:
        try:
            palpite = int(input('Tente adivinhar o numero (1-100): '))

            if not 1 <= palpite <= 100:
                raise ValueError('Numero fora do intervalo! Digite um número que está entre (1-100)')
            
            tentativas += 1

            if palpite < numero_secreto:
                print('Muito Baixo! Tente Novamente.')
            elif palpite > numero_secreto:
                print('Muito Alto! Tente novamente')
            else:
                print(f'PARABÉNS! Você acertou o número {numero_secreto} em {tentativas} tentativas')
                break
        except ValueError as e:
            print(f'Entrada inválida: {e}')
adivinhar_numero()
