# jsapp1

Type Coercion

console.log(firstname + ' ' + age); //John 28 //automatically convert 28 i.e., integer/boolean/undefined to string to concatenate

Variable mutation
age = "twenty eight";

 var person = prompt("Please enter your name", "Harry Potter"); //first parameter is ques, second is the default ans

 Operator precedence table link
 https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence

 var x,y;
 x = y = 123; //right to left
 console.log(x,y);

 operator works left to right but assignment works right to left
  x += 10;
  x++ shortest way to add 1

falsy values: undefined , null , 0 , '' , NaN
truthy values: Not falsy values
