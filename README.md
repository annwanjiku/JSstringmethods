# JavaScript String Methods
JavaScript provides various string methods to manipulate and analyze text data. Below are some commonly used methods with examples.

## 1. `charAt(index)`
Returns the character at a specified index.
```javascript
let str = "Hello, JavaScript!";
console.log(str.charAt(0)); // 'H'
```

## 2. `includes(substring)`
Checks if a substring exists within a string.
```javascript
console.log(str.includes("Java")); // true
```

## 3. `indexOf(substring)`
Returns the first index of a substring.
```javascript
console.log(str.indexOf("Java")); // 7
```

## 4. `lastIndexOf(substring)`
Returns the last index of a substring.
```javascript
console.log(str.lastIndexOf("a")); // 10
```

## 5. `slice(start, end)`
Extracts part of a string.
```javascript
console.log(str.slice(7, 17)); // "JavaScript"
```

## 6. `substring(start, end)`
Similar to slice, but does not accept negative values.
```javascript
console.log(str.substring(7, 17)); // "JavaScript"
```

## 7. `substr(start, length)`
Extracts a portion of a string based on length.
```javascript
console.log(str.substr(7, 10)); // "JavaScript"
```

## 8. `toUpperCase()`
Converts the string to uppercase.
```javascript
console.log(str.toUpperCase());
```

## 9. `toLowerCase()`
Converts the string to lowercase.
```javascript
console.log(str.toLowerCase());
```

## 10. `trim()`
Removes whitespace from both ends of a string.
```javascript
let spacedStr = "  Hello  ";
console.log(spacedStr.trim()); // "Hello"
```

## 11. `replace(oldValue, newValue)`
Replaces part of a string.
```javascript
console.log(str.replace("Hello", "Hi"));
```

## 12. `split(separator)`
Splits a string into an array based on a separator.
```javascript
console.log(str.split(",")); // ["Hello", " JavaScript!"]
```

## 13. `concat()`
Concatenates strings.
```javascript
console.log(str.concat(" - Welcome!"));
```

## 14. `repeat(count)`
Repeats the string multiple times.
```javascript
console.log(str.repeat(3));
```

## 15. `startsWith(substring)`
Checks if the string starts with a specific substring.
```javascript
console.log(str.startsWith("Hello")); // true
```

## 16. `endsWith(substring)`
Checks if the string ends with a specific substring.
```javascript
console.log(str.endsWith("!")); // true
```

## 17. `padStart(length, char)`
Pads the string at the start to a certain length.
```javascript
console.log(str.padStart(20, "*"));
```

## 18. `padEnd(length, char)`
Pads the string at the end to a certain length.
```javascript
console.log(str.padEnd(20, "*"));
```

## 19. `match(regex)`
Searches for matches using a regex pattern.
```javascript
console.log(str.match(/Java/g)); // ["Java"]
```

## 20. `search(regex)`
Returns the index of a regex match.
```javascript
console.log(str.search(/Java/)); // 7
```
