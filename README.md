# Node-JS-Interview-Questions

JS-1

Question 1: What is difference between let and const? What is the difference between let and var?
Question 2 : what is output of this function
function sample (){

for (let i=0; i<=5;i++){
setTimeout (() => Console.log(i), 1000 );

}
}

Question 3 : what is output of this
SetTimeout(()=>{
Console.log("a");
},2000)
Console.log("b") ;

Question 4: how can you print a first and b later with. You are not allowed to use any extra setTimeouts?
Question 6 : what is process.nextTick ?
Question 7: how can you check if a variable is an array?
Question 8 : Do You know Sql ? What is difference between truncate and delete?
Question 9: Do you have any about indexing the table ?

JS-2
Question 1: What is output of this (refer this if you dont know about setimmediate - https://www.educative.io/edpresso/what-is-setimmediate-in-nodejs)

SetImmidiate (()=>{
Console.log("first")
})
SetTimeout (()=>{
Console.log("second")
})
Console.log("third");

Question 2 : Difference between SetImmidiate and Process.nexttick
Question 3: What is difference between promise and call back
Question 4 : What is output ?

 Let a=New Promise((resolve,reject)=>{
reject ({ msg: 'Something went wrong' ))
})
a.then(ressolve=>{console.log{ressolve}}).catch(err=>{console.log(err.msg) })

Question 5 : what is output ?

await delay(6000)
SetTimeout (()=>{
console.log("first")
},10000)
console.log("second");

Question 6: What is function definition ?

JS-3
Explain these answers in details with examples

Difference between let, var and const
Hosting, callbacks, ES6 features
Difference between array.map and array.filter
How to find the length of an object
What are promises? 3 states of promises.
Why do we use promises over callbacks and why use await and async?

JS-4
1. Explain in detail the answers to the following questions with examples
2. What is the temporal dead zone?
Const person=
{
Name:p1,
Age:24
}

1. Can we change age to 25? 
2. Can we do person.push(age:25);
3. Write a function to generate random number between 10 and 99?
4. Difference between settimeout, setinterval setimmediate?
5. Difference between null and undefined
6. Difference between undeclared and undefined

JS-5

1. Difference between ‘==’ and’ ===’ ? (2)
Spread and rest operators
[a,...b,]=[1,2,3,4,5]

2. What are a and b values?
3. const fun = () => arguments.length;
console.log(fun(1,2));

 What is the output?
4. Let str=”JavaScript=Node=Express”;  replace “=” with “.”?
5. Reverse the string given str=”India” to "aidnI"
6. Let arr=[7,8,9,10]

Write a function to check if the given number "n" exists in the array.

If present remove the number from the array , return the remaining array excluding the number else print element not present.

Example Input 1
arr=[7,8,9,10] , n=8
Output
arr=[7,9,10]

Example Input 2

arr=[7,8,9,10] , n=10
Output
"Element not present"

JS-6

1)When do we use async await ?
2)What is the reason behind writing await inside async function only?
3)What will the output of this be?

async fun fun1(){
console.log('a');
console.log('b');
await setTimeout(() => console.log('c'), 1000)
await setTimeout(() => console.log('d'), 0)
console.log('e');
}
fun1()
Explain the reason behind the answer?

4) can you solve thee above problem, so that we get proper outputs ? Hint await should works properly.
5) What are callback? What is Callback hell? Can you give an example of callback hell?
6) How are promises more superior than callbacks? How do promises solve the issue of callback hell?

JS-7

1) What were the 10 new features that were introduced in ES6? Explain each one of them in detail? You will be asked questions on each example you give?
2) Call, Apply, Bind. When to use what ? Can you give an example?
3) What are different ways to store data in browser? Explain each one of them and when should we use what?
4)What are generator function in javascript ? How are they different from normal function?
5)Difference between arr.foreach,  array.map and array.filter? Take example  input array and explain the output which you will get
6)What is the use of arr.reduce? Explain with an example.

JS-8

1) what is the difference between == And ===
2) What is the difference between null and undefined?
3) what will the output (true or false) of the following be?Explain why?
console.log(null === undefined)
console.log(null == undefined)
4)What is event bubbling and event capturing (Event Propagation)? what is the difference between them? Can you give a code  example to explain how you can use event bubbling ?
5)What is function currying? Can you create a curried function and explain?
6) What is an IIFE (Immediately Invoked function expression)? Can you give an example?

JS-9
Explain the different ways of creating object in javascript? Explain all the 3 ways.
What are Object Prototype Methods
What is object chaining in javascript? Can you create functions to explain object chaining better?
What is the main difference between fat arrow function and normal function?
Can you give an example to explain how "this" works differenetly with fat arrow function and normal function?
What are the advantages of Axios vs other competitors( like fetch, http, got etc)? Why is axios so widely used?
What are closures? Explain with an example? (Favourite interview question)

JS-10
How to iterate inside and object and print all the values inside it without the keys? Give a code example?
What is NaN property in JavaScript?
Explain pass by value and pass by reference? Give code example of how you would pass by reference in javascript?
Explain “this” keyword?
What is memoization in javascript? Can you give a code example implementing the same?
What is the data type of variables in JavaScript?
 What are escape characters? Why are they used? Give code example.
What is break and continue statements? How are they different?
What is the typeof an array in javascript?
What are anonymous functions in js? Give an example?
What's the difference between event.preventDefault() and event.stopPropagation() methods in JavaScript?
 What are higher order function ? Explain with code example. Watch this video to understand better
 https://youtu.be/HkWxvB1RJq0
 
 SQL-1
 
