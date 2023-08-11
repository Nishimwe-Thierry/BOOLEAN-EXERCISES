# Part 1
### Write down what the following statements will return. Try to figure this out before putting the commands in the chrome console. 
1. 2 == "2"; (this will return true)
2. 2 === 2; (this will return true)
3. 10 % 3; (this will return 1)
4. 10 % 3 === 1; (this will return true)
5. true && false; (this will return fasle)
6. false || true; (this will return true)
7. true || false; (this will return true)
# Part 2
### Answer the following questions about this code block:
##### (a)
let isLearning = true;
if(isLearning){
    console.log("Keep it up!");
} else {
    console.log("Pretty sure you are learning....");
}

1. What should the above code console.log?
::: it will : keep it up!
2. (i)Why do we not need to specify if(isLearning === true)? 
Since true is a “truthy” value, we can let the if statement turn the expression into a value that is true or false. True will evaluate into a truthy value.
2. (ii)Why does if(isLearning) work on its ownn?
This is due to that the value of the isLearning variable is truthy. That means the code inside of the if {} will be evaluated and not the else {}.
###### (b)
let firstvariable;
let secondvariable = "";
let thirdvariable = 1;
let secretMessage = "Shh!";

if(firstvariable){
    console.log("first");
} else if(firstvariable || secondvariable){
    console.log("second");
} else if(firstvariable || thirdvariable){
    console.log("third");
} else {
    console.log("fourth");
}
1. What should the above console.log? why?
It should return "third"
the reason is that  the first and second variable have falsely values and the third and the forth has truthy values.The statement is only looking for one truthy value.
2. What is the value of firstvariable when it is initialized?
The value of firstVariable is undefined. Variables that are not assigned to any value are assigned to the value undefined and those are included to falsely values.
3. Is the value of firstvaluable a truthy value? Why?.
The ansuer is no because an undefined are falsely value.
4. Is the value of secondvariable a “truthy” value? Why?
The answer is No because an empty string is a falsely value.
5. Is the value of thirdvariable a “truthy” value? Why?
 The answer is Yes because all numbers expect zero are truthy value.
 # Part 3
 1. look "part2.js"
 2. What is a falsey value? List all the falsey values in JavaScript.
 A falsey value is the one that evaluates to FALSE, when checking valuable.
(ii). There are six falsey value. This include:
undefined; null; NaN; 0(zero); ""(empty string); and false.