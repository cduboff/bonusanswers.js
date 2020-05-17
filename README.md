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

// Celsius and Fahrenheit (optional)

function celsiusToFahrenheit(cDegrees){
  var Fahrenheit = (9/5 * cDegrees) + 32;
  return(Fahrenheit);
}

var Celsius = 200;

while(Celsius<celsiusToFahrenheit(Celsius)){
  Celsius--;
  if(Celsius==celsiusToFahrenheit(Celsius)){
    console.log("They're the same!" +Celsius)
  }
}


// Biggie Size

function BiggieSize(arr){
  for(var i=0; i<arr.length; i++){
    if(arr[i]>=0){
      arr[i] = "big";
    }
  }
  console.log(arr);
}

// Print low, Return high

function printLow(arr){
  var min = arr[0];
  var max = arr[0];
  for(var i=1; i<arr.length; i++){
    if(arr[i]<min){
      min = arr[i];
    }
    if(arr[i]>max){
      max = arr[i];
    }
  }
  console.log(min);
  return max;
}

// Print One, Return Another

function printOne(arr){
  console.log(arr[arr.length-2]);
  for(var i=0; i<arr.length; i++){
    if(arr[i]%2 !== 0){
      return arr[i];
    }
  }
}

// Double vision

function double(arr){
  var arrnew = [];
  for(var i=0; i<arr.length; i++){
    arrnew.push(arr[i] * 2);
  }
  return(arrnew);
}

// Count Positives

function countPositives(arr){
  var temp = [];
  for(var i=0; i<arr.length; i++){
    if(arr[i]>0){
      temp.push(arr[i]);
    }
  }
  arr[arr.length-1] = temp.length;
  return arr;
}

//Evens and Odds

// Increment The Seconds

function IncrementTheSeconds(arr){
  for(var i=0; i<arr.length; i++){
    if(arr[i]%2 !== 0){
      arr[i]++;
      console.log(arr[i]);
    }
  }
  return arr;
}

// Previous Lengths

// Add Seven to Most

function AddSeven(arr){
  var arrnew = [];
  for(var i=1; i<arr.length; i++){
    arr[i]+=7;
    arrnew.push(arr[i]);
  }
  return arrnew;
}

// Reverse Array

function Reverse(arr){
  var x=arr.length-1;
  for(var i=0; i<arr.length; i++){
    var temp = arr[i];
    if(x>i){
      arr[i] = arr[x];
      arr[x] = temp;
      x--;
    }
  }
}
Reverse([3,1,6,4,2]);

// Outlook: Negative

function outlook(arr){
  for(var i=0; i<arr.length; i++){
    if(arr[i]>0){
      arr[i] = arr[i] + (-arr[i]*2);
    }
  }
  return arr;
}

// Always Hungry



