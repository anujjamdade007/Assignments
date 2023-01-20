## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
because by python we make make many programs therefore we can called python as general purpose
and python is easy to understand for humans therefore python is called as high level language


Q2. Why is Python called a dynamically typed language?
pythone is very different from another languages in python we dont need to
declare any veriable and there are so many advantages of python therefore
python is called dynamically typed language


Q3. List some pros and cons of Python programming language?
pros
python is object oriented language
in python we dont need to declare to variable
there are so many libraries in python
cons
very simple because of programmer is becoming lasy



Q4. In what all domains can we use Python?
data science, data engineering, web development, machine learning, artificial intalligence




Q5. What are variable and how can we declare them?
variables is known as the name is given to memory location in python we dont want to declare it will 
automatically decleared



Q6. How can we take an input from the user in Python?
we can give input from user by "input()" by this way




Q7. What is the default datatype of the value that has been taken as an input using input() function?
the default database is string



Q8. What is type casting?
by the type casting we can change the data type of the given variable



Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
we cant give the multiple inputs from user by input()



Q10. What are keywords?
int,input,str,bool, print,if,else etc. these are the keywords




Q11. Can we use keywords as a variable? Support your answer with reason.
we cant give keywords as variable in python these keywords are reserved 



Q12. What is indentation? What's the use of indentaion in Python?



Q13. How can we throw some output in Python?
by print() function we can throw output



Q14. What are operators in Python?
there are so many operators like to add two number we can + operator 
these is called operator



Q15. What is difference between / and // operators?
/ operator is used for flot division 
// is used to integer division



Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron

a = "iNeuron"
a = a * 4
print(a)

```



Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

a = int(input("type any number you want you want to check if it is odd or not = "))
if (a % 2) == 0:
    print("the given number is not odd number")
else:
    print("the given number is odd number")





Q18. What are boolean operator?
boolen opereaters are true or false 



Q19. What will the output of the following?
```
1 or 0
true


0 and 0
false

True and False and True
false

1 or 0 or 0
true

```



Q20. What are conditional statements in Python?
in python if else is the comditional statement


Q21. What is use of 'if', 'elif' and 'else' keywords?
if we want compare two statements we can use these keywords



Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

a = int(input("write your age to check you are elligibale for voting or not = "))
if (a <= 18):
    print("you are not elligibale for voting")

else:
    print("you are elligible for voting")

 ```   




Q23. Write a code that displays the sum of all the even numbers from the given list.

numbers = [12, 75, 150, 180, 145, 525, 50]

numbers = [12, 75, 150, 180, 145, 525, 50]
print("sum of the give numbers is ", sum(numbers))

```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.


print("give three numbers to check greatest number")

a = int (input("write first number "))
b = int (input("write second number "))
c = int (input("write third number "))

print("the reatest number in given three numbers is ", max(a,b,c))

```


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
a = [12, 75, 150, 180, 145, 525, 50]
b = []
for i in a:
    if i > 150:
        if i > 500:
            break
        continue
    if i % 5 == 0:
        b.append(i)
        
print(b)


i copied this on google i dont know how to make loop when i understant then i solve it

thank you