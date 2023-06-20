# JavaScript-milestone-01-Pw-Skills
// 1. PassworM Validator
// Write a JavaScript program that checks if the entered password matches the confirmed password. If the
// passwords match, the program should log "Password Matched. Password validation Successful." to the console.
// Otherwise, it should log "Password didn't match. Password validation unsuccessful" to the consoleQ

// let enterPassword = 12345671;
// if (enterPassword == 12345671) {
//     console.log("Password Matched. Password validation Successful");
// }
// else {
//     console.log("Password didn't match. Password validation unsuccessful");
// }

// 2. Calculator
// Create a javascript program that takes in two num#ers and a string operator. Make use of a switch statement
// to perform the operation on the two num#ersQ
// The calculator function should"
//    Take in two num#ers, num1 and num2, and a string representing a mathematical operator, operatorP
//    Use a switch statement to determine which operation to perform #ased on the value of the operatorP
//    If the operator is one of the four valid operators (+, -, *, /), perform the corresponding mathematical
//    operation and store the result in a variable called result.
//    If the operator is not one of the valid operators, log "Invalid operator" to the consoleQ

// let num1 = 10, num2 = 10;
// let operator = "/";

// switch (operator) {
//     case "+": console.log(num1 + num2);
//     break;

//     case "-": console.log(num1 - num2);
//     break;

//     case "*": console.log(num1 * num2);
//     break;

//     case "/": console.log(num1 / num2);
//     break;

//     default: console.log("Invalid operator");
// }

// 3. Color Mixer
// Write a JavaScript program that takes in two strings representing colors and uses a switch statement to
// determine the resulting color when the two colors are mixed. The program should print the resulting color
// #ased on the following criteria"
//   If color1 is "red" and color2 is "blue" or vice versa, print "purple".
//   If color1 is "red" and color2 is "yellow" or vice versa, print "orange".
//   If color1 is "blue" and `color2" is "yellow" or vice versa, print "green".
//   If any other com#ination of colors is input, the program should print "Invalid color com#ination".

// let color1 = "blue", color2 = "yellow";
// let mixColor = color1 + color2;
//
// switch (mixColor) {
// case "redblue": console.log("purple");
// break;
//
// case "redyellow": console.log("orange");
// break;
//
// case "blueyellow": console.log("green");
// break;
//
// default: console.log("Invalid color combination");
// }

// 4. Highest Marks
// A teacher wants to find out the highest marks scored by a student in a class of five students. The teacher enters
// the marks of all five students in an array called "marks". Write a program that iterates through the array and
// finds the highest marks scored by any student in the class. The highest marks must then be displayed to the
// teacher using the console. Make sure you use the ternary operator to find the student with the highest marksQ

// let studentsMarks = [10, 20, 30, 40, 50];
// console.log(studentsMarks);

// let compare = studentsMarks[0];
// for (let i=0; i<=studentsMarks.length; i++) {
//     studentsMarks[i] > compare ? compare = studentsMarks[i] : console.log();
// }

// console.log("Heighest marks is" , compare);

// 5. Capitalize..................................
// You are building a form where users can enter their names. You want to make sure that the first letter of the
// name is always capitalized, even if the user forgets to do so. Write a program that takes in the user's name as a
// string and uses the ternary operator to check if the first letter is lowercase. If it is, the program capitalizes it and
// returns the modified string. Otherwise, it returns the original string without any changes.
// const userName = "rahul";
// let firstCharacter = userName.charAt(0); // first i have targeted my name's first character
// let removedPortion = userName.slice(1), modifiedName; // remove the left portion, .slice(start, end)
// if (firstCharacter != userName.charAt(0).toUpperCase()) {
//     modifiedName = firstCharacter.toUpperCase() + removedPortion;
//     console.log(modifiedName);
// }
// else {
//     console.log(userName);
// }

// 6. Vowel Counter.....................................................................
// We want to count the number of vowels in a person's name. Given a name as input, the program should iterate
// through each character in the name, and check if it is a vowel or not. If the character is a vowel, it should be
// counted.
// const personName = "JavaScript";
// let flag = 0;
// for (let i=0; i<personName.length; i++) {
//     if (personName[i] == "a" || personName[i] == "A" || personName[i] == "e" || personName[i] == "E" || personName[i] == "i" || personName[i] == "I" || personName[i] == "o" || personName[i] == "O" || personName[i] == "u" || personName[i] == "U") {
//         flag++;
//     }
// }
// console.log("Number of vowels in the name is =", flag);

// 7. Remove Duplicates....................................................................
// In an online shopping application, customers can add multiple items to their cart. However, sometimes
// customers accidentally add the same item more than once, resulting in duplicate items in their cart. The
// duplicate items not only make it difficult for the customer to track the items they want to purchase #ut also
// affect the accuracy of the purchase order.

// let items = ["Mango", "Banana", "Grapes", "Grapes", "Mango", "Jackfruits", "Grapes", "Black Berry"];

// function removeDuplicates(items) {
//     let finalNum = [];
//     for(i=0; i < items.length; i++) {
//         if(finalNum.indexOf(items[i]) === -1) {
//             finalNum.push(items[i]);
//         }
//     }
//     return finalNum;
// }
// console.log(removeDuplicates(items));

// 8. Inverte right-angleW triangle pattern with asterisks.
// let rows = 6;
// let i, j;
// for(i=rows; i>=1; i--) {
//   for(j=1; j<=i; j++) {
//     process.stdout.write('* ');
//   }
//   process.stdout.write('\n');
// }

