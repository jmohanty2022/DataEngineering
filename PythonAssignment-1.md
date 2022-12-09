## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
    It's called high level langauge because the code we write is understanable. 

Q2. Why is Python called a dynamically typed language?
    As it does calculate the variable type based on the input.

Q3. List some pros and cons of Python programming language?
    
pros:
   It's very easy to learn as it's similar to engligh langauage.
   it can be used to create a website along with other usage. 

Q4. In what all domains can we use Python?
    web development
    datascience
    os development
    gaming

Q5. What are variable and how can we declare them?
    variable is a temporary memory location and it's dynamic in python
    Ex:
    var_int=5
    var_str="Jyoti"
    
Q6. How can we take an input from the user in Python?
    Here is the command to take input from python
    input() 
    
Q7. What is the default datatype of the value that has been taken as an input using input() function?
    string
Q8. What is type casting?
    when we change the datatype of a variable on the runtime.
    
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
    it's takes only one input by default.
    
Q10. What are keywords?
     Keywords are reserve words in Python.
     Value key words like true,false and operator keywords like and,or not

Q11. Can we use keywords as a variable? Support your answer with reason.
     No
Q12. What is indentation? What's the use of indentaion in Python?
     It refrers to the spaces at the begning to the code of the line.it uses indentation to indicate a block of a code

Q13. How can we throw some output in Python?
     print () function

Q14. What are operators in Python?
     + addition
     - subtract
     * multiplication
     / float division
     // intiger division
     ** power calculation
     % moduluos 

Q15. What is difference between / and // operators?
     / provides the floating value where as // provide the resualt without floating value  

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Here is the code

var_str='iNeuron'*4
print(var_str)


Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

num_enter=input("Enter the number to check odd/even")
num_enter=int(num_enter)

if (num_enter%2)==0:
	print("it a even number")
else:
	print("it an odd number")

Q18. What are boolean operator?
     it provides true or flase statement.

Q19. What will the output of the following?
```
1 or 0   --> True
 
0 and 0  --> True

True and False and True

1 or 0 or 0 --> True
```

Q20. What are conditional statements in Python?
     euals to ==
     not euals !=
     less than <
     greater than >
     lessthan or eual to <=
     greaterthan or eual to >=

Q21. What is use of 'if', 'elif' and 'else' keywords?
     starts the block with if statement and elif is used between if and else statement
     elase is used if none of the criteria is satisfied inside the if block 
     
Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
    
Age_var=int(input("Please enter the age:"))
if (Age_var>18):
	print("I can vote")
else:
	print("I can't vote")

     
Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers_var = [12, 75, 150, 180, 145, 525, 50]
sum = 0
for i in numbers_var:
    for j in str(i):
     
        if int(j)%2 == 0:
            sum = int(j)+sum
            
print("even digit sum: " + str(sum))   

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

num_1= float(input("Enter 1st number: "))         
num_2= float(input("Enter 2nd number: ")) 
num_3= float(input("Enter 3rd number: ")) 

if (num_1 >= num_2) and (num_1>=num_3):
    largest=num_1
elif (num_2 >= num_3) and (num_2 >= num_1 ):
    largest=num_2
else:
    largest=num_3
print("The largest number is ",largest)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

x=[]
for i in numbers:
    if(i>500):
        break
    elif(i%5==0 and i<=150):
        x.append(i)
