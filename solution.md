## Return Negative

````js

function makeNegative(num) {
 return num > 0 ? -num : num
}

## Sum of Positive

```js

```function positiveSum(arr) {
  let sum = 0
  for(let i=0; i < arr.length; i++){
  if(arr[i]> 0){
    sum += arr[i]
  }
  }
    return sum
}

## Function 2

```js

```const square = (num)=>{
  return num*num
}

## Sum Arrays

```js

```function sum (numbers) {
    "use strict";
      if(numbers.length>0){
      let sum=0
  for(let i=0; i < numbers.length; i++){
      sum += numbers[i]
      }
    return sum
      }else return 0
};

## Reversed Strings

```js

```function solution(str){
  let reversed = ''
  for (let i=str.length -1; i>=0; i--){
    reversed += str[i]
  }
  return reversed
}
````
