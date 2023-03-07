# Technical Evaluation Live School Shopping (thinkful)
Technical Interview Live: School Shopping
In this challenge, you'll work with the School Shopping data from the take home problems. You'll solve a new problem and then extend your solution.

During the interview, you are encouraged to think aloud. Talk through your approach with the interviewer. The interviewer may also ask questions or provide guidance.

Instructions

Read the instructions for part 1.
Write code to solve part 1.
Run the tests to check whether your code for part 1 is correct.
After completing part 1, read the instructions for part 2.
Write code to solve part 2.
Part 1 - Find Items By Type
Create a function findItems that

takes in two arguments: an array of items, and a type of item as a string
returns an array of items that have a type that matches the type passed in
Using the example data below,

findItems(items, "book") /* =>
[{ 
    itemName: "Effective Programming Habits", 
    type: "book", 
    price: 18.99
}]
  */
Note: after you write this function and the first set of tests pass, a second set of tests will show up for part 2.

Part 2 - Find Items, Extended
Add the following features to your findItems function:

If there are no items in the cart array, return the string "Your cart does not have any items in it."
If there are no items that match the given type, return the string "No items found of that type. Please search for a different item.".
Sample Shopping Cart Data
let items = [
  { 
    itemName: "Effective Programming Habits", 
    type: "book", 
    price: 18.99
  },
  {
    itemName: "Creation 3005", 
    type: "computer",
    price: 399.99
  },
  {
    itemName: "Orangebook Pro", 
    type: "computer",
    price: 899.99
  }
];
