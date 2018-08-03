# Aula 1 - LTP 1

pilha  = list(range(1, 11))
ultimo = len(pilha)

while True:
    print('Tamanho da pilha', len(pilha))
    print('Pilha Atual: ', pilha)

    operacao = input('Operação L, A ou S : ')

    if operacao == 'L':
        morto = pilha.pop(-1)
        print('Matei o', -1)
    elif operacao == 'A':
        pilha.append(ultimo + 1)
    elif operacao == 'S':
        print('Saindo do processo...')
        break

