# table-even-odd-numbers-loop

<script>
   //    question no 1


 let studentNames = [];
   studentNames.push("Ali", "Sara", "Ahmed", "Zara");

console.log(studentNames); // This will show the array in the console

        // question no 2
// let studentNames = new Array();

//  
//   studentNames.push("Ali");
//   studentNames.push("Sara");
//   studentNames.push("Ahmed");

//   // Show in console
//   console.log("Student Names:", studentNames);

    //    question no 1 chapter no 9

//        let city = prompt("Enter your city name:");

// if (city && city.toLowerCase() === "karachi") {
//   alert("Welcome to city of lights");
// } else {
//   alert("Welcome!");
// // }
//               question no 2 
// let gender = prompt("Enter your gender:");
// if (gendermale.tolowercase() === "male") {
//     alert("good morning sir");
// } else{
//     alert("good morning madam");}

                //   LOOP

    //   INIZILIZATION,CONDITION ICREMENT/DECREMENT

const cars=["BMW","LAMBORGHINI","FORTUNER"];
let text="";
for(let i=0;i<cars.length;i++){
    text+=cars[i]+"<br>";
}
document.getElementById("demo").innerHTML=text;

    //  EVEN ODD

document.write("even/odd");
for (let i=1;i<=20;i++){
    if(i%2==0){
        console.log(i+"even/odd");
    }else{
        console.log(i+"/odd")
    }
}

    //   TABLE
const number =5;
for(let i=1;i <=10; i++){
    console.log(`${number} * ${i} =${number * i}`);
}





assigment chatpter 17 20

   
   //    question no 1
    // Declare and initialize an empty multidimensional array (array of arrays)

let multiArray = [];


        // question no 2
const matrix=[
[1, 2, 3],
[4, 5, 6],
[7, 8, 9],
];

for(let i=0; i <matrix.length; i++){ 
  for(let j=0; j <matrix[i].length;j++) {
  console.log(`Element at row ${i}, column ${j}: ${matrix[i][j]}`)
}}

// Display the matrix
console.log("Matrix:", matrix);


        //  question no 3
// Print numeric counting from 1 to 10,

for (let i = 1; i <= 10; i++) {
  console.log(i);
.

    //    question no 4
// Take table number input from user
let tableNum = +prompt("Enter a number to show its multiplication table");

// Take table length input from user
let tableLength = +prompt("Enter length of multiplication table");

// Print the table using for loop
for (let i = 1; i <= tableLength; i++) {
  console.log(`${tableNum} x ${i} = ${tableNum * i}`);
}
      // question no 5
      let fruits = ["apple", "banana", "mango", "orange", "strawberry"];

for (let i = 0; i < fruits.length; i++) {
  console.log("Element at index " + i + " is " + fruits[i]);
}
     28 june saturday 
    pattern printing
let rows =4;
for (let i =1; i <=rows; i++){
  let pattern = '';
  for (let j = 1; j<= i; j++){
    pattern += j;
  }
  console.log(pattern);
}
    FIXED NUMBERS
let num = 5.56789;
let n = num.toFixed(); AGAR () ME JITNE NUM LIKHOGI UTNI POINT K BD K NUMBEER SHOW KARWAEGA 

document.getElementById("demo").innerHTML = n;

DATE AND TIME
   Const date =new Date ()
   console.log (date typeof date)
ese hi alag alag time month millisecound sab karwa skte or  jo new date hai ise tu pura sab dikhadeta hai 
   
         29 june  sunday
   date and time pre built function in (book samarter way  lean javascript)
    var d = new Date();
                d.setMonth(11);
console.log (d)     ese hi sare function pre built h like year month date 

     FUNCTIONS 
function sum() {
    let a = 10;
    let b = 7;
    let c = 8;
    let total = a + b + c;
    console.log(total);
}

sum(); 
sum();   YE KARWANA LAZMI HAI JB BHI HUM FUNCTION LIKHEN

   PASSING BACK DATA FROM USER
function calcTot(merchTot) {
 var orderTot;
 if (merchTot >= 100) {
 orderTot = merchTot;
 }
 else if (merchTot < 50.01) {
 orderTot = merchTot + 5;
 }
 else {
 orderTot = merchTot + 5 + (.03 * (merchTot - 50));
 }
 return orderTot;
 }


saturday 12 july 2025
chapter while loop   = for loop ki trha hota hai pr while loop condition pr hi chalta hai agar input n nahi hoga tu chlta rahega 

let input = ''
while(input !== 'n') {
    input = prompt('Do you want to continue? y/n')
    console.log(input)
}
chapter do loop   (isme hum phle input lete hn phir phir condition likhty hn)
   
let input ;
   do{
      input=prompt('want y/n')
      console.log(input)
      while(/== 'n')
            ]
chapter 48 49 

function registerPerson(abc) {        (value lagana taky agar kesi hum khud agy likha wa dikhana chahen)
    abc.preventDefault();
    const name = document.getElementById('name').value
    const age = document.getElementById('age').value
    const gender = document.getElementById('gender').value
    const city = document.getElementById('city').value
   
    if (name && age && gender) {
        if (typeof age !== Number) {
            document.getElementById('ageError').innerText = 'Age must be a number';
        } else {
        console.log('Registered...')
        }
    } else {
        console.log('jusxdj', typeof name)
        alert('All fields are mandatory...')
    }
    let country;         (agar hum chahty hn k hum sirf city likhe country khud ajye tu ye lagega)
    switch(city) {
        case 'Karachi':
            country='Pakistan'
            break
        case 'London':
            country="United Kingdom"
            break
        case 'NewYork':
            country='United States of America'
            break
        default:
            country=''
    }
    document.getElementById('country').value = country
}
saturday html k andr javascript se add karna kuch bh id dekr .inner html me agy forexample<p> tag lga k agy likhdo tu ye text html me dekhega bina html me likhe hwy
- document.getElementById("one").innerHTML="<p>hello how are you</p>"
document.getElementById("one").innerHTML+="<ol> fruit vegetable chicken</ol>"











   
 </script>
