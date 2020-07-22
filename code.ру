import random 
s=input('Выбери(К-Камень,Н-ножницы,Б-бумага):')
k=['К','Н','Б']
player1=random.choice(k)
print(player1)

if s in ('К','Н','Б'):
    if s==player1:
        print('Ничья')
    elif s=='К' and player1=='Н':
        print('Вы победили')
    elif s=='К' and player1=='Б':
        print('Вы проиграли')
    elif s=='Н' and player1=='Б':
        print('Вы победили')
    elif s=='Н' and player1=='К':
        print('Вы проиграли')
    elif s=='Б' and player1=='Н':
        print('Вы проиграли')
    elif s=='Б' and player1=='Б':
            print('Вы победили')
else:
    print('Неверно введен символ!')
