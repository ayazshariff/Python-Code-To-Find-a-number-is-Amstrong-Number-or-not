# Python-Code-To-Find-a-number-is-Amstrong-Number-or-not
Python Code to Find Out The Given Number Is Amstrong Or Not

#to find amstrong number

i = int(input('enter a number'))

if i in range(1,1000,1):
    sum = 0
    
    n= len(str(i))
    
    temp = i
    
    while(temp!=0):
        
        digit = temp%10
        
        sum = sum + digit**n
        
        temp = temp//10
    
    if i==sum:
        
        print("Number is Amstrong")
    
    else:
        
        print('Number is not Amstrong')

else:
    
    print("i not in range of 1 to 1000")

