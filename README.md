
# Luhn Algorithm Card Validator

This Python project implements the Luhn Algorithm, a checksum formula used to validate credit and debit card numbers. It's a widely used algorithm in payment systems to detect errors or invalid numbers.

## Features
- Validates card numbers using the Luhn Algorithm.
- Supports card number input with or without spaces or dashes.
- Easy-to-read and well-documented Python code.

## How It Works
1. Removes non-numeric characters (e.g., spaces or dashes) from the input card number.
2. Reverses the card number and processes digits based on their position (odd/even).
3. Applies the Luhn checksum logic:
   - Odd-position digits are summed directly.
   - Even-position digits are doubled, and the sum of their digits is added to the total.
4. Determines the validity of the card number based on the final checksum.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/misbah-ullah01/luhn-algorithm-card-validator.git
   ```
2. Run the script:
   ```bash
   python card_validator.py
   ```
3. Enter your card number as a string (e.g., `5564-2708-8142-8839`), and the script will output whether it's valid or invalid.

## Example
Here’s how the program works with sample card numbers:

**Input 1:**
```python
card_number = '5564-2708-8142-8839'
```

**Output 1:**
```
VALID!
```

**Input 2:**
```python
card_number = '1234-5678-9012-3456'
```

**Output 2:**
```
INVALID!
```

**Input 3:**
```python
card_number = '4111-1111-1111-1111'
```

**Output 3:**
```
VALID!
```

## How to Customize
- Replace the `card_number` in the `main()` function with your card number to validate.
- Ensure the number is in string format (e.g., `'4111-1111-1111-1111'`).

## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
```

---
