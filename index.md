1. What would the following function return (not output) when called? Write the output next to function call.
-

```js
function test() {
  alert('Hello');
}
test(); // undefined
```

-

```js
function test() {
  return;
}
test(); // undefined
```

-

```js
function test() {
  return 21;
}
test(); // 21
```

-

```js
function test() {
  return null;
}
test(); // null
```

-

```js
function test() {
  console.log('hello');
}
test(); // undefined
```

-

```js
function test() {
  prompt('Enter your age?');
}
test(); // undefined
```

-

```js
function test() {
  return prompt('Enter you age');
}
test(); // "100"
```

-

```js
function test() {
  return function second() {};
}
test(); // function second
```


2. What will be the value of test variable in the snippet below

```js
function sayHello() {
  let username = 'John';
  return `Hello ${username}`;
}
let test = sayHello(); // "Hello John"
```

3. What will be the value of test variable and output of console.log() in the snippet below

```js
let username = 'Sam';
function sayHello() {
  let username = 'John';
  return `Hello ${username}`;
}
let test = sayHello(); // 'Hello John'
console.log(username); // 'Sam'
```


4. What will be the value of test and output of console.log() variable in the snippet below

```js
let username = 'Sam';
function sayHello() {
  return `Hello ${username}`;
}
let test = sayHello(); // "Hello Sam"
console.log(username); // "Sam"
```