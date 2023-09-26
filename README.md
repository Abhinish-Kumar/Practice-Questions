# Practice-Questions
Try these common interview questions.


## 1. Write a function that reverses a string. The input string is given as an array of characters s.

You must do this by modifying the input array in-place with O(1) extra memory.

```javascript
Example 1:

Input: s = ["h","e","l","l","o"]
Output: ["o","l","l","e","h"];
```

```javascript
//2 remove immediate duplicate of the array 

let arr=[1,1,1,2,3,3,3,4,5,5,5];
console.log(removeD(arr))

function removeD(arr){
    let newArr=[];
    let n=arr.length;
    for(let i=0;i<=n;i++){
    if(arr[i]!=arr[i+1]){
        newArr.push(arr[i])
    }}
    return newArr;
}

//[ 1, 2, 3, 4, 5 ]
```


