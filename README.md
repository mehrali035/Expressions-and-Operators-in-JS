# Expressions-and-Operators-in-JS 


/**** 3 👉 EXPRESSION AND OPERATORS in JavaScript ****/

// console.log(5 + 20); =25 ( 5 and 20 operand and '+' is operator) 
// (operator+operand= is called expression)

// 6 Types of operators


//  No.i ASSIGNMENT OPERATOR (=)  ( assign a value to its left operand)


// var x = 5
// var y = 5
// console.log("is both x and y are equal or not" + x == y);  // false becos we add + 
// console.log(x == y);   //true 
// console.log('is both the x and y are equal : ${x == y}'); true , becoz new method in ECMA 


// No.ii ARITHMATIC OPERATOR 
// (Takes numerical value as their operand and returns a single numeric value like ,3+3=6)


// console.log(3+3);  =6
// console.log(10-5);  =5
// console.log(20/5);  =4
// console.log(5*6);   =30
//console.log("remainder operator " + 27%4); //remainder operator =3

// No.iii Increment and Decrement operator
// operator x++ or ++x , x--  or  --x
// if used postfix like, x++. (the incre operator increm and return the value before incrementing)


// var num = 15;
// var newnum = num++ + 7;
// console.log(num);
// console.log(num++);

// //if use prefix (the variable is incremented first and then the expression is evaluated
// // using new value of the variable)


// var num = 15;
// var newnum = ++num + 5;
// console.log(num);    //= 16 and then 21
// console.log(newnum);

// var num = 15;
// var newnum = num-- + 5;
// console.log(num);       // =14 then 20
// console.log(newnum);

// var num = 15;
// var newnum = --num + 5;
// console.log(num);    
// console.log(newnum);

// No.iv  COMPARISON OPERATORS 
// (compares its operands and returns a logical value based on weather comparison is true.)

 
// var a = 30;
// var b = 10;
// // equal operator
// console.log(a == b);

// var a = 30;
// var b = 10;
// // not equal to 
// console.log(a != b);

// var a = 30;
// var b = 10;
// // gretaer than 
// console.log(a > b);

// var a =30;
// var b =10;
// // greater than or equal to 
// console.log(a >= b);

// var a = 30;
//  var b = 10;
// // //  less than 
// console.log(a < b);

// // less than or equal to 
// console.log(a <= b);

// No.V LOGICAL OPERATORS (logical conjunction values are typically used with boolean values,
// they return boolean value,true or false)


// var a = 30;
// var b = -20;


// logical AND (&&) (Logical conjunction for a set of operands is true if and only if
//  all its expression are true)
//console.log(a > b && b > 0); //all expression must be true 



// logical OR (||) (logical disjunction  for a set of operands is true if and only if 
// one oe more of its expression is true)
//console.log((a > b) || (b < 0) );


// Logical NOT (!) (logical complements ,negation takes truth to false and vice vers)
// console.log(!((a < b) || (b > 0))); //complete expression in one paranthysis


// strings concatenation (operator)
// the concatenation operator + concatenates two string values together,
// return another string that is the union of two operand stirngs.


// console.log("hello " + "world"); hello world (for space between strings add space in qomma)
//  conditional (ternary) operator ,(see later in if else statements)



// console.log(3**3); =27
// console.log("hello" + 5); concatenates
//console.log(5 - "hello"); // =NaN 


// var a = 5;
// var b = 10;
// output needed b=5 and a=10
// var c = b //c = 10
// b = a; //b=5
// a = c;
// console.log("tha value of a " + a);
// console.log("the value of b " + b);


//  without adding c 
// var a = 5;
// var b = 10;
// // output needed b=5 and a=10
// a = a + b; //a=15
// b = a - b; //b=5
// a = a - b; //a=10

// console.log("tha value of a " + a);
// console.log("the value of b " + b);



// var num1 = 5;
// var num2 = '5';
// console.log(typeof(num1));
// console.log(typeof(num2));
// console.log(num1 == num2);


// var num1 = 5;
// var num2 = '5';
// console.log(typeof(num1));
// console.log(typeof(num2));
// console.log(num1 === num2);
// (== check only value and === check value and data typr of that value) 
