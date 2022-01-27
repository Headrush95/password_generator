import random


def generate_password(length1, chars):
    password = ''
    for _ in range(length1):
        password += random.choice(chars)
    return password


digits = '0123456789'
lc_letters = 'abcdefghijklmnopqrstuvwxyz'
uc_letters = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
sim = '!#$%&*+-=?@^_'
char = ''
n = int(input('Сколько паролей нужно сгенерировапть?   '))
length = int(input('Какая длина одного пароля?    '))
if input('Включать ли цифры? y or n    ') == 'y':
    char += digits
if input('Включать ли прописные буквы? y or n    ') == 'y':
    char += uc_letters
if input('Включать ли строчные буквы? y or n    ') == 'y':
    char += lc_letters
if input('Включать ли символы? y or n    ') == 'y':
    char += sim
if input('Включать ли неоднозначные символы? y or n    ') == 'n':
    for c in 'il1Lo0O':
            char = char.replace(c, '')
for _ in range(n):
    print(generate_password(length, char))
