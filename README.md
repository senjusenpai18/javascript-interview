# 300+ JavaScript Coding Questions - Complete Practice Guide

## Table of Contents
- [Basic Level (Questions 1-75)](#basic-level-questions-1-75)
- [Intermediate Level (Questions 76-150)](#intermediate-level-questions-76-150)
- [Advanced Level (Questions 151-225)](#advanced-level-questions-151-225)
- [Expert Level (Questions 226-300+)](#expert-level-questions-226-300)

---

## Basic Level (Questions 1-75)

### Variables & Data Types

**1. Variable Declaration**
- **Question:** Create variables using var, let, and const with different values
- **Explanation:** Demonstrate understanding of variable declarations and their differences
- **Input:** No input required
- **Output:** Variables declared with values: name="John", age=25, isActive=true
- **Answer:** Variables successfully declared with specified values

**2. Data Type Check**
- **Question:** Check and return the data type of given values
- **Explanation:** Use typeof operator to determine data types
- **Input:** [42, "hello", true, null, undefined, {}, []]
- **Output:** Array of data types for each input
- **Answer:** ["number", "string", "boolean", "object", "undefined", "object", "object"]

**3. String Concatenation**
- **Question:** Concatenate firstName and lastName with a space
- **Explanation:** Join two strings with proper spacing
- **Input:** firstName = "John", lastName = "Doe"
- **Output:** Full name as single string
- **Answer:** "John Doe"

**4. Number Operations**
- **Question:** Perform basic arithmetic operations on two numbers
- **Explanation:** Calculate sum, difference, product, quotient, and remainder
- **Input:** a = 15, b = 4
- **Output:** Object with all operations
- **Answer:** {sum: 19, diff: 11, product: 60, quotient: 3.75, remainder: 3}

**5. Boolean Logic**
- **Question:** Determine if a number is both positive and even
- **Explanation:** Use logical AND operator with multiple conditions
- **Input:** num = 8
- **Output:** Boolean result
- **Answer:** true

**6. Array Creation**
- **Question:** Create an array with numbers from 1 to 5
- **Explanation:** Initialize array with consecutive integers
- **Input:** No input required
- **Output:** Array of numbers 1-5
- **Answer:** [1, 2, 3, 4, 5]

**7. Object Creation**
- **Question:** Create an object representing a person with name, age, and city
- **Explanation:** Define object with specified properties
- **Input:** name="Alice", age=30, city="New York"
- **Output:** Person object
- **Answer:** {name: "Alice", age: 30, city: "New York"}

**8. Null vs Undefined**
- **Question:** Demonstrate difference between null and undefined
- **Explanation:** Show when each value type occurs
- **Input:** Declare variable without assignment and assign null to another
- **Output:** Both values and their types
- **Answer:** undefined (type: undefined), null (type: object)

**9. String Length**
- **Question:** Find the length of a given string
- **Explanation:** Use string length property
- **Input:** str = "JavaScript"
- **Output:** Length of string
- **Answer:** 10

**10. Array Length**
- **Question:** Find length of an array
- **Explanation:** Access array length property
- **Input:** arr = [1, 2, 3, 4, 5, 6]
- **Output:** Array length
- **Answer:** 6

### Basic Operations & Functions

**11. Simple Function**
- **Question:** Create function that adds two numbers
- **Explanation:** Define function with parameters and return sum
- **Input:** a = 5, b = 3
- **Output:** Sum of inputs
- **Answer:** 8

**12. String Uppercase**
- **Question:** Convert string to uppercase
- **Explanation:** Use built-in string method for case conversion
- **Input:** str = "hello world"
- **Output:** Uppercase string
- **Answer:** "HELLO WORLD"

**13. String Lowercase**
- **Question:** Convert string to lowercase
- **Explanation:** Use built-in string method for case conversion
- **Input:** str = "HELLO WORLD"
- **Output:** Lowercase string
- **Answer:** "hello world"

**14. Even or Odd**
- **Question:** Determine if number is even or odd
- **Explanation:** Use modulo operator to check divisibility by 2
- **Input:** num = 7
- **Output:** "even" or "odd"
- **Answer:** "odd"

**15. Maximum of Two**
- **Question:** Find maximum of two numbers
- **Explanation:** Compare two numbers and return larger one
- **Input:** a = 12, b = 8
- **Output:** Maximum value
- **Answer:** 12

**16. Minimum of Two**
- **Question:** Find minimum of two numbers
- **Explanation:** Compare two numbers and return smaller one
- **Input:** a = 12, b = 8
- **Output:** Minimum value
- **Answer:** 8

**17. Absolute Value**
- **Question:** Find absolute value of a number
- **Explanation:** Return positive value regardless of input sign
- **Input:** num = -15
- **Output:** Absolute value
- **Answer:** 15

**18. Square of Number**
- **Question:** Calculate square of given number
- **Explanation:** Multiply number by itself
- **Input:** num = 6
- **Output:** Square value
- **Answer:** 36

**19. Age Category**
- **Question:** Categorize person based on age (child, teen, adult, senior)
- **Explanation:** Use conditional statements for age ranges
- **Input:** age = 17
- **Output:** Age category
- **Answer:** "teen"

**20. Grade Calculator**
- **Question:** Convert numeric score to letter grade
- **Explanation:** Use conditional logic for grade boundaries
- **Input:** score = 85
- **Output:** Letter grade
- **Answer:** "B"

### Arrays & Basic Methods

**21. Array Access**
- **Question:** Access first and last elements of array
- **Explanation:** Use index notation for array element access
- **Input:** arr = [10, 20, 30, 40, 50]
- **Output:** Object with first and last elements
- **Answer:** {first: 10, last: 50}

**22. Array Push**
- **Question:** Add element to end of array
- **Explanation:** Use push method to append element
- **Input:** arr = [1, 2, 3], element = 4
- **Output:** Modified array
- **Answer:** [1, 2, 3, 4]

**23. Array Pop**
- **Question:** Remove last element from array
- **Explanation:** Use pop method and return removed element
- **Input:** arr = [1, 2, 3, 4]
- **Output:** Removed element
- **Answer:** 4

**24. Array Shift**
- **Question:** Remove first element from array
- **Explanation:** Use shift method and return removed element
- **Input:** arr = [1, 2, 3, 4]
- **Output:** Removed element
- **Answer:** 1

**25. Array Unshift**
- **Question:** Add element to beginning of array
- **Explanation:** Use unshift method to prepend element
- **Input:** arr = [2, 3, 4], element = 1
- **Output:** Modified array
- **Answer:** [1, 2, 3, 4]

**26. Array Join**
- **Question:** Convert array elements to string with separator
- **Explanation:** Use join method with custom separator
- **Input:** arr = ["apple", "banana", "cherry"], separator = ", "
- **Output:** Joined string
- **Answer:** "apple, banana, cherry"

**27. Array Slice**
- **Question:** Extract portion of array
- **Explanation:** Use slice method with start and end indices
- **Input:** arr = [1, 2, 3, 4, 5], start = 1, end = 4
- **Output:** Sliced array
- **Answer:** [2, 3, 4]

**28. Array Includes**
- **Question:** Check if array contains specific value
- **Explanation:** Use includes method for value existence check
- **Input:** arr = [1, 2, 3, 4, 5], value = 3
- **Output:** Boolean result
- **Answer:** true

**29. Array Index**
- **Question:** Find index of specific element in array
- **Explanation:** Use indexOf method to locate element position
- **Input:** arr = ["a", "b", "c", "d"], element = "c"
- **Output:** Index of element
- **Answer:** 2

**30. Array Reverse**
- **Question:** Reverse elements in array
- **Explanation:** Use reverse method to invert array order
- **Input:** arr = [1, 2, 3, 4, 5]
- **Output:** Reversed array
- **Answer:** [5, 4, 3, 2, 1]

### String Methods

**31. String Character At**
- **Question:** Get character at specific position
- **Explanation:** Use charAt method for character access
- **Input:** str = "Hello", index = 1
- **Output:** Character at index
- **Answer:** "e"

**32. String Substring**
- **Question:** Extract substring from string
- **Explanation:** Use substring method with start and end positions
- **Input:** str = "JavaScript", start = 0, end = 4
- **Output:** Extracted substring
- **Answer:** "Java"

**33. String Split**
- **Question:** Split string into array using delimiter
- **Explanation:** Use split method to break string into parts
- **Input:** str = "apple,banana,cherry", delimiter = ","
- **Output:** Array of split parts
- **Answer:** ["apple", "banana", "cherry"]

**34. String Replace**
- **Question:** Replace first occurrence of substring
- **Explanation:** Use replace method for string substitution
- **Input:** str = "Hello World", oldStr = "World", newStr = "JavaScript"
- **Output:** Modified string
- **Answer:** "Hello JavaScript"

**35. String Trim**
- **Question:** Remove whitespace from both ends of string
- **Explanation:** Use trim method to clean string
- **Input:** str = "  Hello World  "
- **Output:** Trimmed string
- **Answer:** "Hello World"

**36. String Starts With**
- **Question:** Check if string starts with specific substring
- **Explanation:** Use startsWith method for prefix checking
- **Input:** str = "JavaScript", prefix = "Java"
- **Output:** Boolean result
- **Answer:** true

**37. String Ends With**
- **Question:** Check if string ends with specific substring
- **Explanation:** Use endsWith method for suffix checking
- **Input:** str = "JavaScript", suffix = "Script"
- **Output:** Boolean result
- **Answer:** true

**38. String Repeat**
- **Question:** Repeat string specified number of times
- **Explanation:** Use repeat method for string duplication
- **Input:** str = "Ha", count = 3
- **Output:** Repeated string
- **Answer:** "HaHaHa"

**39. String Padding Start**
- **Question:** Pad string at beginning to reach target length
- **Explanation:** Use padStart method with fill character
- **Input:** str = "5", targetLength = 3, padChar = "0"
- **Output:** Padded string
- **Answer:** "005"

**40. String Padding End**
- **Question:** Pad string at end to reach target length
- **Explanation:** Use padEnd method with fill character
- **Input:** str = "5", targetLength = 3, padChar = "0"
- **Output:** Padded string
- **Answer:** "500"

### Basic Control Structures

**41. Simple If Statement**
- **Question:** Check if number is positive
- **Explanation:** Use if statement for condition checking
- **Input:** num = 5
- **Output:** "positive" or "not positive"
- **Answer:** "positive"

**42. If-Else Statement**
- **Question:** Check if number is positive or negative
- **Explanation:** Use if-else for binary condition
- **Input:** num = -3
- **Output:** "positive" or "negative"
- **Answer:** "negative"

**43. If-Else-If Chain**
- **Question:** Categorize temperature (cold, warm, hot)
- **Explanation:** Use multiple conditions with else-if
- **Input:** temp = 75
- **Output:** Temperature category
- **Answer:** "warm"

**44. Switch Statement**
- **Question:** Convert day number to day name
- **Explanation:** Use switch statement for multiple discrete values
- **Input:** dayNum = 3
- **Output:** Day name
- **Answer:** "Wednesday"

**45. Ternary Operator**
- **Question:** Use ternary operator to find max of two numbers
- **Explanation:** Implement conditional logic in single expression
- **Input:** a = 8, b = 12
- **Output:** Maximum value
- **Answer:** 12

**46. For Loop Sum**
- **Question:** Calculate sum of numbers from 1 to n
- **Explanation:** Use for loop for iterative calculation
- **Input:** n = 5
- **Output:** Sum of numbers
- **Answer:** 15

**47. While Loop Counter**
- **Question:** Count down from n to 1
- **Explanation:** Use while loop for countdown
- **Input:** n = 5
- **Output:** Array of countdown numbers
- **Answer:** [5, 4, 3, 2, 1]

**48. Do-While Loop**
- **Question:** Generate random numbers until getting one greater than 0.5
- **Explanation:** Use do-while loop that executes at least once
- **Input:** No input (random generation)
- **Output:** Array of generated numbers
- **Answer:** [0.2, 0.3, 0.7] (example output)

**49. For-In Loop**
- **Question:** Iterate through object properties
- **Explanation:** Use for-in loop to access object keys
- **Input:** obj = {name: "John", age: 25, city: "NYC"}
- **Output:** Array of property names
- **Answer:** ["name", "age", "city"]

**50. For-Of Loop**
- **Question:** Iterate through array elements
- **Explanation:** Use for-of loop for array traversal
- **Input:** arr = [10, 20, 30]
- **Output:** Array of elements (same as input)
- **Answer:** [10, 20, 30]

### Basic Functions & Scope

**51. Function Declaration**
- **Question:** Create function that multiplies two numbers
- **Explanation:** Define named function with parameters
- **Input:** a = 6, b = 7
- **Output:** Product of inputs
- **Answer:** 42

**52. Function Expression**
- **Question:** Create function expression that divides two numbers
- **Explanation:** Assign function to variable
- **Input:** a = 20, b = 4
- **Output:** Division result
- **Answer:** 5

**53. Arrow Function**
- **Question:** Create arrow function that calculates square
- **Explanation:** Use arrow function syntax
- **Input:** num = 8
- **Output:** Square of input
- **Answer:** 64

**54. Function with Default Parameters**
- **Question:** Create greeting function with default name
- **Explanation:** Use default parameter values
- **Input:** name = undefined (use default "Guest")
- **Output:** Greeting message
- **Answer:** "Hello, Guest!"

**55. Function Return**
- **Question:** Create function that returns object with multiple values
- **Explanation:** Return complex data structure from function
- **Input:** radius = 5
- **Output:** Object with area and circumference
- **Answer:** {area: 78.54, circumference: 31.42}

**56. Variable Scope**
- **Question:** Demonstrate difference between global and local variables
- **Explanation:** Show how scope affects variable access
- **Input:** No input required
- **Output:** Values from different scopes
- **Answer:** {global: "global", local: "local"}

**57. Hoisting Example**
- **Question:** Show variable hoisting behavior
- **Explanation:** Demonstrate how var declarations are hoisted
- **Input:** No input required
- **Output:** Variable values before and after declaration
- **Answer:** {before: undefined, after: "initialized"}

**58. Let vs Var**
- **Question:** Demonstrate block scope difference
- **Explanation:** Show how let differs from var in loops
- **Input:** No input required
- **Output:** Array showing scope behavior
- **Answer:** [0, 1, 2] for let, [3, 3, 3] for var

**59. Const Behavior**
- **Question:** Show const variable behavior with objects
- **Explanation:** Demonstrate const immutability rules
- **Input:** No input required
- **Output:** Modified object with same reference
- **Answer:** {name: "John", age: 26} (age modified)

**60. Recursive Function**
- **Question:** Calculate factorial using recursion
- **Explanation:** Implement recursive function call
- **Input:** n = 5
- **Output:** Factorial result
- **Answer:** 120

### Math & Number Methods

**61. Math.max**
- **Question:** Find maximum value from array of numbers
- **Explanation:** Use Math.max with spread operator
- **Input:** numbers = [3, 7, 2, 9, 1]
- **Output:** Maximum value
- **Answer:** 9

**62. Math.min**
- **Question:** Find minimum value from array of numbers
- **Explanation:** Use Math.min with spread operator
- **Input:** numbers = [3, 7, 2, 9, 1]
- **Output:** Minimum value
- **Answer:** 1

**63. Math.round**
- **Question:** Round number to nearest integer
- **Explanation:** Use Math.round for standard rounding
- **Input:** num = 4.6
- **Output:** Rounded number
- **Answer:** 5

**64. Math.ceil**
- **Question:** Round number up to nearest integer
- **Explanation:** Use Math.ceil for ceiling function
- **Input:** num = 4.1
- **Output:** Ceiling value
- **Answer:** 5

**65. Math.floor**
- **Question:** Round number down to nearest integer
- **Explanation:** Use Math.floor for floor function
- **Input:** num = 4.9
- **Output:** Floor value
- **Answer:** 4

**66. Math.random**
- **Question:** Generate random number between 1 and 10
- **Explanation:** Use Math.random with scaling and offset
- **Input:** No input required
- **Output:** Random integer between 1-10
- **Answer:** 7 (example)

**67. Math.pow**
- **Question:** Calculate power of number
- **Explanation:** Use Math.pow for exponentiation
- **Input:** base = 2, exponent = 3
- **Output:** Power result
- **Answer:** 8

**68. Math.sqrt**
- **Question:** Calculate square root of number
- **Explanation:** Use Math.sqrt for square root calculation
- **Input:** num = 16
- **Output:** Square root
- **Answer:** 4

**69. Number.parseInt**
- **Question:** Parse string to integer
- **Explanation:** Convert string representation to integer
- **Input:** str = "42px"
- **Output:** Parsed integer
- **Answer:** 42

**70. Number.parseFloat**
- **Question:** Parse string to floating point number
- **Explanation:** Convert string representation to float
- **Input:** str = "3.14159"
- **Output:** Parsed float
- **Answer:** 3.14159

### Basic Object Operations

**71. Object Property Access**
- **Question:** Access object properties using dot and bracket notation
- **Explanation:** Demonstrate different ways to access object properties
- **Input:** obj = {name: "Alice", age: 30}
- **Output:** Property values using both methods
- **Answer:** {dotNotation: "Alice", bracketNotation: 30}

**72. Object Property Addition**
- **Question:** Add new property to existing object
- **Explanation:** Dynamically add property to object
- **Input:** obj = {name: "Bob"}, newProp = "email", value = "bob@email.com"
- **Output:** Modified object
- **Answer:** {name: "Bob", email: "bob@email.com"}

**73. Object Property Deletion**
- **Question:** Delete property from object
- **Explanation:** Use delete operator to remove property
- **Input:** obj = {name: "Charlie", age: 25, temp: "remove"}
- **Output:** Object without deleted property
- **Answer:** {name: "Charlie", age: 25}

**74. Object Keys**
- **Question:** Get all property names from object
- **Explanation:** Use Object.keys() to extract property names
- **Input:** obj = {a: 1, b: 2, c: 3}
- **Output:** Array of property names
- **Answer:** ["a", "b", "c"]

**75. Object Values**
- **Question:** Get all property values from object
- **Explanation:** Use Object.values() to extract property values
- **Input:** obj = {a: 1, b: 2, c: 3}
- **Output:** Array of property values
- **Answer:** [1, 2, 3]

---

## Intermediate Level (Questions 76-150)

### Advanced Array Methods

**76. Array Map**
- **Question:** Transform array elements by doubling each value
- **Explanation:** Use map method to create new array with transformed elements
- **Input:** arr = [1, 2, 3, 4, 5]
- **Output:** Array with doubled values
- **Answer:** [2, 4, 6, 8, 10]

**77. Array Filter**
- **Question:** Filter array to keep only even numbers
- **Explanation:** Use filter method to create new array with filtered elements
- **Input:** arr = [1, 2, 3, 4, 5, 6, 7, 8]
- **Output:** Array with only even numbers
- **Answer:** [2, 4, 6, 8]

**78. Array Reduce**
- **Question:** Calculate product of all array elements
- **Explanation:** Use reduce method to accumulate array values
- **Input:** arr = [2, 3, 4, 5]
- **Output:** Product of all elements
- **Answer:** 120

**79. Array Find**
- **Question:** Find first element greater than 10
- **Explanation:** Use find method to locate first matching element
- **Input:** arr = [5, 8, 12, 3, 15, 2]
- **Output:** First element > 10
- **Answer:** 12

**80. Array FindIndex**
- **Question:** Find index of first negative number
- **Explanation:** Use findIndex to locate position of first matching element
- **Input:** arr = [2, 5, -3, 8, -1]
- **Output:** Index of first negative number
- **Answer:** 2

**81. Array Some**
- **Question:** Check if array contains any number greater than 100
- **Explanation:** Use some method to test if any element meets condition
- **Input:** arr = [45, 67, 23, 145, 89]
- **Output:** Boolean result
- **Answer:** true

**82. Array Every**
- **Question:** Check if all numbers in array are positive
- **Explanation:** Use every method to test if all elements meet condition
- **Input:** arr = [2, 5, 8, 12, 3]
- **Output:** Boolean result
- **Answer:** true

**83. Array Sort Numbers**
- **Question:** Sort array of numbers in ascending order
- **Explanation:** Use sort method with numeric comparison function
- **Input:** arr = [3, 1, 4, 1, 5, 9, 2, 6]
- **Output:** Sorted array
- **Answer:** [1, 1, 2, 3, 4, 5, 6, 9]

**84. Array Sort Strings**
- **Question:** Sort array of strings alphabetically
- **Explanation:** Use sort method for string comparison
- **Input:** arr = ["banana", "apple", "cherry", "date"]
- **Output:** Alphabetically sorted array
- **Answer:** ["apple", "banana", "cherry", "date"]

**85. Array Concatenation**
- **Question:** Merge multiple arrays into one
- **Explanation:** Use concat method or spread operator
- **Input:** arr1 = [1, 2], arr2 = [3, 4], arr3 = [5, 6]
- **Output:** Combined array
- **Answer:** [1, 2, 3, 4, 5, 6]

**86. Array Flat**
- **Question:** Flatten nested array one level deep
- **Explanation:** Use flat method to reduce array nesting
- **Input:** arr = [1, [2, 3], [4, [5, 6]]]
- **Output:** Flattened array
- **Answer:** [1, 2, 3, 4, [5, 6]]

**87. Array FlatMap**
- **Question:** Map and flatten array in single operation
- **Explanation:** Use flatMap to transform and flatten simultaneously
- **Input:** arr = [1, 2, 3]
- **Output:** Array where each element becomes [x, x*2]
- **Answer:** [1, 2, 2, 4, 3, 6]

**88. Array Splice**
- **Question:** Remove 2 elements starting at index 1 and insert new elements
- **Explanation:** Use splice method for array modification
- **Input:** arr = [1, 2, 3, 4, 5], start = 1, deleteCount = 2, items = [8, 9]
- **Output:** Modified array
- **Answer:** [1, 8, 9, 4, 5]

**89. Array Fill**
- **Question:** Fill array with specific value between indices
- **Explanation:** Use fill method to replace array elements
- **Input:** arr = [1, 2, 3, 4, 5], value = 0, start = 1, end = 4
- **Output:** Array with filled values
- **Answer:** [1, 0, 0, 0, 5]

**90. Array From**
- **Question:** Create array from string characters
- **Explanation:** Use Array.from to convert iterable to array
- **Input:** str = "hello"
- **Output:** Array of characters
- **Answer:** ["h", "e", "l", "l", "o"]

### String Advanced Methods

**91. String Match**
- **Question:** Find all digits in string using regex
- **Explanation:** Use match method with regular expression
- **Input:** str = "Phone: 123-456-7890"
- **Output:** Array of matched digits
- **Answer:** ["1", "2", "3", "4", "5", "6", "7", "8", "9", "0"]

**92. String Search**
- **Question:** Find position of word in string (case-insensitive)
- **Explanation:** Use search method with regex for pattern matching
- **Input:** str = "JavaScript is awesome", pattern = /script/i
- **Output:** Index of match
- **Answer:** 4

**93. String Replace All**
- **Question:** Replace all occurrences of substring
- **Explanation:** Use replaceAll method or regex with global flag
- **Input:** str = "hello hello world", oldStr = "hello", newStr = "hi"
- **Output:** String with all replacements
- **Answer:** "hi hi world"

**94. String Locale Compare**
- **Question:** Compare two strings for sorting
- **Explanation:** Use localeCompare for proper string comparison
- **Input:** str1 = "apple", str2 = "banana"
- **Output:** Comparison result (-1, 0, or 1)
- **Answer:** -1

**95. String Slice**
- **Question:** Extract substring using negative indices
- **Explanation:** Use slice method with negative start/end positions
- **Input:** str = "JavaScript", start = -6, end = -2
- **Output:** Extracted substring
- **Answer:** "Scri"

**96. Template Literals**
- **Question:** Create formatted string using template literals
- **Explanation:** Use template literal syntax with expressions
- **Input:** name = "John", age = 25, city = "NYC"
- **Output:** Formatted string
- **Answer:** "John is 25 years old and lives in NYC"

**97. String Code Point**
- **Question:** Get Unicode code point of character
- **Explanation:** Use codePointAt method for Unicode values
- **Input:** str = "A", index = 0
- **Output:** Unicode code point
- **Answer:** 65

**98. String From Code Point**
- **Question:** Create string from Unicode code points
- **Explanation:** Use String.fromCodePoint for Unicode conversion
- **Input:** codePoints = [72, 101, 108, 108, 111]
- **Output:** String from code points
- **Answer:** "Hello"

**99. String Normalize**
- **Question:** Normalize Unicode string
- **Explanation:** Use normalize method for Unicode normalization
- **Input:** str = "café" (with combining characters)
- **Output:** Normalized string
- **Answer:** "café" (composed form)

**100. String Raw**
- **Question:** Get raw string template literal
- **Explanation:** Use String.raw for unprocessed template strings
- **Input:** template = String.raw`C:\Users\name\file.txt`
- **Output:** Raw string with backslashes
- **Answer:** "C:\\Users\\name\\file.txt"

### Object Advanced Operations

**101. Object Assign**
- **Question:** Merge multiple objects into target object
- **Explanation:** Use Object.assign for object composition
- **Input:** target = {a: 1}, source1 = {b: 2}, source2 = {c: 3}
- **Output:** Merged object
- **Answer:** {a: 1, b: 2, c: 3}

**102. Object Entries**
- **Question:** Convert object to array of key-value pairs
- **Explanation:** Use Object.entries for object decomposition
- **Input:** obj = {name: "Alice", age: 30, city: "NYC"}
- **Output:** Array of [key, value] pairs
- **Answer:** [["name", "Alice"], ["age", 30], ["city", "NYC"]]

**103. Object From Entries**
- **Question:** Create object from array of key-value pairs
- **Explanation:** Use Object.fromEntries for object reconstruction
- **Input:** entries = [["a", 1], ["b", 2], ["c", 3]]
- **Output:** Object from entries
- **Answer:** {a: 1, b: 2, c: 3}

**104. Object Freeze**
- **Question:** Freeze object to prevent modifications
- **Explanation:** Use Object.freeze for immutability
- **Input:** obj = {name: "John", age: 25}
- **Output:** Frozen object (modifications fail silently)
- **Answer:** {name: "John", age: 25} (unchanged after freeze)

**105. Object Seal**
- **Question:** Seal object to prevent property addition/deletion
- **Explanation:** Use Object.seal for controlled mutability
- **Input:** obj = {name: "Jane", age: 28}
- **Output:** Sealed object (values can change, structure cannot)
- **Answer:** {name: "Jane", age: 29} (age modified but no new props)

**106. Object GetOwnPropertyNames**
- **Question:** Get all property names including non-enumerable
- **Explanation:** Use Object.getOwnPropertyNames for complete property list
- **Input:** obj = {visible: 1}; Object.defineProperty(obj, 'hidden', {value: 2})
- **Output:** Array of all property names
- **Answer:** ["visible", "hidden"]

**107. Object HasOwnProperty**
- **Question:** Check if object has specific property (not inherited)
- **Explanation:** Use hasOwnProperty for own property detection
- **Input:** obj = {name: "Bob"}, prop = "name"
- **Output:** Boolean result
- **Answer:** true

**108. Object Property Descriptor**
- **Question:** Get property descriptor for object property
- **Explanation:** Use Object.getOwnPropertyDescriptor for property metadata
- **Input:** obj = {name: "Alice"}, prop = "name"
- **Output:** Property descriptor object
- **Answer:** {value: "Alice", writable: true, enumerable: true, configurable: true}

**109. Object Define Property**
- **Question:** Define property with custom descriptor
- **Explanation:** Use Object.defineProperty to create property with specific attributes
- **Input:** obj = {}, prop = "age", descriptor = {value: 25, writable: false}
- **Output:** Object with defined property
- **Answer:** {age: 25} (age is non-writable)

**110. Object Create**
- **Question:** Create object with specific prototype
- **Explanation:** Use Object.create for prototype-based object creation
- **Input:** proto = {greet: function() { return "Hello"; }}
- **Output:** Object with proto as prototype
- **Answer:** {} (with greet method in prototype chain)

### Function Advanced Concepts

**111. Function Call**
- **Question:** Use call method to invoke function with specific 'this' context
- **Explanation:** Demonstrate explicit this binding with call()
- **Input:** obj = {name: "John"}, function greet() { return `Hello ${this.name}`; }
- **Output:** Greeting with bound context
- **Answer:** "Hello John"

**112. Function Apply**
- **Question:** Use apply method with array of arguments
- **Explanation:** Invoke function with this binding and argument array
- **Input:** function sum(a, b, c) { return a + b + c; }, args = [1, 2, 3]
- **Output:** Function result with applied arguments
- **Answer:** 6

**113. Function Bind**
- **Question:** Create bound function with fixed 'this' and partial arguments
- **Explanation:** Use bind to create new function with preset context/arguments
- **Input:** function multiply(a, b) { return a * b; }, boundMultiply = multiply.bind(null, 5)
- **Output:** Result of calling bound function with remaining arguments
- **Answer:** 25 (when called with argument 5)

**114. IIFE (Immediately Invoked Function Expression)**
- **Question:** Create and execute function immediately
- **Explanation:** Demonstrate IIFE pattern for module/namespace creation
- **Input:** No external input
- **Output:** Result of immediately executed function
- **Answer:** "IIFE executed"

**115. Closure Basic**
- **Question:** Create closure that maintains private counter
- **Explanation:** Demonstrate closure for data privacy
- **Input:** No input (function factory)
- **Output:** Object with increment and get methods
- **Answer:** {increment: function, getCount: function} (count starts at 0)

**116. Closure Advanced**
- **Question:** Create function that returns multiple closures sharing state
- **Explanation:** Multiple functions accessing same lexical environment
- **Input:** initialValue = 10
- **Output:** Object with increment, decrement, and getValue functions
- **Answer:** {increment: fn, decrement: fn, getValue: fn} (shared state = 10)

**117. Function Constructor**
- **Question:** Create function using Function constructor
- **Explanation:** Dynamically create function from string
- **Input:** params = "a, b", body = "return a + b;"
- **Output:** Function that adds two numbers
- **Answer:** function(a, b) { return a + b; }

**118. Generator Function**
- **Question:** Create generator function that yields numbers 1 to 5
- **Explanation:** Use function* syntax and yield keyword
- **Input:** No input required
- **Output:** Generator object that yields sequence
- **Answer:** Generator yields: 1, 2, 3, 4, 5

**119. Generator with Return**
- **Question:** Create generator that yields values and returns final value
- **Explanation:** Demonstrate yield and return in generators
- **Input:** No input required
- **Output:** Generator yields values then returns
- **Answer:** Yields: "a", "b", "c", Returns: "done"

**120. Async Function Basic**
- **Question:** Create async function that waits 1 second then returns value
- **Explanation:** Use async/await for asynchronous operations
- **Input:** value = "Hello"
- **Output:** Promise resolving to value after delay
- **Answer:** Promise<"Hello"> (resolved after 1 second)

### Error Handling

**121. Try-Catch Basic**
- **Question:** Handle division by zero error
- **Explanation:** Use try-catch to handle runtime errors gracefully
- **Input:** a = 10, b = 0
- **Output:** Error message or result
- **Answer:** "Cannot divide by zero"

**122. Try-Catch-Finally**
- **Question:** Demonstrate finally block execution
- **Explanation:** Show finally block runs regardless of error
- **Input:** shouldThrow = true
- **Output:** Messages from try/catch/finally blocks
- **Answer:** ["Error caught", "Finally executed"]

**123. Custom Error**
- **Question:** Create and throw custom error class
- **Explanation:** Extend Error class for specific error types
- **Input:** message = "Custom error occurred"
- **Output:** Custom error with specific properties
- **Answer:** CustomError: "Custom error occurred"

**124. Error Propagation**
- **Question:** Demonstrate error bubbling through call stack
- **Explanation:** Show how unhandled errors propagate
- **Input:** No input required
- **Output:** Error caught at appropriate level
- **Answer:** "Error caught in outer function"

**125. Promise Error Handling**
- **Question:** Handle promise rejection with catch
- **Explanation:** Use .catch() for promise error handling
- **Input:** Promise.reject("Promise failed")
- **Output:** Handled error message
- **Answer:** "Handled: Promise failed"

### Regular Expressions

**126. Regex Test**
- **Question:** Test if string contains valid email format
- **Explanation:** Use regex.test() method for pattern matching
- **Input:** email = "user@example.com"
- **Output:** Boolean validation result
- **Answer:** true

**127. Regex Match Groups**
- **Question:** Extract parts of date string using capture groups
- **Explanation:** Use parentheses in regex for grouping
- **Input:** dateStr = "2023-12-25", pattern = /(\d{4})-(\d{2})-(\d{2})/
- **Output:** Array with full match and groups
- **Answer:** ["2023-12-25", "2023", "12", "25"]

**128. Regex Replace with Function**
- **Question:** Replace matched patterns using callback function
- **Explanation:** Use function as replacement parameter
- **Input:** str = "hello world", pattern = /\b\w/g
- **Output:** String with first letters capitalized
- **Answer:** "Hello World"

**129. Regex Global Match**
- **Question:** Find all occurrences of word boundaries
- **Explanation:** Use global flag to find multiple matches
- **Input:** str = "The quick brown fox", pattern = /\b\w+\b/g
- **Output:** Array of all words
- **Answer:** ["The", "quick", "brown", "fox"]

**130. Regex Lookahead**
- **Question:** Match passwords with positive lookahead for strength
- **Explanation:** Use (?=...) for lookahead assertions
- **Input:** password = "Abc123!", pattern = /^(?=.*[A-Z])(?=.*\d).{6,}$/
- **Output:** Boolean validation result
- **Answer:** true

### DOM-like Operations (Conceptual)

**131. Element Selection Simulation**
- **Question:** Simulate getElementById functionality
- **Explanation:** Find object in array by id property
- **Input:** elements = [{id: "btn1", text: "Click"}, {id: "btn2", text: "Submit"}], targetId = "btn1"
- **Output:** Found element object
- **Answer:** {id: "btn1", text: "Click"}

**132. Class List Simulation**
- **Question:** Simulate classList.add functionality
- **Explanation:** Add class to element's class array
- **Input:** element = {classes: ["btn"]}, newClass = "active"
- **Output:** Element with added class
- **Answer:** {classes: ["btn", "active"]}

**133. Event Handler Simulation**
- **Question:** Simulate addEventListener functionality
- **Explanation:** Add event handler to element's handlers array
- **Input:** element = {handlers: {}}, event = "click", handler = function
- **Output:** Element with added event handler
- **Answer:** {handlers: {click: [function]}}

**134. Style Manipulation Simulation**
- **Question:** Simulate style property manipulation
- **Explanation:** Modify object representing element styles
- **Input:** element = {style: {color: "black"}}, property = "color", value = "red"
- **Output:** Element with modified style
- **Answer:** {style: {color: "red"}}

**135. Attribute Manipulation Simulation**
- **Question:** Simulate setAttribute functionality
- **Explanation:** Add/modify attribute in element's attributes object
- **Input:** element = {attributes: {}}, name = "disabled", value = "true"
- **Output:** Element with set attribute
- **Answer:** {attributes: {disabled: "true"}}

### Advanced Data Structures

**136. Set Basic Operations**
- **Question:** Create Set and perform add, delete, has operations
- **Explanation:** Demonstrate Set for unique value collections
- **Input:** values = [1, 2, 3, 2, 1], checkValue = 2
- **Output:** Set operations results
- **Answer:** {size: 3, has2: true, after_delete: Set{1, 3}}

**137. Set Union**
- **Question:** Create union of two Sets
- **Explanation:** Combine Sets using spread operator or forEach
- **Input:** set1 = Set{1, 2, 3}, set2 = Set{3, 4, 5}
- **Output:** Union Set
- **Answer:** Set{1, 2, 3, 4, 5}

**138. Set Intersection**
- **Question:** Find common elements between two Sets
- **Explanation:** Use filter or iteration to find intersection
- **Input:** set1 = Set{1, 2, 3}, set2 = Set{2, 3, 4}
- **Output:** Intersection Set
- **Answer:** Set{2, 3}

**139. Map Basic Operations**
- **Question:** Create Map and perform set, get, delete operations
- **Explanation:** Demonstrate Map for key-value pairs with any key type
- **Input:** entries = [["name", "John"], [1, "one"], [true, "boolean"]]
- **Output:** Map operations results
- **Answer:** {size: 3, getName: "John", has1: false (after delete)}

**140. Map with Object Keys**
- **Question:** Use objects as Map keys
- **Explanation:** Demonstrate Map's ability to use non-string keys
- **Input:** obj1 = {id: 1}, obj2 = {id: 2}, values = ["first", "second"]
- **Output:** Map with object keys
- **Answer:** Map{ {id:1} => "first", {id:2} => "second" }

**141. WeakMap Usage**
- **Question:** Create WeakMap for private data storage
- **Explanation:** Use WeakMap for object-associated metadata
- **Input:** objects = [{name: "Alice"}, {name: "Bob"}], metadata = ["admin", "user"]
- **Output:** WeakMap with object keys
- **Answer:** WeakMap{ obj1 => "admin", obj2 => "user" }

**142. WeakSet Usage**
- **Question:** Track object instances in WeakSet
- **Explanation:** Use WeakSet for object membership without preventing GC
- **Input:** objects = [{id: 1}, {id: 2}]
- **Output:** WeakSet containing objects
- **Answer:** WeakSet{ {id:1}, {id:2} }

### JSON Operations

**143. JSON Stringify**
- **Question:** Convert object to JSON string with formatting
- **Explanation:** Use JSON.stringify with replacer and space parameters
- **Input:** obj = {name: "John", age: 30, city: "NYC"}, space = 2
- **Output:** Formatted JSON string
- **Answer:** "{\n  \"name\": \"John\",\n  \"age\": 30,\n  \"city\": \"NYC\"\n}"

**144. JSON Parse**
- **Question:** Parse JSON string to object
- **Explanation:** Use JSON.parse to convert JSON to JavaScript object
- **Input:** jsonStr = '{"name":"Alice","scores":[85,92,78]}'
- **Output:** Parsed JavaScript object
- **Answer:** {name: "Alice", scores: [85, 92, 78]}

**145. JSON Stringify with Replacer**
- **Question:** Stringify object excluding certain properties
- **Explanation:** Use replacer function to filter properties
- **Input:** obj = {name: "Bob", password: "secret", email: "bob@email.com"}
- **Output:** JSON string without password
- **Answer:** '{"name":"Bob","email":"bob@email.com"}'

**146. JSON Parse with Reviver**
- **Question:** Parse JSON with date string conversion
- **Explanation:** Use reviver function to transform values during parsing
- **Input:** jsonStr = '{"name":"Charlie","birthDate":"2023-01-15T00:00:00.000Z"}'
- **Output:** Object with Date object instead of string
- **Answer:** {name: "Charlie", birthDate: Date object}

**147. JSON Deep Copy**
- **Question:** Create deep copy of object using JSON methods
- **Explanation:** Use JSON.parse(JSON.stringify()) for deep copying
- **Input:** obj = {user: {name: "Dave", preferences: {theme: "dark"}}}
- **Output:** Deep copied object
- **Answer:** {user: {name: "Dave", preferences: {theme: "dark"}}} (independent copy)

### Date and Time

**148. Date Creation**
- **Question:** Create Date objects using different constructors
- **Explanation:** Demonstrate various ways to create Date instances
- **Input:** dateStr = "2023-12-25", timestamp = 1703462400000
- **Output:** Date objects from different inputs
- **Answer:** {fromString: Date, fromTimestamp: Date, current: Date}

**149. Date Formatting**
- **Question:** Format date in different locale-specific formats
- **Explanation:** Use toLocaleDateString and toLocaleTimeString
- **Input:** date = new Date("2023-12-25T15:30:00")
- **Output:** Formatted date strings
- **Answer:** {date: "12/25/2023", time: "3:30:00 PM", full: "Monday, December 25, 2023"}

**150. Date Arithmetic**
- **Question:** Calculate difference between two dates in days
- **Explanation:** Use date subtraction and time calculations
- **Input:** startDate = "2023-12-01", endDate = "2023-12-25"
- **Output:** Number of days between dates
- **Answer:** 24

---

## Advanced Level (Questions 151-225)

### Prototypes and Inheritance

**151. Prototype Chain**
- **Question:** Create object with custom prototype chain
- **Explanation:** Demonstrate prototype-based inheritance
- **Input:** parentObj = {greet: function() { return "Hello"; }}
- **Output:** Child object with inherited method
- **Answer:** Child object can call greet() method from prototype

**152. Constructor Function**
- **Question:** Create constructor function with prototype methods
- **Explanation:** Use function constructor pattern for object creation
- **Input:** name = "Car", properties = ["make", "model", "year"]
- **Output:** Constructor function with prototype methods
- **Answer:** Car constructor with drive() method on prototype

**153. Class Declaration**
- **Question:** Create ES6 class with constructor and methods
- **Explanation:** Use modern class syntax for object-oriented programming
- **Input:** className = "Person", properties = ["name", "age"]
- **Output:** Class with constructor and methods
- **Answer:** Person class with constructor and speak() method

**154. Class Inheritance**
- **Question:** Create subclass that extends parent class
- **Explanation:** Use extends keyword and super() for inheritance
- **Input:** ParentClass = Vehicle, ChildClass = Car
- **Output:** Car class extending Vehicle with additional properties
- **Answer:** Car extends Vehicle with honk() method

**155. Static Methods**
- **Question:** Add static methods to class
- **Explanation:** Create methods that belong to class, not instances
- **Input:** MathUtils class with static calculation methods
- **Output:** Class with static methods callable without instantiation
- **Answer:** MathUtils.add(), MathUtils.multiply() work without new MathUtils()

**156. Private Fields**
- **Question:** Create class with private fields using # syntax
- **Explanation:** Implement true private fields in ES2022
- **Input:** BankAccount class with private balance
- **Output:** Class with inaccessible private fields
- **Answer:** BankAccount with #balance field, accessible only through methods

**157. Getters and Setters**
- **Question:** Implement property getters and setters in class
- **Explanation:** Control property access with getter/setter methods
- **Input:** Temperature class with Celsius/Fahrenheit conversion
- **Output:** Class with computed properties
- **Answer:** temp.celsius = 25 sets temp.fahrenheit to 77

**158. Method Override**
- **Question:** Override parent method in child class
- **Explanation:** Demonstrate method overriding in inheritance
- **Input:** Animal class with speak(), Dog class overrides
- **Output:** Child method replaces parent method
- **Answer:** dog.speak() returns "Woof!" instead of generic animal sound

**159. Mixin Pattern**
- **Question:** Implement mixin for multiple inheritance simulation
- **Explanation:** Create reusable behavior objects for composition
- **Input:** Flyable mixin, Bird class
- **Output:** Object combining multiple behaviors
- **Answer:** Bird with fly() method from Flyable mixin

**160. Symbol Properties**
- **Question:** Use Symbol as object property key
- **Explanation:** Create unique property keys using Symbol
- **Input:** obj = {}, symbol = Symbol("unique")
- **Output:** Object with Symbol property
- **Answer:** obj[symbol] = "value" creates non-enumerable property

### Asynchronous Programming

**161. Promise Creation**
- **Question:** Create Promise that resolves after random delay
- **Explanation:** Use Promise constructor with executor function
- **Input:** minDelay = 1000, maxDelay = 3000
- **Output:** Promise resolving with delay time
- **Answer:** Promise resolves with actual delay value

**162. Promise Chain**
- **Question:** Chain multiple Promise operations
- **Explanation:** Use .then() for sequential asynchronous operations
- **Input:** initialValue = 5
- **Output:** Final result after chain of operations
- **Answer:** 5 → 10 → 20 → 22 (add 5, multiply 2, add 2)

**163. Promise All**
- **Question:** Wait for multiple Promises to resolve
- **Explanation:** Use Promise.all() for concurrent operations
- **Input:** promises = [fetch1, fetch2, fetch3]
- **Output:** Array of all resolved values
- **Answer:** [result1, result2, result3] when all complete

**164. Promise Race**
- **Question:** Get result from fastest Promise
- **Explanation:** Use Promise.race() for first completion
- **Input:** promises with different delays
- **Output:** Result from fastest Promise
- **Answer:** Result from Promise with shortest delay

**165. Promise AllSettled**
- **Question:** Wait for all Promises regardless of outcome
- **Explanation:** Use Promise.allSettled() for complete results
- **Input:** mix of resolving and rejecting Promises
- **Output:** Array of all settlement results
- **Answer:** [{status: "fulfilled", value: 1}, {status: "rejected", reason: Error}]

**166. Async/Await Basic**
- **Question:** Convert Promise chain to async/await
- **Explanation:** Use async function with await for cleaner syntax
- **Input:** Promise-based API calls
- **Output:** Same result with async/await syntax
- **Answer:** Sequential execution with cleaner code

**167. Async Error Handling**
- **Question:** Handle errors in async functions
- **Explanation:** Use try/catch with async/await
- **Input:** async operation that may fail
- **Output:** Handled error or success result
- **Answer:** "Error handled" or success value

**168. Concurrent Async Operations**
- **Question:** Run multiple async operations concurrently
- **Explanation:** Use Promise.all with async/await
- **Input:** multiple independent async operations
- **Output:** All results when complete
- **Answer:** [result1, result2, result3] from concurrent execution

**169. Async Iterator**
- **Question:** Create async iterator using async generator
- **Explanation:** Use async function* with yield
- **Input:** array of values with delays
- **Output:** Async iterator yielding values over time
- **Answer:** Iterator yields values with 500ms delays

**170. For Await Of**
- **Question:** Iterate over async iterator
- **Explanation:** Use for await...of loop for async iteration
- **Input:** async iterator of values
- **Output:** Values processed sequentially
- **Answer:** Each value processed in order with delays

### Advanced Functions

**171. Currying**
- **Question:** Create curried function for multiple arguments
- **Explanation:** Transform function with multiple parameters into series of functions
- **Input:** function add(a, b, c) { return a + b + c; }
- **Output:** Curried function add(a)(b)(c)
- **Answer:** curriedAdd(1)(2)(3) returns 6

**172. Partial Application**
- **Question:** Create partially applied function
- **Explanation:** Fix some arguments and return function for remaining
- **Input:** function multiply(a, b, c), fix first argument to 2
- **Output:** Function with first argument pre-filled
- **Answer:** multiplyBy2(3, 4) returns 24

**173. Function Composition**
- **Question:** Compose multiple functions into single function
- **Explanation:** Create function that applies functions in sequence
- **Input:** functions = [add5, multiply2, subtract1]
- **Output:** Composed function
- **Answer:** compose(add5, multiply2, subtract1)(10) = 29

**174. Memoization**
- **Question:** Implement memoization for expensive function
- **Explanation:** Cache function results to avoid recalculation
- **Input:** fibonacci function
- **Output:** Memoized version with cache
- **Answer:** memoizedFib(40) calculated once, cached for subsequent calls

**175. Throttling**
- **Question:** Create throttled function that limits execution frequency
- **Explanation:** Ensure function executes at most once per time period
- **Input:** function to throttle, limit = 1000ms
- **Output:** Throttled function
- **Answer:** Function executes maximum once per second regardless of calls

**176. Debouncing**
- **Question:** Create debounced function that delays execution
- **Explanation:** Delay execution until after calls have stopped
- **Input:** function to debounce, delay = 500ms
- **Output:** Debounced function
- **Answer:** Function executes 500ms after last call

**177. Function Pipeline**
- **Question:** Create pipeline for data transformation
- **Explanation:** Chain functions where output of one becomes input of next
- **Input:** data = "hello", functions = [capitalize, addExclamation, repeat(2)]
- **Output:** Final transformed result
- **Answer:** "HELLO!HELLO!"

**178. Higher-Order Function**
- **Question:** Create function that takes functions as arguments
- **Explanation:** Implement function that operates on other functions
- **Input:** array of numbers, transformation functions
- **Output:** Result of applying functions to array
- **Answer:** applyOperations([1,2,3], [double, addOne]) returns [3,5,7]

**179. Function Factory**
- **Question:** Create factory function that generates specialized functions
- **Explanation:** Return customized functions based on parameters
- **Input:** operation type, configuration
- **Output:** Specialized function
- **Answer:** createValidator("email") returns email validation function

**180. Recursive Function with Memoization**
- **Question:** Implement recursive function with built-in memoization
- **Explanation:** Combine recursion with caching for efficiency
- **Input:** problem requiring recursive solution
- **Output:** Optimized recursive function
- **Answer:** Tree traversal with cached results

### Advanced Array Operations

**181. Array Chunk**
- **Question:** Split array into chunks of specified size
- **Explanation:** Create subarrays of fixed length from original array
- **Input:** arr = [1,2,3,4,5,6,7,8], chunkSize = 3
- **Output:** Array of chunks
- **Answer:** [[1,2,3], [4,5,6], [7,8]]

**182. Array Flatten Deep**
- **Question:** Flatten nested array to any depth
- **Explanation:** Recursively flatten arrays regardless of nesting level
- **Input:** arr = [1, [2, [3, [4, 5]]]]
- **Output:** Completely flattened array
- **Answer:** [1, 2, 3, 4, 5]

**183. Array Intersection**
- **Question:** Find common elements between multiple arrays
- **Explanation:** Return elements present in all input arrays
- **Input:** arrays = [[1,2,3], [2,3,4], [2,3,5]]
- **Output:** Array of common elements
- **Answer:** [2, 3]

**184. Array Difference**
- **Question:** Find elements in first array not in others
- **Explanation:** Return elements unique to first array
- **Input:** arr1 = [1,2,3,4], arr2 = [2,4], arr3 = [3]
- **Output:** Array of unique elements
- **Answer:** [1]

**185. Array Unique**
- **Question:** Remove duplicate elements from array
- **Explanation:** Create array with only unique values
- **Input:** arr = [1,2,2,3,3,3,4]
- **Output:** Array with unique elements
- **Answer:** [1, 2, 3, 4]

**186. Array Group By**
- **Question:** Group array elements by specified criteria
- **Explanation:** Create object with grouped arrays based on key function
- **Input:** users = [{name:"John",role:"admin"}, {name:"Jane",role:"user"}]
- **Output:** Object with grouped arrays
- **Answer:** {admin: [{name:"John",role:"admin"}], user: [{name:"Jane",role:"user"}]}

**187. Array Partition**
- **Question:** Split array into two groups based on predicate
- **Explanation:** Separate array into elements that pass/fail condition
- **Input:** arr = [1,2,3,4,5,6], predicate = isEven
- **Output:** Array with two subarrays
- **Answer:** [[2,4,6], [1,3,5]]

**188. Array Zip**
- **Question:** Combine multiple arrays element-wise
- **Explanation:** Create array of tuples from corresponding elements
- **Input:** arr1 = [1,2,3], arr2 = ["a","b","c"], arr3 = [true,false,true]
- **Output:** Array of combined elements
- **Answer:** [[1,"a",true], [2,"b",false], [3,"c",true]]

**189. Array Transpose**
- **Question:** Transpose 2D array (swap rows and columns)
- **Explanation:** Convert rows to columns and vice versa
- **Input:** matrix = [[1,2,3], [4,5,6]]
- **Output:** Transposed matrix
- **Answer:** [[1,4], [2,5], [3,6]]

**190. Array Permutations**
- **Question:** Generate all permutations of array elements
- **Explanation:** Create array containing all possible arrangements
- **Input:** arr = [1, 2, 3]
- **Output:** Array of all permutations
- **Answer:** [[1,2,3], [1,3,2], [2,1,3], [2,3,1], [3,1,2], [3,2,1]]

### Advanced String Operations

**191. String Anagram Check**
- **Question:** Check if two strings are anagrams
- **Explanation:** Determine if strings contain same characters in different order
- **Input:** str1 = "listen", str2 = "silent"
- **Output:** Boolean result
- **Answer:** true

**192. String Palindrome Check**
- **Question:** Check if string is palindrome (ignoring case and spaces)
- **Explanation:** Verify if string reads same forwards and backwards
- **Input:** str = "A man a plan a canal Panama"
- **Output:** Boolean result
- **Answer:** true

**193. String Longest Common Subsequence**
- **Question:** Find longest common subsequence between two strings
- **Explanation:** Find longest sequence that appears in both strings in order
- **Input:** str1 = "ABCDGH", str2 = "AEDFHR"
- **Output:** Length of LCS
- **Answer:** 3 ("ADH")

**194. String Edit Distance**
- **Question:** Calculate minimum edit distance between two strings
- **Explanation:** Find minimum operations to transform one string to another
- **Input:** str1 = "kitten", str2 = "sitting"
- **Output:** Minimum edit distance
- **Answer:** 3

**195. String Compression**
- **Question:** Compress string using run-length encoding
- **Explanation:** Replace repeated characters with character and count
- **Input:** str = "aaabbbcccaaa"
- **Output:** Compressed string
- **Answer:** "a3b3c3a3"

**196. String Decompression**
- **Question:** Decompress run-length encoded string
- **Explanation:** Expand compressed string to original form
- **Input:** compressed = "a3b2c4"
- **Output:** Decompressed string
- **Answer:** "aaabbcccc"

**197. String Word Frequency**
- **Question:** Count frequency of words in text
- **Explanation:** Create object mapping words to their occurrence count
- **Input:** text = "hello world hello javascript world"
- **Output:** Word frequency object
- **Answer:** {hello: 2, world: 2, javascript: 1}

**198. String Camel Case Conversion**
- **Question:** Convert string to camelCase
- **Explanation:** Transform string to camelCase naming convention
- **Input:** str = "hello-world-example"
- **Output:** CamelCase string
- **Answer:** "helloWorldExample"

**199. String Snake Case Conversion**
- **Question:** Convert camelCase to snake_case
- **Explanation:** Transform camelCase to snake_case naming convention
- **Input:** str = "helloWorldExample"
- **Output:** Snake_case string
- **Answer:** "hello_world_example"

**200. String Levenshtein Distance**
- **Question:** Calculate Levenshtein distance between strings
- **Explanation:** Minimum single-character edits to change one word into another
- **Input:** str1 = "saturday", str2 = "sunday"
- **Output:** Levenshtein distance
- **Answer:** 3

### Complex Data Manipulation

**201. Deep Object Merge**
- **Question:** Recursively merge nested objects
- **Explanation:** Combine objects at all nesting levels
- **Input:** obj1 = {a: {b: 1}}, obj2 = {a: {c: 2}, d: 3}
- **Output:** Deeply merged object
- **Answer:** {a: {b: 1, c: 2}, d: 3}

**202. Object Deep Clone**
- **Question:** Create deep copy of complex nested object
- **Explanation:** Clone object with all nested references
- **Input:** obj = {user: {profile: {settings: {theme: "dark"}}}}
- **Output:** Independent deep copy
- **Answer:** Completely separate object with same structure

**203. Object Path Access**
- **Question:** Access nested object property using dot notation string
- **Explanation:** Get value from object using path like "user.profile.name"
- **Input:** obj = {user: {profile: {name: "John"}}}, path = "user.profile.name"
- **Output:** Value at specified path
- **Answer:** "John"

**204. Object Path Set**
- **Question:** Set nested object property using dot notation string
- **Explanation:** Set value in nested object using path like "user.profile.name"
- **Input:** obj = {user: {profile: {}}}, path = "user.profile.name", value = "Alice"
- **Output:** Object with value set at path
- **Answer:** {user: {profile: {name: "Alice"}}}

**205. Object Flatten**
- **Question:** Flatten nested object into single-level object with dot notation keys
- **Explanation:** Convert nested structure to flat object with compound keys
- **Input:** obj = {user: {profile: {name: "John", age: 30}}}
- **Output:** Flattened object
- **Answer:** {"user.profile.name": "John", "user.profile.age": 30}

**206. Object Unflatten**
- **Question:** Convert flattened object back to nested structure
- **Explanation:** Rebuild nested object from dot notation keys
- **Input:** flat = {"user.profile.name": "John", "user.settings.theme": "dark"}
- **Output:** Nested object structure
- **Answer:** {user: {profile: {name: "John"}, settings: {theme: "dark"}}}

**207. Array to Tree**
- **Question:** Convert flat array to tree structure
- **Explanation:** Build hierarchical tree from array with parent-child relationships
- **Input:** data = [{id:1,parent:null,name:"Root"}, {id:2,parent:1,name:"Child1"}]
- **Output:** Tree structure
- **Answer:** {id:1,name:"Root",children:[{id:2,name:"Child1",children:[]}]}

**208. Tree to Array**
- **Question:** Flatten tree structure to array
- **Explanation:** Convert hierarchical tree to flat array representation
- **Input:** tree = {id:1,name:"Root",children:[{id:2,name:"Child1",children:[]}]}
- **Output:** Flat array
- **Answer:** [{id:1,parent:null,name:"Root"}, {id:2,parent:1,name:"Child1"}]

**209. Data Aggregation**
- **Question:** Aggregate data by multiple criteria
- **Explanation:** Group and calculate statistics for complex data sets
- **Input:** sales = [{product:"A",region:"US",amount:100}, {product:"A",region:"EU",amount:150}]
- **Output:** Aggregated results
- **Answer:** {US: {A: {count: 1, total: 100}}, EU: {A: {count: 1, total: 150}}}

**210. Data Pivot**
- **Question:** Pivot data table structure
- **Explanation:** Transform rows to columns based on specified criteria
- **Input:** data = [{name:"John",subject:"Math",score:85}, {name:"John",subject:"Science",score:92}]
- **Output:** Pivoted structure
- **Answer:** {John: {Math: 85, Science: 92}}

**211. Data Normalization**
- **Question:** Normalize nested data structure
- **Explanation:** Convert nested data to normalized form with separate entities
- **Input:** posts = [{id:1,author:{id:1,name:"John"},comments:[{id:1,text:"Great!"}]}]
- **Output:** Normalized entities
- **Answer:** {posts: {1: {id:1,authorId:1}}, authors: {1: {id:1,name:"John"}}, comments: {1: {id:1,text:"Great!"}}}

**212. Data Denormalization**
- **Question:** Denormalize separated entities back to nested structure
- **Explanation:** Combine normalized entities into nested data structure
- **Input:** Separate entities for posts, authors, comments
- **Output:** Nested data structure
- **Answer:** [{id:1,author:{id:1,name:"John"},comments:[{id:1,text:"Great!"}]}]

**213. Schema Validation**
- **Question:** Validate object against schema definition
- **Explanation:** Check if object matches expected structure and types
- **Input:** obj = {name:"John",age:25}, schema = {name:"string",age:"number"}
- **Output:** Validation result
- **Answer:** {valid: true, errors: []}

**214. Dynamic Property Access**
- **Question:** Access object properties using computed property names
- **Explanation:** Use bracket notation with dynamic keys from array
- **Input:** obj = {firstName:"John",lastName:"Doe"}, keys = ["firstName","lastName"]
- **Output:** Array of property values
- **Answer:** ["John", "Doe"]

**215. Object Serialization**
- **Question:** Serialize object to custom string format
- **Explanation:** Convert object to custom string representation for storage/transmission
- **Input:** obj = {name:"Alice",age:30,active:true}
- **Output:** Custom serialized string
- **Answer:** "name:Alice;age:30;active:true"

**216. Object Deserialization**
- **Question:** Parse custom string format back to object
- **Explanation:** Convert custom serialized string back to JavaScript object
- **Input:** serialized = "name:Bob;age:25;active:false"
- **Output:** Parsed object
- **Answer:** {name:"Bob",age:25,active:false}

**217. Circular Reference Handling**
- **Question:** Handle circular references in object serialization
- **Explanation:** Serialize object with circular references without infinite loops
- **Input:** obj = {name:"parent"}; obj.child = {parent: obj}
- **Output:** Serialized object with reference markers
- **Answer:** {name:"parent",child:{parent:"[Circular]"}}

**218. Memory Optimization**
- **Question:** Optimize object for memory usage
- **Explanation:** Reduce object memory footprint through various techniques
- **Input:** Large object with redundant data
- **Output:** Memory-optimized version
- **Answer:** Object with shared references and reduced redundancy

**219. Immutable Update**
- **Question:** Update nested object immutably
- **Explanation:** Create new object with changes without mutating original
- **Input:** state = {user:{profile:{name:"John"}}}, update = {user:{profile:{age:25}}}
- **Output:** New object with merged changes
- **Answer:** {user:{profile:{name:"John",age:25}}} (original unchanged)

**220. State Management**
- **Question:** Implement simple state management system
- **Explanation:** Create system for managing application state with subscriptions
- **Input:** initialState = {count:0}, actions = {increment, decrement}
- **Output:** State manager with subscribe/dispatch methods
- **Answer:** StateManager with getState(), dispatch(), subscribe() methods

### Performance and Optimization

**221. Algorithm Complexity Analysis**
- **Question:** Analyze time complexity of nested loop algorithm
- **Explanation:** Determine Big O notation for algorithm performance
- **Input:** Algorithm with nested iterations over arrays
- **Output:** Time and space complexity
- **Answer:** O(n²) time complexity, O(1) space complexity

**222. Memory Leak Detection**
- **Question:** Identify and fix memory leak in closure
- **Explanation:** Find variables that prevent garbage collection
- **Input:** Function creating closure with unnecessary references
- **Output:** Fixed version without memory leaks
- **Answer:** Closure with proper cleanup and null assignments

**223. Performance Benchmarking**
- **Question:** Compare performance of different array iteration methods
- **Explanation:** Measure execution time of for, forEach, map, etc.
- **Input:** Large array and different iteration approaches
- **Output:** Performance comparison results
- **Answer:** {forLoop: 1.2ms, forEach: 2.1ms, map: 2.8ms}

**224. Lazy Evaluation**
- **Question:** Implement lazy evaluation for expensive computations
- **Explanation:** Defer computation until value is actually needed
- **Input:** Function that performs expensive calculation
- **Output:** Lazy wrapper that computes on demand
- **Answer:** Lazy object that computes value only when accessed

**225. Virtual DOM Simulation**
- **Question:** Implement basic virtual DOM diffing algorithm
- **Explanation:** Compare two virtual DOM trees and generate update operations
- **Input:** oldVTree = {tag:"div",children:[{tag:"p",text:"old"}]}
- **Output:** Diff operations array
- **Answer:** [{type:"update",path:[0],newValue:{tag:"p",text:"new"}}]

---

## Expert Level (Questions 226-300+)

### Advanced Language Features

**226. Proxy Object**
- **Question:** Create Proxy that logs all property access and modifications
- **Explanation:** Use Proxy for meta-programming and property interception
- **Input:** target = {name:"John",age:25}
- **Output:** Proxy with logging behavior
- **Answer:** Proxy that console.logs "GET name: John" and "SET age: 26"

**227. Reflect API**
- **Question:** Use Reflect API for dynamic property manipulation
- **Explanation:** Perform object operations using Reflect methods
- **Input:** obj = {}, propName = "dynamicProp", value = "test"
- **Output:** Object modified using Reflect
- **Answer:** Reflect.set(obj, propName, value) returns true

**228. Symbol Iterator**
- **Question:** Create custom iterator using Symbol.iterator
- **Explanation:** Make object iterable with custom iteration behavior
- **Input:** range = {start: 1, end: 5}
- **Output:** Iterable object
- **Answer:** for...of range yields 1, 2, 3, 4, 5

**229. Symbol AsyncIterator**
- **Question:** Implement async iterator with Symbol.asyncIterator
- **Explanation:** Create asynchronous iteration with delays
- **Input:** asyncRange = {start: 1, end: 3, delay: 1000}
- **Output:** Async iterable object
- **Answer:** for await...of yields values with 1s delays

**230. WeakRef and Finalizers**
- **Question:** Use WeakRef and FinalizationRegistry for memory management
- **Explanation:** Create weak references and cleanup callbacks
- **Input:** Large objects that should be garbage collected
- **Output:** WeakRef system with cleanup notifications
- **Answer:** Objects can be GC'd, cleanup callbacks executed

**231. Intl API Usage**
- **Question:** Format numbers, dates, and text using Intl API
- **Explanation:** Use Internationalization API for locale-specific formatting
- **Input:** number = 1234567.89, locale = "de-DE"
- **Output:** Formatted values for different locales
- **Answer:** "1.234.567,89" (German number format)

**232. Temporal API (Future)**
- **Question:** Work with proposed Temporal API for date/time
- **Explanation:** Use modern date/time API replacing Date object
- **Input:** dateStr = "2023-12-25T15:30:00"
- **Output:** Temporal objects with precise time handling
- **Answer:** Temporal.PlainDateTime with accurate arithmetic

**233. Optional Chaining Advanced**
- **Question:** Use optional chaining with dynamic property access
- **Explanation:** Safely access nested properties with computed keys
- **Input:** obj = {users: {123: {profile: {name: "John"}}}}, id = "123"
- **Output:** Safely accessed nested value
- **Answer:** obj.users?.[id]?.profile?.name returns "John"

**234. Nullish Coalescing Complex**
- **Question:** Use nullish coalescing in complex expressions
- **Explanation:** Handle null/undefined with ?? operator in chains
- **Input:** config = {api: {timeout: null}}, defaults = {timeout: 5000}
- **Output:** Resolved configuration with fallbacks
- **Answer:** config.api.timeout ?? defaults.timeout returns 5000

**235. BigInt Operations**
- **Question:** Perform arithmetic with very large integers using BigInt
- **Explanation:** Handle integers larger than Number.MAX_SAFE_INTEGER
- **Input:** a = 9007199254740991n, b = 2n
- **Output:** BigInt arithmetic results
- **Answer:** a + b = 9007199254740993n

### Advanced Asynchronous Patterns

**236. Promise Cancellation**
- **Question:** Implement cancellable Promise pattern
- **Explanation:** Create Promise that can be cancelled before completion
- **Input:** long-running async operation
- **Output:** Cancellable Promise with cancel method
- **Answer:** Promise with cancel() method that rejects with CancelError

**237. Async Pool/Queue**
- **Question:** Implement async operation pool with concurrency limit
- **Explanation:** Limit number of concurrent async operations
- **Input:** tasks = [fetch1, fetch2, fetch3, fetch4], concurrency = 2
- **Output:** Results with controlled concurrency
- **Answer:** Maximum 2 operations running simultaneously

**238. Retry with Exponential Backoff**
- **Question:** Implement retry mechanism with exponential backoff
- **Explanation:** Retry failed operations with increasing delays
- **Input:** failingOperation, maxRetries = 3, baseDelay = 1000
- **Output:** Eventually successful result or final failure
- **Answer:** Retries at 1s, 2s, 4s intervals

**239. Circuit Breaker Pattern**
- **Question:** Implement circuit breaker for fault tolerance
- **Explanation:** Prevent cascading failures by temporarily stopping calls
- **Input:** unreliable service, failure threshold = 5
- **Output:** Circuit breaker that opens after failures
- **Answer:** Service calls blocked when circuit is open

**240. Async Mutex/Semaphore**
- **Question:** Implement mutex for async operation synchronization
- **Explanation:** Ensure only one async operation accesses resource
- **Input:** shared resource, multiple competing async operations
- **Output:** Synchronized access to shared resource
- **Answer:** Operations wait for mutex release before proceeding

**241. Stream Processing**
- **Question:** Implement async stream processing with backpressure
- **Explanation:** Process data stream with flow control
- **Input:** data stream, processing function, buffer size
- **Output:** Processed stream with backpressure handling
- **Answer:** Stream processes data without overwhelming consumer

**242. Event Sourcing Pattern**
- **Question:** Implement event sourcing with async event handlers
- **Explanation:** Store events and rebuild state from event history
- **Input:** events = [{type:"userCreated",data:{name:"John"}}]
- **Output:** Current state rebuilt from events
- **Answer:** {users: {1: {name: "John"}}}

**243. CQRS Implementation**
- **Question:** Implement Command Query Responsibility Segregation
- **Explanation:** Separate read and write operations with different models
- **Input:** commands and queries for user management
- **Output:** Separate command and query handlers
- **Answer:** WriteModel.createUser(), ReadModel.getUserById()

**244. Saga Pattern**
- **Question:** Implement distributed transaction saga
- **Explanation:** Coordinate multiple services with compensating actions
- **Input:** multi-step business process across services
- **Output:** Saga with compensation logic
- **Answer:** Process with rollback capabilities for failures

**245. Event-Driven Architecture**
- **Question:** Create event-driven system with async event bus
- **Explanation:** Decouple components using event publishing/subscription
- **Input:** multiple components needing to communicate
- **Output:** Event bus with publishers and subscribers
- **Answer:** Components communicate through events, not direct calls

### Metaprogramming and Code Generation

**246. Dynamic Function Creation**
- **Question:** Generate functions dynamically based on configuration
- **Explanation:** Create functions programmatically from metadata
- **Input:** config = {name:"validate",params:["email"],body:"return /\\S+@\\S+/.test(email)"}
- **Output:** Dynamically created function
- **Answer:** function validate(email) { return /\\S+@\\S+/.test(email) }

**247. AST Manipulation**
- **Question:** Parse and modify JavaScript code using AST
- **Explanation:** Transform code by manipulating Abstract Syntax Tree
- **Input:** code = "function add(a, b) { return a + b; }"
- **Output:** Modified code with added logging
- **Answer:** function add(a, b) { console.log("add called"); return a + b; }

**248. Custom DSL Implementation**
- **Question:** Create Domain Specific Language for configuration
- **Explanation:** Build mini-language for specific problem domain
- **Input:** DSL rules for form validation
- **Output:** Validator functions generated from DSL
- **Answer:** "required|email|min:8" generates validation chain

**249. Template Engine**
- **Question:** Build template engine with expressions and loops
- **Explanation:** Parse templates and generate output with data
- **Input:** template = "Hello {{name}}! {{#each items}}{{this}}{{/each}}"
- **Output:** Rendered template with data substitution
- **Answer:** "Hello John! Item1Item2Item3"

**250. Code Transformation Pipeline**
- **Question:** Create pipeline for code transformations
- **Explanation:** Chain multiple code transformation steps
- **Input:** source code, transformation rules
- **Output:** Transformed code through pipeline stages
- **Answer:** Code passes through minify → obfuscate → optimize stages

**251. Decorator Pattern Implementation**
- **Question:** Implement decorator pattern for method enhancement
- **Explanation:** Add functionality to methods without modifying them
- **Input:** class with methods, decorators for logging/timing
- **Output:** Enhanced methods with decorator functionality
- **Answer:** Methods automatically log execution and measure timing

**252. Plugin Architecture**
- **Question:** Design extensible plugin system
- **Explanation:** Create system that allows runtime plugin loading
- **Input:** core application, plugin definitions
- **Output:** Application extended with plugin functionality
- **Answer:** Core app + plugins = enhanced functionality

**253. Macro System**
- **Question:** Implement macro expansion system
- **Explanation:** Create system for code generation using macros
- **Input:** macro definitions and usage sites
- **Output:** Expanded code with macros replaced
- **Answer:** Macro calls replaced with generated code

**254. Live Code Reloading**
- **Question:** Implement hot module replacement system
- **Explanation:** Update running code without full restart
- **Input:** modified modules, dependency graph
- **Output:** System with updated modules
- **Answer:** Code changes reflected immediately in running system

**255. JIT Compilation Simulation**
- **Question:** Simulate Just-In-Time compilation optimization
- **Explanation:** Optimize frequently executed code paths
- **Input:** function call statistics, optimization strategies
- **Output:** Optimized function versions for hot paths
- **Answer:** Frequently called functions replaced with optimized versions

### Advanced Data Structures & Algorithms

**256. Red-Black Tree**
- **Question:** Implement self-balancing Red-Black tree
- **Explanation:** Create balanced binary search tree with color properties
- **Input:** sequence of insertions and deletions
- **Output:** Balanced tree maintaining red-black properties
- **Answer:** Tree with O(log n) operations and balanced structure

**257. B-Tree Implementation**
- **Question:** Implement B-tree for large datasets
- **Explanation:** Create tree structure optimized for disk-based storage
- **Input:** large dataset, B-tree order = 5
- **Output:** B-tree with efficient range queries
- **Answer:** Tree with multiple keys per node, optimized for I/O

**258. Bloom Filter**
- **Question:** Implement space-efficient probabilistic data structure
- **Explanation:** Create filter for membership testing with false positives
- **Input:** hash functions, bit array size, elements to add
- **Output:** Bloom filter with membership testing
- **Answer:** Filter returns "possibly in set" or "definitely not in set"

**259. Skip List**
- **Question:** Implement probabilistic alternative to balanced trees
- **Explanation:** Create multi-level linked list for fast search
- **Input:** elements to insert, probability = 0.5
- **Output:** Skip list with O(log n) operations
- **Answer:** Multi-level structure with logarithmic search time

**260. Trie (Prefix Tree)**
- **Question:** Implement trie for string prefix matching
- **Explanation:** Create tree structure for efficient string operations
- **Input:** words = ["cat", "car", "card", "care", "careful"]
- **Output:** Trie supporting prefix search and autocomplete
- **Answer:** Tree allowing fast prefix matching and word suggestions

**261. Suffix Array**
- **Question:** Build suffix array for string pattern matching
- **Explanation:** Create array of string suffixes for efficient searching
- **Input:** text = "banana"
- **Output:** Sorted suffix array with LCP (Longest Common Prefix)
- **Answer:** Suffixes sorted lexicographically with search capabilities

**262. Segment Tree**
- **Question:** Implement segment tree for range queries
- **Explanation:** Create tree for efficient range sum/min/max queries
- **Input:** array = [1,3,5,7,9,11], query type = range sum
- **Output:** Segment tree supporting range operations
- **Answer:** Tree allowing O(log n) range queries and updates

**263. Fenwick Tree (Binary Indexed Tree)**
- **Question:** Implement Fenwick tree for prefix sum queries
- **Explanation:** Create space-efficient structure for cumulative operations
- **Input:** array of numbers, prefix sum queries
- **Output:** BIT supporting prefix sums and updates
- **Answer:** Tree with O(log n) prefix sum queries and updates

**264. Union-Find (Disjoint Set)**
- **Question:** Implement Union-Find with path compression
- **Explanation:** Create structure for connectivity queries
- **Input:** elements and union operations
- **Output:** Disjoint set with near-constant time operations
- **Answer:** Structure determining if elements are connected

**265. Graph Algorithms**
- **Question:** Implement Dijkstra's shortest path algorithm
- **Explanation:** Find shortest paths in weighted graph
- **Input:** graph = {A:{B:4,C:2}, B:{C:1,D:5}, C:{D:8,E:10}}
- **Output:** Shortest paths from source to all vertices
- **Answer:** {A:0, B:4, C:2, D:5, E:12} (distances from A)

### Memory Management & Performance

**266. Object Pool Pattern**
- **Question:** Implement object pool for memory optimization
- **Explanation:** Reuse objects to reduce garbage collection pressure
- **Input:** expensive objects that can be reused
- **Output:** Pool managing object lifecycle
- **Answer:** Pool provides acquire()/release() methods for object reuse

**267. Lazy Loading Implementation**
- **Question:** Implement lazy loading with cache invalidation
- **Explanation:** Load resources on demand with smart caching
- **Input:** resource identifiers and loading functions
- **Output:** Lazy loader with cache management
- **Answer:** Resources loaded only when accessed, cached for reuse

**268. Memory Profiling**
- **Question:** Create memory usage profiler for objects
- **Explanation:** Track memory consumption and detect leaks
- **Input:** objects to monitor, profiling duration
- **Output:** Memory usage report and leak detection
- **Answer:** Report showing memory growth patterns and potential leaks

**269. Garbage Collection Optimization**
- **Question:** Optimize code to reduce GC pressure
- **Explanation:** Restructure code to minimize object allocation
- **Input:** code with high allocation rate
- **Output:** Optimized version with reduced allocations
- **Answer:** Code reusing objects and avoiding temporary allocations

**270. Weak Reference Management**
- **Question:** Implement cache using WeakMap for automatic cleanup
- **Explanation:** Create cache that doesn't prevent garbage collection
- **Input:** objects to cache with associated data
- **Output:** WeakMap-based cache with automatic cleanup
- **Answer:** Cache entries cleaned up when objects are GC'd

### Concurrency & Parallelism

**271. Web Workers Communication**
- **Question:** Implement communication system between main thread and workers
- **Explanation:** Create message-based communication with workers
- **Input:** compute-intensive tasks, worker scripts
- **Output:** Results computed in parallel
- **Answer:** Tasks distributed to workers, results aggregated in main thread

**272. SharedArrayBuffer Usage**
- **Question:** Use SharedArrayBuffer for inter-worker communication
- **Explanation:** Share memory between workers for high-performance computing
- **Input:** array processing tasks requiring shared state
- **Output:** Coordinated processing using shared memory
- **Answer:** Workers accessing same memory region with atomic operations

**273. Atomic Operations**
- **Question:** Use Atomics API for thread-safe operations
- **Explanation:** Perform atomic operations on SharedArrayBuffer
- **Input:** shared buffer, multiple workers modifying data
- **Output:** Thread-safe operations without race conditions
- **Answer:** Atomic increments/decrements with proper synchronization

**274. Lock-Free Data Structures**
- **Question:** Implement lock-free queue for concurrent access
- **Explanation:** Create thread-safe queue without blocking operations
- **Input:** multiple producers and consumers
- **Output:** Queue supporting concurrent enqueue/dequeue
- **Answer:** CAS-based queue with non-blocking operations

**275. Actor Model Implementation**
- **Question:** Implement actor model for concurrent computation
- **Explanation:** Create actors that communicate via message passing
- **Input:** actor definitions and message types
- **Output:** System of communicating actors
- **Answer:** Actors processing messages independently and asynchronously

### Advanced Testing & Quality

**276. Property-Based Testing**
- **Question:** Implement property-based test generator
- **Explanation:** Generate test cases automatically based on properties
- **Input:** function properties, input generators
- **Output:** Comprehensive test suite with generated cases
- **Answer:** Tests automatically generated covering edge cases

**277. Mutation Testing**
- **Question:** Implement mutation testing for test quality assessment
- **Explanation:** Mutate code to test if tests catch the changes
- **Input:** source code, test suite
- **Output:** Mutation score showing test effectiveness
- **Answer:** Percentage of mutations caught by tests

**278. Fuzzing Implementation**
- **Question:** Create fuzzer for finding edge cases
- **Explanation:** Generate random inputs to find unexpected behavior
- **Input:** function to test, input constraints
- **Output:** Edge cases causing failures or unexpected behavior
- **Answer:** Inputs that reveal bugs or performance issues

**279. Code Coverage Analysis**
- **Question:** Implement code coverage tracking
- **Explanation:** Track which code paths are executed during testing
- **Input:** source code, test execution
- **Output:** Coverage report with metrics
- **Answer:** Line/branch/function coverage percentages

**280. Performance Regression Detection**
- **Question:** Detect performance regressions in code changes
- **Explanation:** Compare performance metrics across code versions
- **Input:** performance benchmarks, code changes
- **Output:** Regression analysis with performance deltas
- **Answer:** Report highlighting performance improvements/degradations

### Cryptography & Security

**281. Hash Function Implementation**
- **Question:** Implement secure hash function
- **Explanation:** Create cryptographic hash for data integrity
- **Input:** arbitrary data, hash algorithm specification
- **Output:** Fixed-size hash value
- **Answer:** Deterministic hash resistant to collisions

**282. Digital Signature Verification**
- **Question:** Implement digital signature verification system
- **Explanation:** Verify message authenticity using public key cryptography
- **Input:** message, signature, public key
- **Output:** Signature validity result
- **Answer:** Boolean indicating if signature is valid

**283. Merkle Tree Implementation**
- **Question:** Build Merkle tree for data verification
- **Explanation:** Create tree structure for efficient data integrity checking
- **Input:** data blocks to be hashed
- **Output:** Merkle tree with root hash and proofs
- **Answer:** Tree allowing verification of individual blocks

**284. JWT Token Implementation**
- **Question:** Implement JSON Web Token creation and verification
- **Explanation:** Create secure tokens for authentication
- **Input:** payload data, secret key
- **Output:** Signed JWT token
- **Answer:** Token with header, payload, and signature

**285. Encryption/Decryption System**
- **Question:** Implement symmetric encryption system
- **Explanation:** Encrypt and decrypt data using shared key
- **Input:** plaintext, encryption key
- **Output:** Encrypted ciphertext and decryption capability
- **Answer:** Securely encrypted data recoverable with key

### Distributed Systems Concepts

**286. Consistent Hashing**
- **Question:** Implement consistent hashing for distributed caching
- **Explanation:** Distribute keys across nodes with minimal reshuffling
- **Input:** keys, server nodes, hash function
- **Output:** Key distribution with node addition/removal handling
- **Answer:** Keys redistributed minimally when nodes change

**287. Vector Clocks**
- **Question:** Implement vector clocks for distributed event ordering
- **Explanation:** Track causal relationships in distributed systems
- **Input:** events from multiple nodes
- **Output:** Vector timestamps showing event causality
- **Answer:** Clocks showing happened-before relationships

**288. Gossip Protocol**
- **Question:** Implement gossip protocol for information dissemination
- **Explanation:** Spread information through network via random communication
- **Input:** network nodes, information to propagate
- **Output:** Eventually consistent information across all nodes
- **Answer:** Information spreads to all nodes with high probability

**289. Leader Election Algorithm**
- **Question:** Implement Raft leader election
- **Explanation:** Select leader in distributed system for consensus
- **Input:** network of nodes, election timeout
- **Output:** Single leader elected with follower consensus
- **Answer:** One node becomes leader, others become followers

**290. Distributed Consensus**
- **Question:** Implement Byzantine fault tolerance consensus
- **Explanation:** Achieve agreement despite malicious nodes
- **Input:** nodes with some potentially malicious behavior
- **Output:** Consensus value agreed upon by honest majority
- **Answer:** Agreement reached despite up to f malicious nodes

### Compiler & Language Implementation

**291. Lexical Analyzer**
- **Question:** Implement lexer for simple programming language
- **Explanation:** Break source code into tokens
- **Input:** source code string
- **Output:** Array of tokens with types and values
- **Answer:** [{type:"IDENTIFIER",value:"x"}, {type:"EQUALS",value:"="}, ...]

**292. Recursive Descent Parser**
- **Question:** Build parser for arithmetic expressions
- **Explanation:** Parse tokens into Abstract Syntax Tree
- **Input:** tokens from lexer
- **Output:** AST representing expression structure
- **Answer:** Tree with operators as internal nodes, operands as leaves

**293. Interpreter Implementation**
- **Question:** Create interpreter for simple language
- **Explanation:** Execute code by walking AST
- **Input:** AST from parser
- **Output:** Execution results
- **Answer:** Variables assigned, expressions evaluated, output produced

**294. Type Checker**
- **Question:** Implement static type checking
- **Explanation:** Verify type correctness before execution
- **Input:** AST with type annotations
- **Output:** Type errors or successful type checking
- **Answer:** List of type mismatches or confirmation of type safety

**295. Code Generator**
- **Question:** Generate target code from AST
- **Explanation:** Transform AST to executable code
- **Input:** type-checked AST
- **Output:** Generated code in target language
- **Answer:** Executable code equivalent to original program

### Cutting-Edge Features

**296. Module Federation**
- **Question:** Implement micro-frontend module sharing
- **Explanation:** Share modules between applications at runtime
- **Input:** multiple applications with shared dependencies
- **Output:** Applications sharing modules dynamically
- **Answer:** Apps loading and sharing modules from remote sources

**297. Streaming Data Processing**
- **Question:** Process continuous data streams with windowing
- **Explanation:** Handle infinite data streams with time-based windows
- **Input:** continuous event stream
- **Output:** Aggregated results over time windows
- **Answer:** Real-time analytics with sliding/tumbling windows

**298. Edge Computing Simulation**
- **Question:** Simulate edge computing with latency optimization
- **Explanation:** Process data closer to source for reduced latency
- **Input:** data sources, processing nodes, network topology
- **Output:** Optimized processing placement
- **Answer:** Data processed at optimal edge locations

**299. Quantum Algorithm Simulation**
- **Question:** Simulate quantum computing algorithms
- **Explanation:** Model quantum operations with classical computation
- **Input:** quantum circuit description
- **Output:** Probability amplitudes and measurement results
- **Answer:** Classical simulation of quantum algorithm behavior

**300. Machine Learning in JavaScript**
- **Question:** Implement neural network from scratch
- **Explanation:** Build and train neural network using only JavaScript
- **Input:** training data, network architecture
- **Output:** Trained model with prediction capabilities
- **Answer:** Neural network that can classify/predict based on training

### Bonus Expert Challenges (301-320)

**301. WebAssembly Integration**
- **Question:** Interface JavaScript with WebAssembly module
- **Explanation:** Call high-performance WASM functions from JS
- **Input:** WASM module with exported functions
- **Output:** JavaScript code using WASM for performance-critical tasks
- **Answer:** Seamless integration between JS and WASM

**302. Service Worker Implementation**
- **Question:** Create offline-capable app with service worker
- **Explanation:** Implement caching strategy for offline functionality
- **Input:** web application with network dependencies
- **Output:** App working offline with cached resources
- **Answer:** Service worker managing cache and offline behavior

**303. WebRTC Data Channel**
- **Question:** Implement peer-to-peer communication using WebRTC
- **Explanation:** Create direct browser-to-browser data transfer
- **Input:** two browser instances, data to transfer
- **Output:** Direct P2P communication without server
- **Answer:** Browsers communicating directly via WebRTC data channels

**304. IndexedDB Complex Queries**
- **Question:** Implement complex database operations with IndexedDB
- **Explanation:** Perform advanced queries and transactions on browser database
- **Input:** large dataset, complex query requirements
- **Output:** Efficient database operations in browser
- **Answer:** Fast queries using indexes and optimized transactions

**305. Canvas Performance Optimization**
- **Question:** Optimize high-performance canvas animations
- **Explanation:** Create smooth 60fps animations with thousands of objects
- **Input:** animation requirements, performance constraints
- **Output:** Optimized rendering pipeline
- **Answer:** Smooth animation using object pooling and efficient rendering

**306. WebGL Shader Programming**
- **Question:** Implement custom WebGL shaders for visual effects
- **Explanation:** Write vertex and fragment shaders for GPU computation
- **Input:** 3D scene requirements, visual effect specifications
- **Output:** Custom shaders running on GPU
- **Answer:** Hardware-accelerated graphics with custom shaders

**307. Audio Context Processing**
- **Question:** Build real-time audio effects processor
- **Explanation:** Process audio streams using Web Audio API
- **Input:** audio input, effect parameters
- **Output:** Real-time processed audio output
- **Answer:** Audio effects applied in real-time using Audio Context

**308. Intersection Observer Advanced**
- **Question:** Implement infinite scroll with performance optimization
- **Explanation:** Use Intersection Observer for efficient viewport monitoring
- **Input:** large list of items, scroll behavior requirements
- **Output:** Performant infinite scroll implementation
- **Answer:** Smooth scrolling with lazy loading and viewport optimization

**309. Custom Elements (Web Components)**
- **Question:** Create reusable web component with Shadow DOM
- **Explanation:** Build encapsulated custom HTML element
- **Input:** component specification, styling requirements
- **Output:** Reusable web component
- **Answer:** Custom element with encapsulated styles and behavior

**310. Broadcast Channel API**
- **Question:** Synchronize data across multiple browser tabs
- **Explanation:** Implement cross-tab communication and state sync
- **Input:** application state, multiple browser tabs
- **Output:** Synchronized state across all tabs
- **Answer:** Tabs automatically sync when data changes in any tab

**311. Performance Observer**
- **Question:** Monitor application performance metrics
- **Explanation:** Track performance using Performance Observer API
- **Input:** web application with performance requirements
- **Output:** Performance monitoring and optimization recommendations
- **Answer:** Detailed performance metrics with bottleneck identification

**312. Resize Observer**
- **Question:** Create responsive components that react to size changes
- **Explanation:** Use Resize Observer for element size monitoring
- **Input:** responsive layout requirements
- **Output:** Components that adapt to size changes
- **Answer:** Elements automatically adjust when container size changes

**313. Payment Request API**
- **Question:** Implement secure payment processing
- **Explanation:** Use Payment Request API for standardized payments
- **Input:** payment methods, transaction details
- **Output:** Secure payment flow with user consent
- **Answer:** Streamlined payment process using browser payment UI

**314. Credential Management API**
- **Question:** Implement passwordless authentication
- **Explanation:** Use Web Authentication API for biometric login
- **Input:** user registration, authentication requirements
- **Output:** Passwordless login system
- **Answer:** Users login with fingerprint/face recognition

**315. File System Access API**
- **Question:** Build file editor with native file system access
- **Explanation:** Read/write files directly from user's file system
- **Input:** file editing requirements, permission handling
- **Output:** Native file system integration
- **Answer:** App can open/save files like native applications

**316. Background Sync**
- **Question:** Implement offline-first data synchronization
- **Explanation:** Sync data when connection becomes available
- **Input:** data to sync, offline scenarios
- **Output:** Reliable data synchronization system
- **Answer:** Data automatically syncs when connectivity restored

**317. Push Notifications**
- **Question:** Create push notification system with service worker
- **Explanation:** Send notifications to users even when app is closed
- **Input:** notification service, user subscriptions
- **Output:** Cross-platform push notification system
- **Answer:** Users receive notifications even when browser closed

**318. Geolocation with High Accuracy**
- **Question:** Build location-aware application with GPS precision
- **Explanation:** Use Geolocation API with high accuracy requirements
- **Input:** location-based features, accuracy requirements
- **Output:** Precise location tracking application
- **Answer:** App tracks user location with meter-level precision

**319. Device Orientation & Motion**
- **Question:** Create motion-controlled interface using device sensors
- **Explanation:** Respond to device tilt, rotation, and acceleration
- **Input:** motion-based interaction requirements
- **Output:** Gesture-controlled interface
- **Answer:** App responds to device movements and orientation changes

**320. Advanced RegExp Features**
- **Question:** Use named capture groups and lookbehind in complex parsing
- **Explanation:** Parse complex text format using advanced regex features
- **Input:** complex text format, parsing requirements
- **Output:** Parsed data structure from complex text
- **Answer:** Structured data extracted using advanced regex patterns

---

## Practice Tips & Guidelines

### How to Use This Question Bank

1. **Start with Your Level**: Begin with questions slightly below your current skill level to build confidence
2. **Progressive Learning**: Move to harder questions gradually - don't jump levels too quickly
3. **Focus on Understanding**: Don't just solve the problem - understand why your solution works
4. **Multiple Approaches**: Try solving the same problem in different ways
5. **Time Yourself**: Practice with time constraints to simulate interview conditions

### Study Strategy

**Week 1-2: Foundations**
- Complete Basic level questions (1-75)
- Focus on syntax, basic methods, and core concepts
- Ensure you understand all fundamental JavaScript features

**Week 3-4: Building Skills**
- Work through Intermediate questions (76-150)
- Practice array methods, object manipulation, async basics
- Start timing yourself on easier questions

**Week 5-6: Advanced Concepts**
- Tackle Advanced level questions (151-225)
- Focus on complex algorithms, advanced async patterns
- Practice explaining your solutions out loud

**Week 7+: Mastery**
- Challenge yourself with Expert level questions (226-320+)
- Focus on optimization, performance, and cutting-edge features
- Practice system design and architectural thinking

### Key Areas to Master

1. **Data Structures**: Arrays, Objects, Maps, Sets, Trees
2. **Algorithms**: Sorting, searching, graph traversal, dynamic programming
3. **Asynchronous Programming**: Promises, async/await, event loops
4. **Functional Programming**: Higher-order functions, closures, currying
5. **Object-Oriented Programming**: Classes, inheritance, polymorphism
6. **Performance Optimization**: Memory management, algorithm complexity
7. **Modern JavaScript**: ES6+ features, modules, web APIs

### Common Interview Topics Covered

- **Technical Skills**: All JavaScript language features and APIs
- **Problem Solving**: Algorithmic thinking and optimization
- **Code Quality**: Clean code, maintainability, testing
- **Performance**: Big O analysis, optimization techniques
- **Real-world Applications**: Practical coding scenarios

### Remember

- **Practice Regularly**: Consistency is more important than marathon sessions
- **Understand, Don't Memorize**: Focus on understanding concepts and patterns
- **Code Without Looking**: Try to solve problems without referring to solutions
- **Review Mistakes**: Analyze what went wrong and why
- **Stay Current**: JavaScript evolves rapidly - keep learning new features

This question bank provides a comprehensive path from JavaScript basics to expert-level mastery. Each question is designed to test specific concepts while building practical coding skills. Good luck with your JavaScript journey! 🚀
