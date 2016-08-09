from random import randint

print "This is a guessing game."

print "You will have three chances to guess a number between 1 and 10."

answer = randint(1,10)

for turn in range(3):
    guess = input("Guess a number")
    if guess == answer:
        print "Well done!"
        break
    elif turn == 2:
        print "You are a failure"
    else:
        if guess > answer:
            print "Lower"
        elif guess < answer:
            print "Higher"
