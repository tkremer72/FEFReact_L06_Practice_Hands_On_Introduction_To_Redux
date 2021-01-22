# L06 Practice Hands on

# Introduction To Redux

Lesson 6 Practice Hands-On
Directions
For your Lesson 6 Practice Hands-On, you will be working in a project you create. This Hands-On will not be graded, but we encourage you to complete it. The best way to become a great programmer is to practice! Once you have submitted your project, you will be able to access the solution on the next page.

Setup
Open up your terminal/command prompt.

Run the following to navigate to your Desktop

cd Desktop
Next, navigate to the FullStackWeb directory in your terminal.

cd FullStackWeb
Then, navigate to the FEFReact directory in your terminal.

cd FEFReact
Create a new project folder named L06HandsOn located within the FEFReact folder in your terminal.

mkdir L06HandsOn
Once the process is complete, navigate into the L06HandsOn directory:

cd L06HandsOn
Run the following to open your new project in VS Code (or you can open the folder within VS Code directly):

code .
Add an index.js file into this directory

Requirements
Add the code for the following requirements within the index.js file.

Step 1
Convert the given JavaScript into ES6 syntax using an arrow function and filter.

const arr = [
    {"name":"chevy", "count": 2},
    {"name":"ford", "count": 5},
    {"name":"acura", "count": 3},
    {"name":"honda", "count": 16},
];

const newArr = [];

for(let i= 0; i < arr.length; i++){
    if(arr[i].name === "ford" ){
        newArr.push(arr[i]);
    }
}

console.log("Filter results:", newArr);
Step 2
Given the function, use the ES6 that was covered to combine the two arrays.

const arr = ['Bill', 'Joe', 'Emily', 'Andrea']
const newStudents = ['Andrew', 'Tasha', 'Carol', 'George'];

function addNewStudent(array, newArray) {
    for(let i = 0; i < newArray.length; i++) {
        array.push(newArray[i]);
    }
}

addNewStudent(arr, newStudents);
Tip!
You will need to use the spread operator!