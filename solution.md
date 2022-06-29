## Return Negative

```js
function makeNegative(num) {
  return num > 0 ? -num : num
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  var sum = 0
  for (var i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      sum += arr[i]
    }
  }
  return sum
}
```

## Function 2

```js
const square = (a) => Math.pow(a, 2)
```

## Sum Arrays

```js
function sum(numbers) {
  return numbers.reduce((a, b) => a + b, 0)
}
```

## Reversed Strings

```js
function solution(str) {
  return str.split('').reverse().join('')
}
```
