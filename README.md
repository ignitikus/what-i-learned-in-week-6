# What I Learned In Week 6

## While Loops
Loops can execute code until certain condition is met.<br>
For example:

    let i = 0;

    while (i<5){
        code code code code;
        i++;
    } 

At the beginning of this code `i` has value of `0`. At the end of the first run `i` will be bumped by 1 and loop restarts. With each run value of `i` will increase by 1. After reaching 5 the condition of the loop `i<5` is satisfied. Loop stops and the code after the loop will be executed. <br>
Note: `if/else` statements can be used inside of the loop to create additional conditions. <br>
`break` can be used to stop the loop after certain condition within loop is met.

### [Whiles and Numbers All Wrapped Up In Strings](https://repl.it/@NikolayKim/Whiles-and-Numbers-All-Wrapped-Up-In-Strings)
Simple loops with numbers and strings. <br>
Lessons learned:

    Use modulo to check if number is even or odd
    number%2 === 0 ? true : false


### [String Loops](https://repl.it/@NikolayKim/String-Loops-201-Advanced-String-Loops)
Loops with strings or how to pick certain letter.
Lessons learned:

    function onlyA(str){
    let i = 0;
        while(i<=str.length){
        str.charAt(i) === 'a';
        console.log(str[i]);
        }
    code code code 
This fragment of the code is responsible for selecting only `a` within a string and outputting it in console.


## Intro to Arrays
A variable that can store multiple values.

    let items = [item1, item2, item3, item4];

All the items within array have index. <br>
Certain item within arrays can selected like this:

    items[0];

To select last item within array:

    arr[arr.length - 1]

Methods that can be used with arrays:

    .push('item') - adds 'item' at the and of an array
    .pop() - removes last item
    .unshift('item') - adds 'item' at the beginning of and array and reassigns all indexes     
    .shift() - removes first 'item' in an array and reassigns all indexes

### [You Deserve Arrays](https://github.com/ignitikus/you-deserve-arrays)
Exercise about selecting certain `item` within array.

### [Array Of Radioactive Mutants](https://github.com/ignitikus/array-of-radioactive-mutants)
Exercise about `push`ing, `unshift`ing and replacing values within an array.


## Human Resource Machine 

    Level 24 - Mod Module

## Extra:
### String Interpolation 
Feature that allows to insert variable inside of a variable

    let name = 'Niko';
    let occupation = 'Student';
    return `Hello my name is ${name} and I'm a ${occupation}`
