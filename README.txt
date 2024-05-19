TASK 1
Function Declaration:
The function processArray is declared to accept a single parameter, array, which is an array of numbers.

Initialize Result Array:
An empty array result is initialized to store the processed numbers.

Iterate Through the Input Array:
A for...of loop is used to iterate through each number (num) in the input array.

Check if the Number is Even or Odd:
Inside the loop, each number is checked using the modulus operator (%) to determine if it is even or odd.
If the number is even (num % 2 === 0), it is squared (num * num) and added to the result array.
If the number is odd, it is tripled (num * 3) and added to the result array.

Return the Result Array:
The result array containing the processed numbers is returned.

Example Usage:
An example array numbers is provided to demonstrate how the processArray function works.
The function is called with numbers as the argument, and the result is logged to the console.
This completes the task of creating a function that processes an array of numbers by squaring even numbers and tripling odd numbers. Save this code in a file named arrayManipulation.js.

TASK 2
Function Declaration for formatArrayStrings:
The function formatArrayStrings is declared to accept two parameters: strings (an array of strings) and numbers (an array of numbers processed by processArray).

Check for Array Length Mismatch:
An error is thrown if the lengths of the strings and numbers arrays are not equal to ensure that there is a corresponding number for each string.

Initialize Formatted Strings Array:
An empty array formattedStrings is initialized to store the modified strings.

Iterate Through the Arrays:
A for loop is used to iterate through the indices of the strings and numbers arrays.
For each index, the corresponding number is checked to determine if it is even or odd.
If the number is even (numbers[i] % 2 === 0), the corresponding string (strings[i]) is converted to uppercase and added to the formattedStrings array.
If the number is odd, the string is converted to lowercase and added to the formattedStrings array.

Return the Formatted Strings Array:
The formattedStrings array containing the modified strings is returned.

Example Usage:
The processArray function is called with a sample array of numbers.
The formatArrayStrings function is then called with a sample array of strings and the processed numbers.
The results are logged to the console.
By following these steps, we have successfully added the formatArrayStrings function to the arrayManipulation.js file, which modifies strings based on corresponding processed numbers.

TASK 3
Explanation
Function Declaration:

The function createUserProfiles is declared to accept two parameters: names (an array of original names) and modifiedNames (an array of modified names).
Check for Array Length Mismatch:

An error is thrown if the lengths of the names and modifiedNames arrays are not equal to ensure that there is a corresponding modified name for each original name.
Initialize User Profiles Array:

An empty array userProfiles is initialized to store the user profile objects.
Iterate Through the Arrays:

A for loop is used to iterate through the indices of the names and modifiedNames arrays.
For each index, a user profile object is created containing the original name, the modified name, and an ID (i + 1).
Add User Profile to Array:

The user profile object is added to the userProfiles array.
Return the User Profiles Array:

The userProfiles array containing the user profile objects is returned.
Example Usage:

Example arrays names and modifiedNames are provided to demonstrate how the createUserProfiles function works.
The function is called with the example arrays, and the result is logged to the console.
By following these steps, we have successfully implemented the createUserProfiles function in the userInfo.js file. This function creates user profiles from the given original and modified names.
