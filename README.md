# Simple Calculator

A simple calculator package for performing basic arithmetic operations.

## Installation

You can install the Simple Calculator package via npm:

```bash
npm install abewe-basic-calculator

`````
## Usage

```javascript
// Import the Simple Calculator module
const { add, subtract, multiply, divide } = require('abewe-basic-calculator');

// Add two numbers
const sum = add(5, 3);
console.log('Sum:', sum); // Output: 8


`````

 ## API Documentation

### `add(a, b)`

Adds two numbers together.

#### Parameters

- `a` (number): The first number to add.
- `b` (number): The second number to add.

#### Returns

(number): The sum of the two numbers.

### `subtract(a, b)`

Subtracts one number from another.

#### Parameters

- `a` (number): The number to subtract from.
- `b` (number): The number to subtract.

#### Returns

(number): The difference between the two numbers.

### `multiply(a, b)`

Multiplies two numbers together.

#### Parameters

- `a` (number): The first number to multiply.
- `b` (number): The second number to multiply.

#### Returns

(number): The product of the two numbers.

### `divide(a, b)`

Divides one number by another.

#### Parameters

- `a` (number): The number to be divided.
- `b` (number): The divisor.

#### Returns

(number): The quotient of the two numbers.

    
   # License
   This project is licensed under the *MIT* License - see the LICENSE file for details
