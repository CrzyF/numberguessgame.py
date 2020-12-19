import random

for i in range(10):
    int(random.randint(1, 10))

    secret_number = int(random.randint(1, 10))
    guess_count = 0
    guess_limit = 3
    while guess_count < guess_limit:
        guess = int(input('Guess: '))
        guess_count += 1
        if guess == int(random.randint(1, 10)):
            print('You Won!')
            break
        else:
            print('...oops wrong answer')
