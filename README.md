# APC
The Arbitrary Precision Calculator (APC) is designed to handle numbers of any size, overcoming the constraints of fixed data types like int or long. This project utilizes data structures such as linked lists, stacks, or arrays to store and manipulate large numbers.
1.Input Representation:

->Accept numbers as strings to handle arbitrary length.
->Parse and store digits in a custom data structure, such as linked lists (one digit per node) or arrays (one digit per element).
2.Core Operations:

->Addition and Subtraction:
Implement digit-wise operations with proper handling of carry and borrow.
->Multiplication:
Simulate manual multiplication with partial products and addition.
->Division:
Perform long division to compute quotient and remainder.
3.Output Representation:

->Convert the result back from the custom data structure to a human-readable string format.
4.User Interface:

->Provide a command-line interface for inputting operations (e.g., 12345678901234567890 + 98765432109876543210).
->Display detailed error messages for invalid inputs or unsupported operations.
