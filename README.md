# Module-9-
Lab Activities 

#Module 9 Lab Activity


#Problem 1


i = 1 

while i < 2:
    print('Infinite')


#Problem 2


L = []
i=0
while i<=10:
    L.append(i)
    i=i+1
print(L)



#Problem 3

num1 = input('Enter first number: ')
num2 = input('Enter second number: ')

sum = float(num1) + float(num2)

print('The sum of {1} is {2}' .format(num1, num2, sum))

#Problem 4

counter = 0
tens=[]
while(counter<=50):
    if counter % 10 == 0:
        tens.append(counter)
    counter = counter + 1

print(tens)

