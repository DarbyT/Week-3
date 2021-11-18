"# Week-3" 
// arrays
/*	Create an array called ages that contains the following 
  values: 3, 9, 23, 64, 2, 8, 28, 93.*/

/*let ages = [3, 9, 23, 64, 2, 8, 28, 93]
    console.log(ages[ages.length - 1] - ages[0]);

    ages.push(25)
    console.log(ages[ages.length - 1] - ages[0]);

    let total = 0
    let avg = 0 

    for(i = 0; i <= ages.length-1; i++){
      total += ages[i];   
    };
    avg = total / ages.length;
    console.log(avg); */

/*
 let total = 0;
let avg = 0;

  let names = ['Sam', 'Tommy', 'Tim', 'Sally', 'Buck', 'Bob']
    for(i = 0; i <= names.length - 1; i++){
        total += names[i].length;
    }
 avg = total/names.length
 console.log(avg);

 for(let i = 0; i < names.length; i++){
   console.log(names[i]);
 }

let namesLengths = names.map(function(element) {
  return element.length;
});
console.log(namesLengths);

let sum = namesLengths.reduce(function(accumulator, currentValue){
  return accumulator + currentValue
})
console.log(sum); */

 //functions
  let result = '';
     function stringRepeat(word, n){
       
      for(let i = 1; i<=3; i++){
         result += word;  
    } return result
   
    } stringRepeat('Hello', 3);
       console.log(result);
    
let firstName = 'Darby'
let lastName = 'Turnbull'

       function names(firstName, lastName){
         result = firstName +  lastName;
       } names('Darby', ' Turnbull');
       console.log(result);

let values = [1, 2, 4, 5, 6]   
       function lessThan(){
   let total = 0;      
      
    total += values.length
    if( total >= 100){
     console.log(true); 
    }else {
      console.log(false);
    }
} lessThan(values);

function twoArrays(a1, a2) {
  let avg1 = 0;
  let avg2 = 0;
  let total1 =0;
  let total2 = 0;
  for(let i =0; i <= a1.length; i++){
    total1 = a1 + a1.length;
    avg1 = total1 / a1.length;
  }
  for(let i = 0; i<=a2.length; i++){
    total2 = a2 +a2.length;
    avg2 = total2 / a2.length;
  }
  if (avg1 > avg2){
    console.log(true);
  }else {
    console.log(false); 
  }
}

let a1 = [50, 100];
let a2 = [22, 34];

twoArrays(a1, a2);


function willBuyDrink(isHotOutside, moneyInPocket){
  if(isHotOutside == true && moneyInPocket > 10.5)
      return true;
  else
      return false;
}

function tooworkoutornot(timeavailable, bodybattery){
  if(timeavailable > 1 && bodybattery >= 50)
  return true
  else
  return false
}
