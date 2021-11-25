# Python
program that asks a user to enter a specific word requested by the program:


word = 'Good Morning'
user_word = input('Type the word "' + word + '":')
while user_word != word:
    user_word = input('Try again!: ')
print('Correct!')
