## Return Negative

```js
function makeNegative(num) {
  return num > 0 ? -num : num
}
// -- OR --
function makeNegative(num) {
  if (num > 0) {
    return num * -1
  } else {
    return num
  }
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0

  for (let i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      sum += arr[i]
    }
  }
  return sum
}
```

## Function 2

```js
function square(arg) {
  return Math.pow(arg, 2)
}
```

## Sum Arrays

```js
sum = (numbers) =>
  numbers.reduce((previousN, currentN) => previousN + currentN, 0)
// -- OR --
sum = function (numbers) {
  'use strict'
  return numbers.reduce(function (total, num) {
    return total + num
  }, 0)
}
```

## Reversed Strings

```js
function solution(str) {
  return str.split('').reverse().join('')
}
```
