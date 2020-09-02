// Q1.program to search character in a string
let str = "pavitra";
console.log(str);
console.log(str.indexOf("t"));

//Q2. Program to convert minutes to seconds

let minutes = 10;

seconds = minutes * 60;
console.log("10 " + " Min " + " into sec is " + seconds);

//Q3. Program to search element in a array of strings
var array = [576, 980, -279, -990, -520, 0];

var found = array.find(function(element) {
    return element >= 0;
});
console.log(found);

//Q4. Program to display only elements containing 'a' in the term of array

var array = ["banana", "grapes", "pavitra", "trees", "jimmy", "sravani", "python"];


function contains(array) {
    for (var i = 0; i < array.length; i++) {
        if (array[i] == "a") {
            return array;
        }
    }
}
console.log(contains(array, a));

//Q5. Print an array in reverse order
Array = ["java", "javascript", "python"];
console.log(Array);
Array = ["java", "javascript", "python"].reverse();
console.log(Array);
