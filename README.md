# Basic JavaScript

## Data Types
```
// Variables and Data-types : String
var firstName = 'Jigme';
console.log(firstName);

// Number type
var lastName = 'zangmo';
var age = 20;

// Boolean type
var fullAge = true;
console.log(fullAge);

// undefine
var job;
console.log(job);

job = 'Teacher';
console.log(job);

// Variable naming rules
var _3years = 3;
var jigmeZangmo = 'Jigme and Mark';
console.log(_3years);
console.log(jigmeZangmo);


// Variable mutation and type coercion
var firstName = 'jigme';
var age = 25;

// Type coercion
console.log(firstName + ' ' + age);

var job, isMarried;
job = 'teacher';
isMarried = false;
console.log(firstName + ' is a ' + age + ' year old '
+ job + '. Is he married? ' + isMarried);

// Variable mutation
age = "twenty five";
job = 'cook';

alert(firstName + ' is a '+ age + ' year old '
+ job + '.Is he married? ' + isMarried);

var lastName = prompt('what is his last Name?');
console.log(firstName + ' ' + lastName);


/*****************
* Basic Operators
*/
var year, yearJigme, yearZangmo;
now = 2020;
ageJigme = 25;
ageZangmo = 34;

// Math Operators
yearJigme = now - ageJigme;
yearZangmo = now - ageZangmo;

console.log(yearZangmo);

console.log(now + 2);
console.log(now * 4);
console.log(now / 10);

// Logical Operators
var jigmeOlder = ageJigme > ageZangmo;
console.log(jigmeOlder);

// typeof Operator
console.log(typeof jigmeOlder);
console.log(typeof ageZangmo);
console.log(typeof 'Zangmo is older than Jigme');
var x;
console.log(typeof x);
```
