# 11-
Гурьянова Станислава
номер 1
a = 42
b = 3.14159
c = "Hello, Python!"
d = True
e = [1, 2, 3]
f = (4, 5, 6)
g = {"name": "Alice", "age": 30}
h = {7, 8, 9}
i = None

print(type(a))
print(type(b))
print(type(c))
print(type(d))
print(type(e))
print(type(f))
print(type(g))
print(type(h))
print(type(i))

номер 2
my_list = [1, 2, 3]
print(my_list)
my_list[0] = 130 #первое значение в списке начинается с 0, из-за этого я поменял первое число на 130. Значение поменялось
print(my_list)

my_tuple = (1, 2, 3)
print(my_tuple)
my_tuple[0] = 1001 #при попытке изменить первое значение выдает ошибку TypeError: 'tuple' object does not support item assignment, следовательно нельзя менять кортеж
print(my_tuple)

my_string = "cat"
print(my_string)
my_string[0] = 'b' #при попытке изменить букву выдает ошибку TypeError: 'str' object does not support item assignment, следовательно нельзя менять строку
print(my_string)

номер 3
try:
    a = input()
    b = input()
    a = int(a)
    b = int(b)
    print(a+b)
except ValueError:
    print("неправильный ввод символов")
