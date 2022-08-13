import random

chars = 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ12345678#*$!()@;'

while 1:
    password_len = int(input('What length would you want your password: '))
    password_count = int(input('How many passwords would you like: '))
    for x in range(0,password_count):
        password = ''
        for x in range(0,password_len):
            password_char = random.choice(chars)
            password      = password + password_char
        print('here is your password : ', password)
