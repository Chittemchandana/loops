# loops
#for
languages = ['Swift', 'Python', 'Go']

# access elements of the list one by one
for i in languages:
    print(i)

loop through a string
language = 'Python'
# iterate over each character in language
for x in language:
    print(x)

#for Loop with Python range()
# iterate from i = 0 to i = 3
for i in range(4):
    print(i)

#Python while Loop
number = 1

while number <= 3:
    print(number)
    number = number + 1

#Python while Loop example
# Calculate the sum of numbers until user enters 0
number = int(input('Enter a number: '))

total = 0

# iterate until the user enters 0
while number != 0:
    total += number
    number = int(input('Enter a number: '))

print('The sum is', total)

#Infinite while Loop
age = 32
# the test condition is always True
while age > 18:
    print('You can vote')
