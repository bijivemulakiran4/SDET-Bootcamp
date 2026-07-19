# Javascript : 

 JavaScript is a powerful scripting language that you can use to make web pages interactive. It's one of the core technologies of the web, along with HTML and CSS. All modern browsers support JavaScript.

# Variables : 
 A variable points to a specific memory address that stores a value. Variables are given a name which can be used throughout your code to access that value.

 Declaring a variable means giving it a name. In JavaScript, this is often done with the let keyword. For example, here is how you would declare a hello variable:

 let hello;
 Variable naming follows specific rules: names can include letters, numbers, dollar signs, and underscores, but cannot contain spaces and must not begin with a number.

 -> When a variable is declared with the let keyword, you can reassign (or change the value  of) that variable later on. In this example, the value of programmer is changed from "Naomi" to "CamperChan".

 -> When variable names are more than one word, there are specific naming conventions for how you capitalize the words. In JavaScript, the convention to use is camel case.

  Camel case means that the first word in the name is entirely lowercase, but the following words are all title-cased. Here are some examples of camel case:

 Example Code
 let variableOne;
 let secondVariable;

# String
 JavaScript has seven primitive data types, with String being one of them. In JavaScript, a string represents a sequence of characters and can be enclosed in either single (') or double (") quotes.

# Console

 The console allows you to print and view JavaScript output. You can send information to the console using console.log(). For example, this code will print "Naomi" to the console:

 Example Code
 let developer = "Naomi";
 console.log(developer);

# Array

 An array is a non-primitive data type that can hold a series of values. Non-primitive data types differ from primitive data types in that they can hold more complex data. Primitive data types like strings and numbers can only hold one value at a time.

 Arrays are denoted using square brackets ([]).

 You can access the values inside an array using the index of the value. An index is a number representing the position of the value in the array, starting from 0 for the first value.

 Arrays are special in that they are considered mutable. This means you can change the value at an index directly.
 
 The way of changing values inside the array is called mutable

 You can make use of the .length property of an array - this returns the number of elements in the array. To get the last element of any array, you can use the following syntax:

 Example Code
 array[array.length - 1]
 
 array.length returns the number of elements in the array. By subtracting 1, you get the index of the last element in the array. You can apply this same concept to your rows array