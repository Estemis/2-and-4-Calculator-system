# Этот код был написан Estemis
# Репозироторий Estemis ссылка https://github.com/Estemis?tab=repositories


while True:
    print("Это калькулятор двух цифер напиши два числа")
    sc = int(input("Напиши первое число\n"))
    scr  = int(input("Напиши второе число\n"))
    skr = input("Выбери функцию\n1)Плюс;+\n2)Минус:-\n3)Умножение:*\n4)Деление:/\n5)Остаток от деления:%")
    if skr == "1":
        print(sc+scr)
    elif skr == "2":
        print(sc-scr)
    elif skr == "3":
        print(sc*scr)
    elif skr == "4":
        print(sc/scr)
    elif skr == "5":
        print(sc%scr)
