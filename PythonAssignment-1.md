723## 
#Assignment Part-1

Q1. Why do we call Python as a general purpose and high-level programming language?

ANS. Python is a human readable form of language or a human friendly language , where the source code is not written in 0 and 1. Hence it is called a high level programming language.

Q2. Why is Python called a dynamically typed language?

ANS. In languages where the declaration of a variable in regarding the datatype is not important , it is called a dynamically typed language.    

Q3. List some pros and cons of Python programming language?

ANS. PROS -> 1. Easy to understand as it is a high level programming language.
             2. It is a interpreted language , the lines are exeuted at the same time line by line which make debugging easy.
     CONS -> 1.It is slower than compiled languages.
             2.High memory consumption.   

Q4. In what all domains can we use Python?

ANS. 1.Machine learning / Artificial intelligence
     2.Web Developement
     3.Data analytics and data visualization 
     4.Game Developement
     5.Mobile app developement
 
Q5. What are variable and how can we declare them?

ANS. Variable is a name given to a specific memory location. 
    Declaring a variable:
         _a = 20
Variable name should start with any alphabet and '_' , no other special symbol is allowed.

Q6. How can we take an input from the user in Python?

ANS. We can take input from the user using the input()
     Ex - name = input()
          print("My name is ", name)
 

Q7. What is the default datatype of the value that has been taken as an input using input() function?

ANS. str

Q8. What is type casting?

ANS. Type casting is a method to convert a variable data type into another data type. There are 3 data type function are :
            1. int()
            2. float()
            3. str()

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
ANS. We can take multiple  input using split() with input().

Syntax : 
input().split(separator, maxsplit)

Q10. What are keywords?

ANS. Keywords in Python are reserved words that can not be used as a variable name, function name, or any other identifier. There are  a total of 
33 keywords in python.

Q11. Can we use keywords as a variable? Support your answer with reason.

ANS. No we cannot use keywords as a variable as it is already reserved for a specific purose and is predefined.

Q12. What is indentation? What's the use of indentaion in Python?

ANS. Indentation refers to adding white space before a statement to a particular block 
     of code. When writing blocks of code identation is more effectively used.

Q13. How can we throw some output in Python?

ANS. print()

Q14. What are operators in Python?

ANS. + , - , * , / , // , ** , %

Q15. What is difference between / and // operators?

ANS. / = float division
    // = integer division


Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
ANS. a = iNeuron 
     print(a*3)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
ANS.

x = input()
n = int(x)

if n%2==0:
  print("even")
else:
  print("odd")  


Q18. What are boolean operator?

ANS.AND, OR, NOT


Q19. What will the output of the following?
```
1 or 0
ANS. TRUE

0 and 0
ANS. FALSE
True and False and True
ANS.FALSE

1 or 0 or 0
ANS. TRUE

```

Q20. What are conditional statements in Python?

ANS.Conditional statements are decision making statements.While using if , else we can make conditional statement.

Q21. What is use of 'if', 'elif' and 'else' keywords?
ANS. 
If statement: It is used if a condition is true . When we use the if condition, we pass the argument and if the argument will be satisfied then the code will be executed otherwise nothing will happen.

elif statement:  If we want to work with extended conditonal parameters then we can use elif statement. 

else statement: The else statement is an optional statement that  can be combined with an if statement. An else statement contains the block of code that executes if the conditional expression in the if statement resolves to 0 or a FALSE value.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
ANS.
x = input()
age = int(x)
if age >= 18:
  print("You are "+ str(age) + " and eligible to vote")
elif age < 18:
  print("You are "+ str(age) + " and  not eligible to vote")  

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
ANS. 
x,y,z = input().split()
print("Number of number 1: ", x)
print("Number of number 2: ", y)
print("Number of number 3: ", z)
if x>y>z:
    print(x, "is the greatest number.")
elif y>x>z:
    print(y, "is the greatest number.")
else:
    print(z, "is the greatest number.")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ANS. 
numbers = [12, 75, 150, 180, 145, 525, 50]
a = [12, 75, 150, 180, 145, 525, 50]
b = []
for number in a:
    if number > 150:
        if number > 500:
            break
        continue
    if number % 5 == 0:
        b.append(number)
        
print(b)