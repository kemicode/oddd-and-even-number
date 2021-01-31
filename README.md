# oddd-and-even-number
#Program that prompts the user to enter his/her age.
#Collaboration: none
#Write a program that prompts for an odd integer that is between 50 and 100,
#inclusive.
#Pseudocode
#start program
#prompt user for an odd number between 50 and 100
#input if number is divided by two and has no remainder, output number is even
#input else output number is odd
#End Program


#Start Program
#
#prompt user for an odd number between 50 and 100
num = int(input('Enter an odd number between 50 and 100'))

#Get if number is odd or even, output result
if (num % 2) == 0:
    print("{0} is Even".format(num))
else:
    print("{0} is Odd".format(num))

#End Program
