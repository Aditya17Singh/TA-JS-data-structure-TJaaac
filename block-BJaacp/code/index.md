1. What will be the output and explain the reason.

```js
let obj = { name: 'Arya' };ijo
obj = { surname: 'Stark' };i
let newObj = { name: 'Arya' };i
let user = obj;oj
let arr = ['Hi'];kjin
let arr2 = arr;ioj
```

Answer the following with reason after going through the above code:

- `[10] === [10]`// true
- What is the value of obj? //
- `obj == newObj`// false
- `obj === newObj`// false
- `user === newObj`// false
- `user == newObj`// false
- `user == obj`// true
- `arr == arr2`//true
- `arr === arr2`// true

2. What's will be the value of `person1` and `person2` ? Explain with reason. Draw the memory representation diagram.

<!-- To add this image here use ![name](./hello.jpg) -->

```js
function personDetails(person) {
  person.age = 25;
  person = { name: 'John', age: 50 };
  return person;
}
var person1 = { name: 'Alex', age: 30 };
var person2 = personDetails(person1);
console.log(person1);oij
console.log(person2);ojk
```

3. What will be the output of the below code:

```js
var brothers = ['Bran', 'John'];
var user = {
  name: 'Sansa',
};
user.brothers = brothers;
brothers.push('Robb');
console.log(user.brothers === brothers); //1. false
console.log(user.brothers.length === brothers.length); //2. true
```
