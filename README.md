<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script >
      // Question :01

// var firstName = prompt("Enter your first name!");
// var lastName = prompt("Enter your last name!");
// var fullName =  firstName+ " " + lastName;
// alert("Hello, " + fullName + "! Welcome.");


// Question :02


// var mobileModle = prompt("Enter your favorite mobile phone modle.");
// var modelLength = mobileModle.length;
// alert("The length of your input is: " + modelLength)


// Question :03


// var word = "Pakistani";
// var index = word.indexOf("n");
// alert("String: Pakistani index of 'n': " + index)


// Question :04

// var word = "Hello World";
// var  find = word.lastIndexOf("l");
// alert("String: Hello World Last index of 'l': " + find);


// Question :05

// var word = "Pakistani";
// var findChart = word.charAt(3);
// alert("String: Pakistani Character at index 3 : i");


// Question :06

// var firstName = prompt("Enter your first name!");
// var lastName = prompt("Enter your last name!");
// var  fullName = firstName.concat(" ", lastName);
// alert("Hello, " + fullName + "! Welcome.");


// Question :07

// var word = "Hyderabad";
// var newWord = word.replace("Hyder", "Islam");
// alert("City Hyderabad After Replacement: " + newWord);

// Question :08

// var message = "Ali and Sami are best friends. They play cricket and football together.";
// var newMessage = message.replace(/and/g, "&");
// alert("Original message: " + message + "\n\nUpdated message: " + newMessage);


// Question :09

// var str = "472";
// var num = Number(str);

// alert("Value: " + num + "\nType: " + typeof num +
//     "\nValue: " + str + "\nType: " + typeof str);


// Question :10

// var userInput = prompt("Enter some text:");
// var capitalizedInput = userInput.toUpperCase();

// alert("Input in capital letters: " + capitalizedInput);


// Question :11

// var userInput = prompt("Enter some text:");

// var words = userInput.split(' ');
// var titleCasedInput = "";

// for (var i = 0; i < words.length; i++) {
//     titleCasedInput = words[i].charAt(0).toUpperCase() + words[i].slice(1).toLowerCase() + " ";
// }

// titleCasedInput = titleCasedInput;

// alert("Input in title case: " + titleCasedInput);


// Question :12

// var num = 35.63;
// var stringWithoutPoint = num.toString().replace('.', '');

// alert("Result: " + stringWithoutPoint);




// Question :13


// var username = prompt("Enter your username:");
// var invalidChars = ['@', '.', '!', ','];

// for (var i = 0; i < invalidChars.length; i++) {
//     if (username.includes(invalidChars[i])) {
//         alert("Please enter a valid username");
//         username = prompt("Enter a valid username:");
//     }
// }

// alert("Username accepted: " + username);


// Question :14


// var list = ["cake", "apple pie", "cookie", "chips", "patties"];
// var userInput = prompt("Welcome to our Bakery. What do you want to order Sir / Ma'am");
// var found = false;

// for (var i = 0; i < list.length; i++) {
//     if (list[i].toLowerCase() === userInput.toLowerCase()) {
//         found = true;
//         break;
//     }
// }

// if (found) {
//     alert("The item '" + userInput + "' is available in the list.");
// } else {
//     alert("The item '" + userInput + "' is not available in the list.");
// }


// Question :15



// var password = prompt("Enter your password:");
// var hasLetter = /[a-zA-Z]/.test(password);
// var hasNumber = /[0-9]/.test(password);
// var startsWithNumber = /^[0-9]/.test(password);
// var isLongEnough = password.length >= 6;

// if (hasLetter && hasNumber && !startsWithNumber && isLongEnough) {

//     alert("Your password is valid: " + password);
// } else {

//     var errorMessage = "Invalid password. Please make sure that:\n";
//     if (!hasLetter) {
//         errorMessage += "- It contains at least one letter.\n";
//     }
//     if (!hasNumber) {
//         errorMessage += "- It contains at least one number.\n";
//     }
//     if (startsWithNumber) {
//         errorMessage += "- It does not start with a number.\n";
//     }
//     if (!isLongEnough) {
//         errorMessage += "- It is at least 6 characters long.\n";
//     }
//     alert(errorMessage);
// }


// Question :16

// var university = "University of Karachi";
// var universityArray = university.split("");

// for (var i = 0; i < universityArray.length; i++) {
//     document.write(universityArray[i] + "<br>");
// }


// Question :17

// var userInput = prompt("Enter a string:");
// var lastChar = userInput.charAt(userInput.length - 1);

// alert("The last character of your input is: " + lastChar);



// Question :18


// var sentence = "The quick brown fox jumps over the lazy dog";
// var count = (sentence.match(/the/gi) || []).length;

// alert("The word 'the' occurs " + count + " times in the given sentence: " + sentence);
    </script>
</body>
</html>
