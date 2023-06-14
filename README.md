# Pyramid-Triangle-Pattern
//Pyramid-Triangle-Pattern
let rows = 10;

let pattern = "";

// outer loop runs for `rows` no. of times
for (let i = 1; i <= rows; i++) {
   // Inner Loop - I -> prints spaces
   for (let j = 1; j <= rows - i; j++) {
      pattern += " ";
   }

   // Inner Loop - II -> prints stars
   for (let k = 1; k <= 2 * i - 1; k++) {
      pattern += "*";
   }
   pattern += "\n";
}
console.log(pattern);
