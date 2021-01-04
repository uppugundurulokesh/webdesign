# webdesign

Functions
Static function
   function subtraction(){
   var i=10;
   var j=20;
   return i-j;
} 
Dynamic functions
function multiplication(a,b){
    return a*b;
}

multiplication(10,2)
Anonymous functions
var addition=function(a,b){
    return a+b;
}

addition(10,20)
Arrow functions
var addition=(a,b)=>{
    return a+b;
}

addition(10,20)
Iterations
for
map
  array1.map(function(value,index){
  console.log(value+"is having this index value "+index)
})

array1.map((value,index)=>{
  console.log(value+"is having this index value "+index)
})
for-in
  for(i in array1){
    console.log(i)
}
for-of
    for(i of array1){
    console.log(i)
}
forEach
  array1.forEach(i=>{
    console.log(i)
})


array.forEach(item=>{
    console.log(item)
})

// item represents the elements of an array


array.forEach((item,index)=>{
    console.log(item+"=>"+index)
})

// index is for positions

array.forEach((item,index,array)=>{
   console.log(item+"=>"+index+"=>"+array)
})

array displays the entire array
Destructuring
Assigning values to a specific variable by extracting them from an array.

     array
     // [1,2,3,4,5,6]
     
     var [a,b]=array;
     a
     // 1
     
     b
     // 2
     
     var [a,b,...c]=array;
     
     c
     // [3,4,5,6]
Array functions
find()

     array.find((n)=>{
     return n>2
})


     array.slice(0,4) // 0 is the starting index & 4 is the ending index
     // [0,1,2,3]
     
     array.filter(n=>{
       return n%2==0
     })
     
     // [2,4,6]
     
     
     // includes
     array.includes(6)
     // true
     
     array.includes("z")
     // false
     
     array.pop()
     // 6
     
     array
     // [1,2,3,4,5]
     
     array.push(6)
     // 6
     [1,2,3,4,5,6]
     
     
     array.toString()
     // "1,2,3,4,5,6"
     
     array.splice(2,4) // Here 2 is the index position and 4 is number of elements to be deleted.
     
     // array.reverse
     array.reverse()
     // [5,4,3,2,1] // Sort an array in descending order
     
     array.sort()
     // [1,2,3,4,5] // Sort an array in ascending order
     
     // array.shift() // Removes an item from the beginning of an array
     
     // array.unshift() // Removes an item from the ending of an array
Template literals || String literals
This is for avoiding complexity and + for joining multiple strings together.

    console.log(`I am ${name} and I am working as a ${role}`);
String functions
str.concat() Merging one or more string(s) together
str.charAt() Getting specific character based on the index value
str.indexOf Getting index value based on the character. If the character is not available we can get -1
replace()
   str.replace("sampple","word")
search()
    str.search("wo")
substr()
substring()
split()
includes()
startsWith()
endsWith()
toUpperCase()
toLowerCase()
