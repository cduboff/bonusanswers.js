# bonusanswers.js

// countdown

var num = [];
function countdown(num){
  for(i = num; i > 0; i--){
    num.push(i);
  }
  return num;
}
countdown(num);
console.log(num.length);

// print and return

function print_return(){
  var arr = [3,5];
  console.log(arr[0]);
  return arr[1];
}
print_return();

// first plus length

function first_plus_array(){
  var arr = [];
  return arr[0] + arr.length;
}

// values greater than second

function greater_than([1,3,5,7,9,13]){
var arrnew = [];
for(var i=0; i<arr.length; i++){
  if(arr[i] > arr[1]){
    arrnew.push(i);
  }
return arrnew.length;  
}  


//This length, that value

function two_nums(num1,num2){
  var arr1 = [];
  for(var i=0; i<num1; i++){
    arr1[i] = num2;
  }
  console.log(arr1);
  if (num1 == num2){
    console.log('Jinx!');
  }
}
  two_nums(5,5);
  
  // fit the first value
  
  function fit_the_first(arr){
  if(arr[0]>arr.length){
    console.log("Too big!");
  }
  else if(arr[0]<arr.length){
    console.log("Too small!");
  }
  else{
    console.log("Just right!");
  }
}

// Fahrenheit to Celsius

function fahrenheitToCelsisus (fDegrees){
   var Celsius = (fDegrees - 32) * 5/9;
  return(Celsius);
}

// Celsius to Fahrenheit

function celsiusToFahrenheit(cDegrees){
  var Fahrenheit = (9/5 * cDegrees) + 32;
  return(Fahrenheit);
}
