# javascript-interview-questions
### Somw other references https://github.com/sudheerj/javascript-interview-questions
### What is hoisting?
### What is event loop?
Ans: Stack -> Web APis -> Task queue/Callback queue -> stack
### Difference between call, apply, bind fuuntions?
### Difference between map and reducer functions?
### Difference between callbacks and promises?
### What are the new features in the ES6?
### What are the outputs?

function y() {
    console.log("result: ", i);
    var i = 10;
}
y();

function x() {
    setTimeout(() => {console.log("result: ", i)}, 2000);
    var i = 10;
}
x();
# What are the main Es5(2009) features: https://ducmanhphan.github.io/2019-02-28-New-features-in-ES5/
# What are the main ES6(2015) features: https://www.boardinfinity.com/blog/top-10-features-of-es6/#3-multi-line-strings
