a=int(input())   #// input is taken from user
sum=0             #// sum declared value with 0
for i in range(1,a+1):           #// for loop range take from 1 to 50+1 because range 1 to fifty if executed only 49 so we can use "+1" in will run or else executed 1 to 50 
    sum+=i                        #//sum intially 0 and then it loop run i becaomes until of range and add in each i value in sum
                                  #// if sum is 0 sum+=i means sum+=1 sum is updated in i now the 1 same process will be continued in until range
print("The sum of numbers 1 TO 50 is :",sum) #//finally print value of 1 to 50 by aad ing each number








a=int(input("Enter the number: "))   *//take a input from the user
if(a%2!=0):                            // condition of checking the input to decide the compiler in even or odd
    print(a,"is the Odd number")      *// it even it will be odd printed 
else:
    print(a,"is the Even number")        else block is executed the condition false then automatically it becomes the even
