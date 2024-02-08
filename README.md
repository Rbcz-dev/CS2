print("Olá bem-vindo a calculadora rbcz")
opcao=input('digite qual operação você deseja usa -,*,**,/,+: ')

def brain ():  
    
    if opcao == '+':
        som()
    elif opcao == '-':
        sub()
    elif opcao == '*':
        mult()
    elif opcao == '/':
        div()
    elif opcao == '**':
        elev()
    else:
        print('Não tem este calculo, volte mais tarde.')

def sub():
    a1=int(input('digite o numero: '))
    a2=int(input('digite o numero: '))
    print(a1-a2)
    
def som():
    b1=int(input('digite o numero: '))
    b2=int(input('digite o numero: '))
    print(b1+b2)

def mult():
    c1=int(input('digite o numero: '))
    c2=int(input('digite o numero: '))
    print(c1*c2)
    
def div():
    d1=int(input('digite o numero: '))
    d2=int(input('digite o numero: '))
    print(d1/d2)
    
def elev():
    e1=int(input('digite o numero: '))
    e2=int(input('digite o numero: '))
    print(e1**e2)

brain()
