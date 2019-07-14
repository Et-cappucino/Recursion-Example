# Recursion-Example
An example of recursion and how it works

function loop (num) {
if (num === 0 ) {
return "";
}
return loop(num-1) + "<br>" + num;
};

var result = loop(5);
console.log(result);
