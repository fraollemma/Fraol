"# Fraol" 
const character = "#";
const count = 8;
const rows = [];

function padRow(rowNumber, rowCount) {
  return " ".repeat(rowCount - rowNumber) + character.repeat(2 * rowNumber - 1) + " ".repeat(rowCount - rowNumber);
}

// TODO: use a different type of loop
/*for (let i = 1; i <= count; i++) {
  rows.push(padRow(i, count));
}*/

if ("") {
  console.log("Condition is true");
} else if (5 < 10) {
  console.log("5 is less than 10");
} else {
  console.log("This is the else block");
}

let result = ""

for (const row of rows) {
  result = result + row + "\n";
}

console.log(result);










const character = "#";
const count = 8;
const rows = [];

function padRow(rowNumber, rowCount) {
  return " ".repeat(rowCount - rowNumber) + character.repeat(2 * rowNumber - 1) + " ".repeat(rowCount - rowNumber);
}

// TODO: use a different type of loop
/*for (let i = 1; i <= count; i++) {
  rows.push(padRow(i, count));
}*/

let continueLoop = false;
let done = 0;

while (done !== count) {
  done++;
  rows.push(padRow(done, count));
}

let result = ""

for (const row of rows) {
  result = result + row + "\n";
}

console.log(result);

Make this website full CSS flex and fit with four item grid layout for 768 media width device.



Arrays also have a .shift() method. This will remove the first element of the array, unlike .pop() which removes the last element. Here is an example of the .shift() method:push() pop()

const numbers = [1, 2, 3];
const shifted = numbers.shift();
console.log(shifted);
const unshifted = numbers.unshift(5);
console.log(unshifted);
console.log(numbers);