# JavascriptHelper

### Running the tasks notes
- When running the tasks you can use node to trigger the javascript to run. 
- Node allows developers to write JavaScript code that runs directly in a computer process itself instead of in a browser.
- If you have created a file called test.js you will want to run in the terminal ```js node test.js ```
- If you are seeing no logging double check that any functions you want to run are being invoked ( explained down below )


### Main Data Types:
#### Numbers:
```js
let length = 16;
let weight = 7.5;
```
#### Strings:
```js
let color = "Yellow";
let lastName = "Johnson";
```
#### Booleans
```js
let x = true;
let y = false;
```
#### Object:
```js
const person = {firstName:"John", lastName:"Doe"};
```
#### Array:
```js
const cars = ["Saab", "Volvo", "BMW"];
```
#### Date object:
```js
const date = new Date("2022-03-25");
```

#### functions:
- A JavaScript function is a block of code designed to perform a particular task
- A JavaScript function is executed when "something" invokes it (calls it).

```js
// Old way of writing a function
function addNumbers(number1, number2) {
    return number1 + number2;
}

// ES6 way of writing functions, can be const or let 
const addNumbers = (number1, number2) => {
    return number1 + number2;
}

// Invoking a function requires you to pass the parameters in call it with the brackets like so.
addNumbers(1, 2)

```
