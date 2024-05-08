## Return Negative

```js

function makeNegative(num) {
  return num < 0 ? num : -num;
}

```

## Sum of Positive

```js
function positiveSum(arr) {
  if (arr.length == 0) {
    return 0
  } else if (arr.length == 1) {
    return arr[0]
  } else {
    let sum = 0
    arr.forEach((num) => {
      if (num > 0) {
        
      sum += num}
      })
    return(sum)
  }
}

console.log(positiveSum([1,-4,7,12]))

```

## Function 2

```js

function square(input) {
  return Math.pow(input,2)
}

```

## Sum Arrays

```js

function sum(input) {
    let total = 0
    for (let i = 0; i < input.length; i++) {
        total += input[i]
    }
    return total
}

```

## Reversed Strings

```js
function solution(str){
    let output = ''
    return output = Array.from(str).reverse().join('')

  }
```

```js

// Get the current time in milliseconds
const startTime = new Date().getTime();

// Check the elapsed time in a loop
while (new Date().getTime() - startTime < 8000) {
    // Do nothing and wait for 8 seconds
}

```

## Leap Year

```js
function isLeapYear(year) {
  if ((year%4 == 0 && year%100 != 0) || year%400 == 0) {return true}
    else {return false}
}
```


<!-- collab with Megan, Kass, Azalea -->