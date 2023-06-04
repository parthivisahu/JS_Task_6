# JS_Task_6
# JavaScript Function to Sort Letters in Alphabetical Order

This JavaScript function allows you to sort the letters of a passed string in alphabetical order. It takes a string as input and returns the sorted string as output.

## Usage

1. Include the JavaScript function in your code or script file:

   ```javascript
   function sortStringAlphabetically(str) {
     const sortedString = str.split('').sort().join('');
     return sortedString;
   }
   ```

2. Call the `sortStringAlphabetically` function with a string as an argument:

   ```javascript
   const inputString = 'openai';
   const sortedString = sortStringAlphabetically(inputString);
   console.log(sortedString);
   ```

   The `sortStringAlphabetically` function will sort the letters of the input string in alphabetical order and assign the sorted string to the `sortedString` variable. It will then log the sorted string to the console.

## Example

```javascript
function sortStringAlphabetically(str) {
  const sortedString = str.split('').sort().join('');
  return sortedString;
}

const inputString = 'openai';
const sortedString = sortStringAlphabetically(inputString);
console.log(sortedString);
```

The output of the above example will be:

```
aeinop
```

The `sortStringAlphabetically` function sorts the letters of the input string in alphabetical order. In the example, the string "openai" is sorted to "aeinop" and logged to the console.

Feel free to use this function in your JavaScript code to sort strings alphabetically as needed.
