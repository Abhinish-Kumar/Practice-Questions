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



## 2.Given an array of integers,return the indices of the add uo to a given target.
Eg:
###### Input
arr=[1,3,7,9,2];
target=11;
###### Output
[9,7];

### Step1. Verify the Constrains.
1. Are all the numbers +ve or can there be a negative number?:_(All the numbers are +ve);
2. Are there duplicate Numbers in the array?:_(no);
3. Will there always be a solution available?:_(no,there may not always be a solution);
   i. if answer is not possible.
   ii.  [] if array is empty.
   iii.  [5] if it has only single value
4. What do we return if there is no solution?:_(Just return null).
5. Can there be multiple pairs that add up to the target?:_(No,only 1 pair of numbers will add upto the target).
6. if [target] and if array contain single value


### Step 2 Figureout the test cases without code 

```javascript
nums=[1,3,7,9,2];
target=11;


```






