Due to the function scope, var is accessible throughout the function where it is declared. This can be quite problematic in some ways because variables declared with var can be reassigning by other parts of the function. Let and const are block scoped, which means they are only accessible in the block of code (defined by curly braces {}) in which they are declared. This makes the code easier to understand and reason about and also helps prevent accidental overwriting.
