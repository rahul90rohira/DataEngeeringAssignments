## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
because this programming lang used to solve wide range of problems and its syntax etc is easy to understand

Q2. Why is Python called a dynamically typed language?
because we do not require to provide the data type while variable declare or initialize


Q3. List some pros and cons of Python programming language?
Pros-
Easy to learn and read
Vast collection of libraries 

Cons-
Consume lot of memory space 
Speed limitations

Q4. In what all domains can we use Python?
API Development,ML /AI,bigdata, test automation etc

Q5. What are variable and how can we declare them?
x=10; y="rahul" ,isEnabled=False

Q6. How can we take an input from the user in Python?
x=input("Take input")

Q7. What is the default datatype of the value that has been taken as an input using input() function?
string

Q8. What is type casting?
Typecasting is a concept to change the type of variable or object
in order to convert float to integer ---> int(<floatvalue>)
in order to convert -->bool(<any data type>)

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Yes we can take multiple input from single input function .But need to split it later into diff variable
a,b,c=input().split()--split by space
a,b,c=input().split(',')---split by commma


Q10. What are keywords?
Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes like if ,else ,elif, switch-case etc


Q11. Can we use keywords as a variable? Support your answer with reason.
No .We cannot use keyword as variable . It will throw compile time error

Q12. What is indentation? What's the use of indentaion in Python?
python is indentation level programming . Indentation here is 4 spaces .
If we need to define all class level element then need to follow indentation

Q13. How can we throw some output in Python?
print statement

Q14. What are operators in Python?
Arithmatic,Assignment ,Comparison,Logical,Bitwise,membership operator

Q15. What is difference between / and // operators?
Float and integer divison

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
print(r"```","\n","iNeuroniNeuroniNeuroniNeuron","\n ```")


Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
try :
    num=int(input("enter number"))

    if num %2 ==0 :
        print("even")
    else :
        print("odd")
except Exception as e :
   print("invalid input",e)


Q18. What are boolean operator?
which return true or false like --  >,<,AND , OR ,<>

Q19. What will the output of the following?
```
1 or 0  ---True

0 and 0--_False

True and False and True--False

1 or 0 or 0--True
```

Q20. What are conditional statements in Python?
if ,else ,elif

Q21. What is use of 'if', 'elif' and 'else' keywords?
in order to check conditions

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

age=int(input("Enter your age"))
print("I can vote") if age >=18 else print("I can't vote")


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]

ls=[12, 75, 150, 180, 145, 525, 50]
print(sum(filter(lambda x:x%2==0,ls)))
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
num1,num2,num3=input("Enter 3 no seperated by comma").split(",")
max = num1 if int(num1)>int(num2) else num2
max = num3 if int(num3)>int(max) else max
print(max)


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]

numbers = [12, 75, 150, 180, 145, 525, 50]
for x in numbers :
    if x%5==0 :
        if x > 500 :
            print(x)
            break
        elif x > 150 :
            continue
        else:
            print(x)
```
