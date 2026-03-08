#rus version



#1





import random
from time import sleep

random_number = random.randint(1, 10)

print( "У вас 3 попытки!" )

user_number = input("Угадай число (от 1 до 10): ")
sleep(1)
print( "Загрузка информации (1.2%)" )
sleep(0.3)
print( "Загрузка информации (41.6%)" )
sleep(1)
print( "Загрузка информации (56%)" )
sleep(1)
print( "Загрузка информации (86%)" )
sleep(1)
print( "Загрузка информации (100%)" )


if user_number == random_number:
    print("Вы угадали!")

else:
    print( "Вы НЕ угадали :(" )
    sleep(1)
    print(f"Было загадано число {random_number}!")
    print(f"Ваше число: {user_number}")
    sleep(0.5)
    print( "У вас осталось 2 попытки!" )


#2


import random
from time import sleep

random_number = random.randint(1, 10)

user_number = input("Угадай число (от 1 до 10): ")
sleep(1)
print( "Загрузка информации (5.2%)" )
sleep(0.3)
print( "Загрузка информации (21.6%)" )
sleep(0.6)
print( "Загрузка информации (56%)" )
sleep(0.9)
print( "Загрузка информации (76%)" )
sleep(0.3)
print( "Загрузка информации (100%)" )


if user_number == random_number:
    print("Вы угадали!")

else:
    print( "Вы НЕ угадали :(" )
    sleep(1)
    print(f"Было загадано число {random_number}")
    print(f"Ваше число: {user_number}")
    sleep(0.5)
    print( "У вас осталось 1 попытка!" )


#3


import random
from time import sleep

random_number = random.randint(1, 10)

user_number = input("Угадай число (от 1 до 10): ")
sleep(1)
print( "Загрузка информации (5.2%)" )
sleep(0.3)
print( "Загрузка информации (11.6%)" )
sleep(0.6)
print( "Загрузка информации (56%)" )
sleep(0.9)
print( "Загрузка информации (96%)" )
sleep(0.7)
print( "Загрузка информации (100%)" )


if user_number == random_number:
    print("Вы угадали!")

else:
    print( "Вы НЕ угадали :(" )
    sleep(1)
    print(f"Было загадано число {random_number}")
    print(f"Ваше число: {user_number}")
    sleep(0.5)
    print( "У вас осталось 0 попыток!" )

sleep(1)
print("Повезет в следующий раз")
sleep(0.5)
print("Игра окончена")
sleep(0.2)
print( "Досвидание!" )
