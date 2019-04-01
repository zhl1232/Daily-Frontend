# Daily-Frontend

#### 第一天 [参数传值](https://github.com/zhl1232/Daily-Frontend/issues/1)
```js
function fn(person) {
  person.age = 23
  person = {
    name: 'zzz',
    age: 28
  }
  return person
}
const p1 = {
  name: 'xxx',
  age: 25
}
const p2 = fn(p1)
console.log(p1) // -> ?
console.log(p2) // -> ?
```

