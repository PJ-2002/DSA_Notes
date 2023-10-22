# Strings
Strings in Python are one of the most commonly used data types. They are sequences of characters that can be enclosed by either single quotes or double quotes. For example, ‘Hello’ and “World” are both valid strings in Python.

Strings can be accessed by indexing, slicing, or looping through the characters. Indexing means using square brackets to get a specific character from a string. For example, ‘Hello’ [0] returns ‘H’. Slicing means using a colon to get a range of characters from a string. For example, ‘Hello’ [1:3] returns ‘el’. Looping means using a for loop to iterate over the characters in a string. For example, for x in ‘Hello’: print(x) prints each character in a new line.

Strings are immutable in Python, which means they cannot be modified after they are created. However, you can create new strings by concatenating, formatting, or using built-in methods. Concatenating means using the + operator to join two or more strings together. For example, ‘Hello’ + ‘World’ returns ‘HelloWorld’. Formatting means using placeholders and values to create a formatted string. For example, ‘Hello {}’ .format(‘World’) returns ‘Hello World’. Built-in methods are functions that can be applied to strings to perform various operations. For example, ‘Hello’.upper() returns ‘HELLO’.

Strings can also be compared using the == operator, which returns True if two strings are equal and False otherwise. For example, ‘Hello’ == ‘World’ returns False, while ‘Hello’ == ‘Hello’ returns True.

Concatenation: This operation joins two or more strings together to form a new string. For example, ‘Hello’ + ‘World’ returns ‘HelloWorld’. The time complexity of this operation depends on the length of the strings. In Python, concatenation is 0 (n), where n is the total length of the strings, because it creates a new string object.
Removing: O (n), where n is the length of the string, because it creates a new string object without the removed character and copies the remaining characters from the original string.
Modifying: O (n), where n is the length of the string, because it creates a new string object with the modified character and copies the other characters from the original string.
Slicing: O (k), where k is the length of the substring, because it creates a new string object with the sliced characters and copies them from the original string.


