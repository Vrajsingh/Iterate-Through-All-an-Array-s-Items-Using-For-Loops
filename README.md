# Iterate-Through-All-an-Array-s-Items-Using-For-Loops
Here is the shortest code which one have to solve this topic problem of - Iterate Through All an Array's Items Using For Loops


Basic Data Structures: Iterate Through All an Array's Items Using For Loops

We have defined a function, filteredArray, which takes arr, a nested array, and elem as arguments, and returns a new array. elem represents an element that may or may not be present on one or more of the arrays nested within arr. Modify the function, using a for loop, to return a filtered version of the passed array such that any array nested within arr containing elem has been removed.


solution=
function filteredArray(arr, elem) {
  let newArr = [];
  // change code below this line
   for( var i = 0 ; i<arr.length ; i++){
if (arr[i].indexOf(elem) === -1){
newArr.push(arr[i]);
}
}
  // change code above this line
  return newArr;
}

// change code here to test different cases:
console.log(filteredArray([[3, 2, 3], [1, 6, 3], [3, 13, 26], [19, 3, 9]], 3));

KINDLY VISIT THE BELOW MENTIONED LINK TO GET ACCESS OF THE CODE
https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-data-structures/iterate-through-all-an-arrays-items-using-for-loops
