ligou = False
atendeu = True
ligou = True
nao_atendi = False

print('if ligou == True and nao_atendi == False:')
data = input('qual é o dia da semana (no caso de terça, colocar terca): ')
horario = input('periodo do dia [manha, tarde ou noite] (sem acento): ')

if ligou == True and nao_atendi == False:

   while data != 'segunda' and data != 'terca' and data != 'quarta' and data != 'quinta' and data != 'sexta' and data != 'sabado' and data != 'domingo':
        data = input(f'{data} tem algum caracter errado, tente novamente: ')
        data = data

   while horario != 'manha' and horario != 'tarde' and horario != 'noite':
        horario = input(f'{horario} tem algum caracter errado, tente novamente: ')
        horario = horario
    

  if data == 'segunda' or data == 'quarta':
        if horario == 'manha':
            print('to estudando')
        elif horario == 'tarde':
            print('to nadando')
        elif horario == 'noite':
            print('to estudando ingles')
    
  elif data == 'terca':
        if horario == 'manha':
            print('to estudando')
        elif horario == 'tarde':
            print('to trabalhando ou estudando')
        elif horario == 'noite':
            print('to querendo dormir')

   elif data == 'quinta' or data == 'sexta':
        if horario == 'manha':
            print('to estudando')
        elif horario == 'tarde':
            print('to nadando')
        elif horario == 'noite':
            print('to estudando')

   else:
        print('nao quero atender')
