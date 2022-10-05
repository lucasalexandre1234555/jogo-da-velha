

lista =('''
        1 2 3
        4 5 6 
        7 8 9
        ''')

p1=""
p2=""
def tabela():
    print("1 2 3\n4 5 6\n7 8 9")

def player1():
    global lista
    global p1
    posicao_p1 = input("P1-escolha a posição:")
    for i in lista:
        if posicao_p1 == i in lista:
            lista = lista.replace(f"{i}", f"{p1}")
            print(lista)

def player2():
    global lista
    global p2
    posicao_p2 = input("P2-escolha a posição:")
    for i in lista:
        if posicao_p2 == i in lista:
            lista = lista.replace(f"{i}", f"{p2}")
            print(lista)


sinal=input("player1: * ou #:").upper()
while True:
    if sinal=="*":
        p1=sinal
        p2="#"
        print(f"\nplayer 1:{p1}\nplayer 2:{p2}\n")

    elif sinal=="#":
        p1=sinal
        p2="*"
        print(f"\nplayer 1:{p1}\nplayer 2:{p2}\n")

    print(lista)
    player1()
    player2()
