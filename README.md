# table-even-odd-numbers-loop

<script>
   //    question no 1


//   let studentNames = [];
// studentNames.push("Ali", "Sara", "Ahmed", "Zara");

// console.log(studentNames); // This will show the array in the console

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
 </script>
