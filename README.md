# JavaScript String Methods
JavaScript provides various string methods to manipulate and analyze text data. Below are some commonly used methods with examples.

## String Methods and Examples
```javascript
let str = "Hello, JavaScript!";
console.log("Original String:", str);

// charAt(index) - Returns the character at a specified index
console.log("charAt(0):", str.charAt(0)); // 'H'

// includes(substring) - Checks if a substring exists
console.log("includes('Java'):", str.includes("Java")); // true

// indexOf(substring) - Returns the first index of a substring
console.log("indexOf('Java'):", str.indexOf("Java")); // 7

// lastIndexOf(substring) - Returns the last index of a substring
console.log("lastIndexOf('a'):", str.lastIndexOf("a")); // 10

// slice(start, end) - Extracts part of a string
console.log("slice(7, 17):", str.slice(7, 17)); // "JavaScript"

// substring(start, end) - Similar to slice but doesn't accept negative values
console.log("substring(7, 17):", str.substring(7, 17)); // "JavaScript"

// substr(start, length) - Extracts a portion of a string based on length
console.log("substr(7, 10):", str.substr(7, 10)); // "JavaScript"

// toUpperCase() - Converts string to uppercase
console.log("toUpperCase():", str.toUpperCase());

// toLowerCase() - Converts string to lowercase
console.log("toLowerCase():", str.toLowerCase());

// trim() - Removes whitespace from both ends
let spacedStr = "  Hello  ";
console.log("trim():", spacedStr.trim()); // "Hello"

// replace(oldValue, newValue) - Replaces part of a string
console.log("replace('Hello', 'Hi'):", str.replace("Hello", "Hi"));

// split(separator) - Splits string into an array
console.log("split(','):", str.split(","));

// concat() - Concatenates strings
console.log("concat(' - Welcome!'):", str.concat(" - Welcome!"));

// repeat(count) - Repeats string multiple times
console.log("repeat(3):", str.repeat(3));

// startsWith(substring) - Checks if string starts with a specific substring
console.log("startsWith('Hello'):", str.startsWith("Hello")); // true

// endsWith(substring) - Checks if string ends with a specific substring
console.log("endsWith('!'):", str.endsWith("!")); // true

// padStart(length, char) - Pads string at start to a certain length
console.log("padStart(20, '*'):", str.padStart(20, "*"));

// padEnd(length, char) - Pads string at end to a certain length
console.log("padEnd(20, '*'):", str.padEnd(20, "*"));

// match(regex) - Searches for matches using regex
console.log("match(/Java/g):", str.match(/Java/g)); // ["Java"]

// search(regex) - Returns index of regex match
console.log("search(/Java/):", str.search(/Java/)); // 7
