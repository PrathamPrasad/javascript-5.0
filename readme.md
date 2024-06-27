What is javascript and why we used it ?

-Javascript is logic based programming language where we can create our code project functionality in that.
-Javascipt is a high level programming language for build web pages.
-Now we used the ES6(echma script 6) version of javascript, in other words we called vanilla javascript.
-Runtime environment of javascript is node js.

VARIABLE:

-Variable is container to store some data.
-In javascript we have 3 types of variables-
 1. let:
    -Let is a type of variable is used for changing the variable name later.
    -Now these days, most of the cases we used let for creating variable.
    -Let is a block scope code so we have been using let for most of the case.  
 2. var:
    -Var is a type of variable which is also used for caging the variable later satge.
    -Var is used in oldest browser so now a days we are dont use var most of the time.
 3. const:
    -Const  is a type of variable where we can't change our data further.
    -Const means constant to store some data like numbers, integer etc... .


Task:
1. Difference b/t Let & Var.
2. Difference b/t Var & Const.
3. What do you mean by hoisting?


RULES OF VARIABLE:
- Variable names are case sensitive "a" & "A" is different.
- Only letter, digit, underscore & $ is allowed(not even space).
- Only letter, underscore or $ should be 1st character.
- Reserver words cannot be variable names.

DATA TYPES in JAVASCRIPT:

- Data type is an attribute associated with a piece of data that tells a computer system how to interpret its value.
- In data types we used "typeof" operator to know that what type of data it is.
- Mainly in javascript there are 2 types of data type.
 1. Primitive:
   -In javascript there are 7 types of primitive data types.
   1.Number:-Number are the tpe of data type those it contain some numerical value.
   2.String:-String is a type of data type that can hold some character like names..
   3.Boolean:- In boolean data type we get Boolean value like true, false
   4.Undefined:- In undefined data type the data is not define so that it will show undefined.
   5.Null:- In this data type we get null for the value means nothing.
   6.Bigint:- In bigint we well get big integer.
   7.Symbol:- In symbol we will get whole symbol as well as the value we get for the data type.

 2. Non-primitive or Reference:
   -Non premitive data types are the types of data types that can hold multiple items in a single time.
   -Non primitive data types ae: abject, aray,function.
   1. Object:-
        - Object is anon primitive data types which can hold multiple of item in asingle time.
        -Mainly ojects are working on (key:value0 pair).
        -The left hand side is our keys and right hand side are the values of the following abjects.

        ex:

        Pratham={
         college:"GIET",
         address:"BBSR",
         age: 21,
         salary : 45000,
         carrier: "good"
        } 


OPERATOR  in JS:

- Operator are the key features to do some task or operate some task.
- Ex: A + B
- In the above example A & B are the operads, '+' is the opertaors to do the addition.
 1. ARITHMETIC OPERATORS:
   (+,-,*,/)
   Modulus = %
   Exponentiation = **
   Increment = ++
   Decrement = --
 2. unary operator:-
   Increment = ++
   Decrement = --
 3. Assignment operator :- (assign some value to the variables)
   (=, +=, -=, %=, **=)
 4. Comparison operator :- (compair the values)
        equal to -> ==
        not equal to -> !=
        equal to & type -> ===
        not equal to & type -> !==
        (>, >=, <, <=)

 5. Logical Operator :- checks the logic of the operator(true/false)
       Logical AND &&
       table of AND operator is :-
       cond 1, cond 2, res (&&)
       T + T = T
       T + F = F
       F + T = F
       F + F = F
       Logical OR ||
       Table of OR operator is :-
       cond 1, cond 2, res (||)
       T + T = T
       T + F = T
       F + T = T
       F + F = F
       Logical NOT !

conditional statement :-

- to implement some condition in the code.
- there are 3 types of conditional statements are there
1. if condition :-
    - if condition is true then statement is true otherwise false.
    syntax :-
    if(condition){
      statement
    }
2. if-else condition :-
    - if condition is true then block executed otherwise its terminate to else condition.
    syntax :-
    if(condition){
      statement
    }
3. else-is condition :-
   - It checks the condition multiple times where condition is true.
   syantax :-
   if(condition){
      statements;
   } else if(condtion){
      statements;
   } else{
      statements; 
   } 

Loops :-

- Loops are used to execute a piece of code again & again.

1. For Loop :-
syntax - 
for(initialization,condition,updation){
     statement
}
ex-
for(let i = 1; i <= 5; i++){
     console.log("web bocket)
}

2. While Loop :-
syntax - 
while(condition){
     statement
     updation
}

3. Do-While Loop :-
syntax - 
do{
     statement
     updation
}while (condition);

4. For-Of Loop :- It iterate on string and array.

5. For-in Loop :- It iterate over objects(key-value pair)
syntax - 
for(let key in objvar){
     statement
}

* home work *
1. print all even number from 0 to 100
2. create a game you start with any random game number, ask the user to keep guessing the game number untill the user enters correct value.
