
import time  #this will help you to create a delay 
name = input('Whats your name?')
greetings = input('How are you? ' +  name )
time.sleep(3)
print( name  + ' We are going to play a game ')
time.sleep(3)
print('Think in any number, then write this number down in a piece of paper')
time.sleep(5)
Help = input('Did you write the number')
if Help == 'yes':
    print('we go to the next question then')
else:
    print('you have 10 seconds' )
    time.sleep(10)
print('Now get the number you thought and  multiply it by 2')
time.sleep(5)
print('Now get this result and add a number')
a = float(input('Please any number'))#The user will input a number here, the system will store it
print('Thank you')
time.sleep(3)
print('Now get the result and divide by 2')
time.sleep(3)
print('Now get this result and subtract by the first number you thought')
b_float = a/2 #this will get the number add and divide by 2 and give the result
print('Wait a minute I am calculating the results')
time.sleep(5)
print('The Result is ' + str(b_float))
Result = input('Did I get the number')
if Result == 'yes':
    print('Oh, Great!!')
else:
    print('You cheater' )
print('See you soon ' + name)








