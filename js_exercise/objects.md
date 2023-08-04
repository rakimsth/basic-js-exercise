1. Print (console.log()) value of the property "name" in the given object:
   let student = {
   name:"Max",
   age: 27
   };

2. a. Find the value of the price property and if it is greater than 100, discount it by 10%. If that’s not the case, discount it by 7%.
   b. Update the object with the new property - discount and the corresponding value (7% or 10%) and the new price.

3. Use given object and loop through its properties and if it has property “discount” print “Already discounted by…” and add the value (how much was the discount). In opposite case, do what you did in the previous exercise: check the price, depending on it (if it’s greater or lower than 100) add discount (10% or 7%) and add the property “discount” to the object.

let prod = {
name: "headphones",
price: 83.7,
discount: "7%",
};

End result should be like this >>
// end result - case 1:
// { name: 'headphones', price: '77.84', discount: '7%' }

// end result - case 2:
// Already discounted by 7%.

4. Write a JavaScript program to calculate circle area and perimeter.
   Note : Create two methods to calculate the area and perimeter. The radius of the circle will be supplied by the user.

5. Write a program which can return a boolean if value is present in the range with given start and end values in an object
   // Example
   let range = {
   start: 10,
   end: 50,
   };

5 in range; // false
25 in range; // true
