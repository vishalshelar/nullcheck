# nullcheck

This package is check whether input is either undefined, null or empty, false otherwise

## Usage

Insatll the package using npm :
npm install nullcheck --save
Then, require the package and use it:
[Comment: to check if this usage is proper]
var isNullOrEmpty = require('nullcheck');
console.log(isNullOrEmpty("")); // true
console.log(isNullOrEmpty("Hello World")); // false
