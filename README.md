Due to the function scope, var is accessible throughout the function where it is declared. This can be quite problematic in some ways because variables declared with var can be reassigning by other parts of the function. Let and const are block scoped, which means they are only accessible in the block of code (defined by curly braces {}) in which they are declared. This makes the code easier to understand and reason about and also helps prevent accidental overwriting.




In JavaScript, the value ”0” returns false when matched with a Boolean context and hence is known as a “falsy” value. There are several contexts where this value is considered false; however, these contexts do not literally provide the falsy value. Some of the contexts where 0 is considered ‘falsy’ include: logical operations, conditional statements, if statements etc. The values ”0”, -0 , 0n, false, null, undefined, empty strings and NaN are all considered to be falsy values. Code within the if statement does not get executed when these values are used as conditions.

1.The value of ”false”: Any statement that is marked to be false is treated as a Boolean value and is defined as ”0” in the mathematical context.

2.The value of 0 within parenthesis: Zero is the mathematical representative of absence, and in the case of Java, it acts as false in a logical statement.

3.Empty String '' : An empty string has the value 0, making it a void string and hence is considered to return false in a logical statement.