1. https://www.mygreatlearning.com/blog/sql-interview-questions/
2. What is Sequelize and why it is used
3. Why you are using MySql and why not NoSQL in the project?
4. What are views in MqSql?
5. How to connect sequelize to database?
6. What are joins ? Explain the different types of joins and their uses?
7. What are MySQL Triggers? Watch this video and explain it in your own words here.
https://youtu.be/gy6LY0Xy2zU
8. What is Sharding in SQL? Go through this video and answer in your own words and explain it in your own words here.
https://youtu.be/5faMjKuB9bc
9. What is BLOB -> First watch this video and then go through this answer and explain it in your own words here.
https://youtu.be/Jw1wLldeLlQ
10. What is BLOB in MySQL? Watch this video and explain it in your own words here.
https://youtu.be/_HZdLuGL8Ho

SQL-2

What are JOINS?Explain each of the 4 joins.
Write an SQL query to demonstrate joins ?
What are constraints in SQL? Explain 5 of them.
What is UNIQUE constraint?
What are primary keys and foreign keys.When to use what ? Explain with an example.
What is the difference betwen primary key and unique key?

SQL-3

What is a subquery? What are its various types?
Can you give an example where you might use subquery
What is the use of UNION keyword in SQL? Write an example query.
What are Entities and Relationship (ER)?
What are the differents types of relationships which are there?
Can you make an ER Diagram of any one of your past projects and explain it and explain how you handled all the different types of relationship as mentioned above?

SQL-4

What is a view ? (Commonly asked)
Why do we even need Views?
What is normalisation of database?
What are Delete, Truncate and DROP keywords?
How are they different from each other?
What is Indexing? What is the advantage of indexing and what is the disadvantage?
How to create an index in SQL? Please write the query . Use the example of any table that you have used before.
 If we drop a table, does it also drop related objects like constraints, indexes, columns, default, views and sorted procedures?
 
 SQL-5
 
 What is the difference between IN and BETWEERN Operator?
How to write an SQL query to find students' names start with 'A'?
Write the SQL query to get the third maximum salary of an employee from a table named employees.You have to use OFFSET as other algos are not optimised. (Assume whatever you want to) - [Commonly asked Interview Question]
What is the ACID property in a database? Explain each one of them .
What is a deadlock in SQL?
Is a blank space or zero the same as a NULL value?
What is the usage of the NVL() function?
What is SQL Injection?

SQL-6

Write a Query to display the number of employees working in each region? 
Write SQL query to fetch employee names having a salary greater than or equal to 20000 and less than or equal 10000.
 Given a table Employee having columns empName and empId, what will be the result of the SQL query below? select empName from Employee order by 2 asc;
How to delete a column in SQL? Please write the query.
 How to find the nth highest salary in SQL?
How to add a new column in SQL?
Write a Query to display odd records from student table?
How to fetch alternate records from a table?
Write a Query to display employee details belongs to ECE department?

SQL-7

What is BLOB and TEXT in MySQL?
How do you return a hundred books starting from 105th? Write the query. Make required assumptions.
How would you select all the users, whose email id and phone number is NULL?
Write an SQL query to fetch five max salaries from a table.
How do you get the  second last id without the max function?
Write a query to find out the data between the age range of 25 to 35 from employee table?

NODE JS-1

What are the advantages of Node Js?
What is module.exports ?
what are default exports?
What is cors?
What are REST APIs? How does it work?
What is Event loop? (Watch this video to understnad event loop in detail)
https://youtu.be/EI7sN1dDwcY

NODE JS-2

What is expressJS?
Node js is single threaded or multithreaded?
If node js is single threaded then how does it handle concurrency?
What are the different Http methods? Explain when to use what?
In SQL what is primary key and foreign key?
What are middlewares and what does next() function do?
Which module is used to read and write operations in a file?

NODE JS-3

What are web servers? How are they different from your laptop
Write a SQL query to demonstrate joins and order by? Take any table example.
What are classes in javascript?
What are constructors? what does super() do in js?
What are destructors? when are they called?
Explain garbage collection in js.? When is a variable garbage collected?
How do you do error logging in your application?

NODE JS-4

What is abstraction and encapsulation
What is a jwt token ? How do you create a jwt token?
Explain the flow of login and authentication? How does the backend identify the user?
When you create a jwt token , how do you expire it after a certain amount of time?  [Common question]
What is the difference between Delete and truncate in sql
What are the different kinds of joins? Explain each one of them?

NODE JS-5

Explain the steps for deploying the code to AWS?
What all files will you add to .gitignore file?
What is the use of pm2 ? What advantage does it give?
What are the different pm2 commands that you have used?
What is the use package json file?
What is the use of packagelock.json?Why do we even need it?
What is the difference between dependencies and devdependencies in package.json? When to use what?

NODE JS-6

1. What is a first class function in Javascript?
2. What is Node.js and how it works?
3. What are some commonly used timing features of Node.js?
4. What is fork in node JS?
5. How many types of API functions are there in Node.js?
6.What do you understand by callback hell?
7. If Node.js is single threaded then how does it handle concurrency? (This is a good resource for understanding )
https://www.geeksforgeeks.org/if-node-js-is-single-threaded-then-how-to-handles-concurrency/
8. What is node.js streams?
9. What are node.js buffers?
10. Describe the 5 exit codes of Node.js?

NODE JS-7

1) Enhancing Node.js performance through clustering. How can you do this via forking?Can you write the code?
2) What is the difference between fork() and spawn() methods in Node.js?
3) What are some of the flags used in the read/write operations in files?
4) What is a reactor and proactor pattern in Node.js? Watch this video and explain in your own words?
https://youtu.be/Vm5l8zH4hOE
5) What is the purpose of NODE_ENV? Why do we even need the different environments like production and staging? 
 
