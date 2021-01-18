# hello_world
This is a test repository for Matt to practice storing code in GitHub.  Anything in here can be deleted without worry.

prompt = 'What was your score on the test?'
score = input(prompt)
score1 = float(score)

if score1 == 1.0 :
    print('Wow! Perfect score.')
elif score1 > 0.9 :
    print('You made an A.')
elif score1 > 0.8 :
    print('You made a B.')
elif score1 > 0.7 :
    print('You made a C.')
elif score1 > 0.6 :
    print('You made a D.')
else:
    print('You failed...')
