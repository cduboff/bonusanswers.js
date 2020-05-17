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
