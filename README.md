# javascript-interview-questions
### Somw other references https://github.com/sudheerj/javascript-interview-questions
### What is hoisting?
### What is event loop?
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
