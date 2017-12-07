# variable
var age = 10; 10.2
var name = 'arafat';
# datatype
  * scalar
    *  string ''
    * number 
      * integer
      * float
    * boolean (true, false)
  * composite
    * array
    var random =  ['apple', 'orange', 2, 3, 'dhaka', 'bangladesh']
    random[0]
    * object
    var random =  {fruit1: 'apple', fruit2: 'orange'};
    random.fruit1
    random['fruit2']
# control flow
* conditional 
if (2 + 2 == 5) {
  i will go
} else {
  some thing else
}
if (2 + 2 == 5) {
  i will go
} else if (2 + 2 == 7) {
  I will eat fruit
} else {
  some thing else
}
2+2 === 4 ? 'do something' : 'do other thing';
switch (2+2) {
  case 5:
    i will go
    break;
  case 7:
    I will eat fruit;
  default:
    some thing else
}

* iterative
do while
var number = 1;
while (number < 10) {
  console.log(number);
  ++number
}
for (var number = 1; number < 10; number = number + 1) {
  console.log(number);
}
for loop
# function
var name = 'mubarok';
//built in 
name.toUpperCase() //MUBAROK
// user defined
function add (n1, n2) {
  return n1 + n2;
}
add (2, 3);
# operator
* unary
++ --
var x = 10;
x = x + 1;  x++ ++x
x = x - 1;  x-- --x
* binary
+ + - / * % == === 
* ternary
condition ? 'do something' : 'another thing';
