# Tarea 1, Pruebas de caja negra

1. Function that checks if a given number is positive, negative, or zero.

| Input      | Output   |
| ---------- | -------- |
| 0          | Zero     |
| 1          | Positive |
| -1         | Negative |
| -1_000_000 | Negative |
| 10_000_000 | Positive |
| a          | NaN      |
| null       | NaN      |

2. Function that validates user passwords.
   The password validation rules are as follows:

The password must be at least 8 characters long.
The password must contain at least one uppercase letter,
one lowercase letter, one digit, and one special character (!, @, #, $, %, or &).

| Input      | Output |
| ---------- | ------ |
| Password   | false  |
| Password1  | false  |
| $Password1 | true   |
| $Pas1      | false  |
| $$$111     | false  |
| null       | false  |
| 123        | false  |

3. Function that calculates the discount for a customer's purchase based on the total amount.
   The discount rules are as follows:

If the total amount is less than 100, no discount is applied.
If the total amount is between 100 and 500 (inclusive), a 10% discount is applied.
If the total amount is greater than 500, a 20% discount is applied.

| Input | Output |
| ----- | ------ |
| 35    | 35     |
| -10   | error  |
| 0     | 0      |
| 250   | 225    |
| 500   | 450    |
| 850   | 680    |
| 1000  | 800    |
