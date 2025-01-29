# Function-to-retrieve-Unicode-and-UTF-8-byte-code-values-from-a-String-in-Python

simple Python project that demonstrates the use of Unicode UTF-8. We'll write a program that takes user input, converts it into UTF-8, and then displays the Unicode representation for each character in the string.

Project: Unicode UTF-8 Converter
Goal:
This program will:

Accept a string input from the user.
Encode the string into UTF-8.
Display the UTF-8 byte values for each character.
Steps:
Get input from the user.
Convert the input string to UTF-8 encoding.
Display the Unicode code points and their corresponding UTF-8 byte values

Explanation:
input(): Takes a string input from the user.
encode('utf-8'): Encodes the input string into UTF-8 bytes.
ord(): Converts each character into its Unicode code point.
Loop: For each character in the string, it prints the character, its Unicode code point, and its corresponding byte in the UTF-8 encoding.

How It Works:
Each character, whether a standard English letter or an emoji, is converted into its Unicode code point and its corresponding UTF-8 byte(s).
For example, the emoji🌍 has a Unicode code point of 127757, and its UTF-8 encoding involves multiple bytes (240 in this case).

This project is a basic demonstration of working with Unicode and UTF-8 in Python. It can be extended or modified to handle more advanced scenarios, such as reading from files, handling different encodings, or performing operations on non-ASCII characters.
