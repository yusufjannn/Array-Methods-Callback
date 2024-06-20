# Array-Methods-Js-Callback!!!
# Array Method "Map"->
## In JavaScript, map() is a method of the Array object. It creates a new array by calling a function on every element of the original array and storing the results in a new array. map() returns the new array, and the original array is unchanged. JavaScript map() Syntax
![](https://res.cloudinary.com/practicaldev/image/fetch/s--BcYqvgBS--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kaafkhqh861uc06l309t.jpg)
# Array Method "ForEach"->
## the forEach() method is an iterative method. It calls a provided callbackFn function once for each element in an array in ascending-index order
```js
     let result = [];
    arr.forEach((element,index) => {
     if (arr.indexOf(element)===index){
      result.push(element);
```
# Array Method "Find"->
## In JavaScript, find() is an Array method that is used to return the value of the first element in the array that meets a specific criteria
![image](https://github.com/yusufjannn/Array-Methods-Callback/assets/171818496/336d2b67-7c80-4eae-9559-91ed67775b0d)
# Array Method "Filter"->
## The JavaScript Array filter() method is used for selectively extracting elements from an array based on specified criteria. It helps you to create a new array containing only those elements that satisfy a condition defined by a callback function
```js
 function test (arr){
    return arr.filter((e)=> e > 0);
 }
console.log(test([-1,2,-3,4,-5]));
```
# Array Method "reduce"->
## The array reduce in JavaScript is a predefined method used to reduce an array to a single value by passing a callback function on each element of the array. It accepts a function executed on all the items of the specified array in the left-to-right sequence
```js
 let arr = [2,4,6,8];
 let ans = arr.reduce((cnt,current)=>{
     return cnt + current;
 });
 console.log(ans/arr.length);
```
# Array Method "ToSorted"->
## The toSorted() method of Array instances is the copying version of the sort() method. It returns a new array with the elements sorted in ascending order.
``` js
 let arr = [1,20,2,3,4];
console.log(arr.toSorted((a,b)=>a-b));
```
# Array Method "Rest"->
## The rest operator in javaScript allows a function to take an indefinite number of arguments and bundle them in an array, thus allowing us to write functions that can accept a variable number of arguments, irrespective of the number of parameters defined
```js
  let arr = [1,2,3];
  let [...a] = arr;
console.log(a);
```
# We have many types of CallBack methods but i said some of them for more info---------->
### https://medium.com/@rajanmagarrr/array-callback-methods-7cb79ec7dbc6
