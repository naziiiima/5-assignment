Testing Report for StringProcessor Class
Overview
This report provides a summary of the testing conducted on the StringProcessor class, which features methods for checking password strength, counting digits, counting words, and evaluating mathematical expressions.

Test Cases
1. Password Strength Check
Test Case 1:

Input: "Strong1@"
Expected Result: true
Actual Result: true
Outcome: Passed
Test Case 2:

Input: "weakpass"
Expected Result: false
Actual Result: false
Outcome: Passed
2. Counting Digits
Test Case 1:

Input: "Hello 123!"
Expected Result: 3
Actual Result: 3
Outcome: Passed
Test Case 2:

Input: "No digits here."
Expected Result: 0
Actual Result: 0
Outcome: Passed
3. Counting Words
Test Case:
Input: "This is a sample input."
Expected Result: 5
Actual Result: 5
Outcome: Passed
4. Evaluating Mathematical Expressions
Test Case 1:

Input: "2 + 3"
Expected Result: 5.0
Actual Result: 5.0
Outcome: Passed
Test Case 2:

Input: "(1 + 2) * 3 - 1"
Expected Result: 8.0
Actual Result: 8.0
Outcome: Passed
Issues Encountered
During testing, I encountered issues with expression evaluation due to incorrect formatting. Some expressions raised exceptions, which were addressed by validating the input to ensure it was well-formed before evaluation.

Conclusion
The testing of the StringProcessor class was successful, with all test cases passing and no critical issues identified. I gained valuable experience in creating unit tests using JUnit and improved my understanding of exception handling in code.