// 9. Check for Wivisibility.
// Writd a program that takds an array of numbdrs and prints all thd numbdrs that ard divisible by 3, but not by 2.
// Usd a for loop and continud statement.
// let arr = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20];
// for (let i=0; i<arr.length; i++) {
//     if (arr[i] % 3 == 0) {
//         if(arr[i] % 2 == 0) {
//             continue;
//         }
//         console.log(arr[i]);
//     }
// }

// 10. pending

// 11. Unit converter...............................
//  A local weather station neds to convert temperature data collected in Celsius to Fahrenheit before displaying
//  it on its website. They want a function that can convert Celsius to Fahrenheit accurately and efficiently. The
//  function should take input in Celsius and return output in Fahrenheit. This function will help the weather station
//  to provide temperature readings that ard easily understandable to a wider audience.
// let temperatureInCelcius = 38.7
// let convertTemperature = (temperature) => {
//     let temperatureInFahrenheit = (9/5)*temperature + 32
//     return temperatureInFahrenheit
// }
// console.log("Temperature in Fahrenheit: ",convertTemperature(temperatureInCelcius));






// 12. Calculate rental cost................................................
// A car rental company needs to calculate the cost of a rental based on the number of days rented and the type
// of car. They require a function that takes in the number of days rented and car type and returns the rental cost.
// Thd total cost would be the rental cost multiplied by the number of days rented.
//   The rental costs are
//   Economy = Rs. 4000 /- per day.
//   Midsize = Rs. 10000 /- per day.
//   Luxury = Rs. 20000 /- per day.

// const calculateRentalCost = (numberOfDays, carType) => {
//     let rentalCost = 0;
//     switch (carType) {
//         case "Economy": rentalCost = 4000
//         break;

//         case "Midsize": rentalCost = 10000
//         break;

//         case "Luxury": rentalCost = 20000
//         break;

//         default: console.log("Invalid Car Type");
//     }

//     return numberOfDays * rentalCost
// }
// let dayNum = 20, typeOfCar = "Luxury"
// console.log(calculateRentalCost(dayNum, typeOfCar));





// 13. Bill splitter
// A restaurant wants to calculate the total bill for a table based on the cost of each dish and the number of
// people sharing it. They require a function that takes in the cost of each dish and the number of people sharing
// it and returns an object that contains the total bill and the bill to be paid by each person in the group.

// const bill = (Number_Of_People, Biriyani, Fried_Rice, Chicken_Chap, Chicken_Kasha, Mutton_Kasha, Salad, cold_Drinks, Ice_Creame) => {
//     let obj = {
//         Number_Of_People, Biriyani, Fried_Rice, Chicken_Chap, Chicken_Kasha, Mutton_Kasha, Salad, cold_Drinks, Ice_Creame
//     }
//     return obj
// }
// console.log(bill(10, 6, 4, 2, 4, 4, 10, 5, 5));





// 14. Calculate the final order price....................................
// A retail store needs to calculate the total cost of items in a customer's cart. A customer cart is an array of
// objects with unit price and quantity. Implement an arrow function to calculate the total cost of items, based on
// the unit price and quantity of each item.

// const itemsAndQuantity = [{item: 199, quantity: 2}, {item: 299, quantity: 1}, {item: 599, quantity: 4}]

// let calculation = (itemsAndQuantity) => {
//     let total = 0
//     itemsAndQuantity.map((items) => {
//         total += items.item * items.quantity
//     })
//     return total
// }

// console.log(calculation(itemsAndQuantity));






// 15. Calculate the percentage of the discount
// A retail store is offering a discount on its products and wants to calculate the percentage of the discount to
// show customers how much they can save. Given the original price and the discounted price of a product,
// implement an arrow function to calculate the percentage of the discount rounded off to two decimal places.
// This function could be useful for the store's marketing team to create promotions and offers that attract
// customers

// const originalPrice = 299
// let discountedPrice = 21.5

// let calculatePercentage = (originalPrice, discountedPrice) => {
//     let discount = (100 * (discountedPrice / originalPrice))
//     return discount.toFixed(2) //I'm using toFixed function to print number upto 2 decimal after dot 
// }

// console.log(calculatePercentage(originalPrice, discountedPrice));




// 16. Generate a random number...................................................
// Create a JavaScript program that generates a random number between 1 and 100 when the program starts.
// Use a self-invoking arrow function to generate the random number. This program can be used as a component
// in various games or applications that require a random number generator.

// let func = () => {
//     return (Math.floor(Math.random() * 100))
// }
// console.log(func());





// 17. Build a banking application.............................................................
// A banking application needs to manage customer accounts and transactions. The user detail is stored in an
// object with a keys name and balance. Write functions using object methods to update a customer's account
// balance based on a deposit or withdrawal. 
// Create an object representing a customer's account
// let customerAccount = {
//     name: "John Doe",
//     balance: 1000
//   };
  
//   // Function to deposit an amount into the customer's account
//   function deposit(amount) {
//     this.balance += amount;
//     console.log(`Deposit of ${amount} successful. New balance is ${this.balance}.`);
//   }
  
//   // Function to withdraw an amount from the customer's account
//   function withdraw(amount) {
//     if (this.balance < amount) {
//       console.log(`Insufficient balance. Withdrawal of ${amount} unsuccessful.`);
//     } else {
//       this.balance -= amount;
//       console.log(`Withdrawal of ${amount} successful. New balance is ${this.balance}.`);
//     }
//   }
  
  // Example usage of the deposit and withdraw functions
  console.log(`Initial balance for ${customerAccount.name}: ${customerAccount.balance}`);
  deposit.call(customerAccount, 500); // Deposit 500
  withdraw.call(customerAccount, 200); // Withdraw 200
  withdraw.call(customerAccount, 1500); // Withdraw 1500 (should fail due to insufficient balance)
  
