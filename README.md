# Closures

var x = 4; // declaration in outer scope
function bar() {
 console.log(x); // outer scope is captured on declaration
}
bar(); // prints 4 to console
