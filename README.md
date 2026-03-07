# treino
codigos de estudo
login = 'adm'
senha = '0987'

if login == 'adm' and senha == '0987':
    print('acesso adm')
else:
    if login == 'gerente' and senha == '1234':
        print('acesso gerente')
    else:
        if login == 'vendedor' and senha == '5656':
            print('acesso vendedor')
        else:
            print('acesso negado')
