# bmi1.0
print("Эта программа поможет узнать Ваш идеальный вес основываясь на некоторых Ваших параметрах.\nНажмите Enter для продолжения")

d=str(input())
g=("bmi")

#name=str(int(input("Как Вас зовут? ")))
print("Как Вас зовут? ")
name=input()
print("здравствуйте,"+name+".\nСейчас мы будем собирать данные о Вас.")

age=int(input("Сколько вам лет? "))
height=int(input("Какой Ваш рост (в см)? "))
weight=int(input("Введите свой вес: "))
gender=str(input("Ваш пол: М/Ж "))

if d==("М", "м"):
	print(d, "Мужской")

elif d=="Ж":
	print(d, "Женский")
#не принтует пол

print("ваш имт составляет: ")
print(weight/(height*2))

#else
	
