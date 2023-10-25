## Dictionary Built-in function
## dict(): 
This function creates a new dictionary from an iterable of key-value pairs, or from keyword arguments. For example, dict([("a", 1), ("b", 2)]) returns {"a": 1, "b": 2} and dict(a=1, b=2) returns the same1.
## len(): 
This function returns the number of items in a dictionary. For example, len({"a": 1, "b": 2}) returns 21.
## max() and min(): 
These functions return the largest and smallest key in a dictionary, respectively. For example, max({"a": 1, "b": 2}) returns "b" and min({"a": 1, "b": 2}) returns "a"1.
## sum(): 
This function returns the sum of all the values in a dictionary. For example, sum({"a": 1, "b": 2}) returns 31.
## clear(): 
This method removes all the key-value pairs from the dictionary. For example, {"a": 1, "b": 2}.clear() makes the dictionary empty2.
## copy(): 
This method returns a shallow copy of the dictionary. For example, {"a": 1, "b": 2}.copy() returns a new dictionary with the same key-value pairs as the original2.
## fromkeys(): 
This method creates a new dictionary from the given iterable (such as a string, list, set, tuple) as keys and with the specified value. For example, dict.fromkeys("abc", 0) returns {"a": 0, "b": 0, "c": 0}2.
## get(): 
This method returns the value of the specified key in the dictionary. If the key is not found, it returns None or a default value if specified. For example, {"a": 1, "b": 2}.get("c") returns None and {"a": 1, "b": 2}.get("c", -1) returns -12.
## items(): 
This method returns a view object that provides a dynamic view of dictionary elements as a list of key-value pairs. This view object changes when the dictionary changes. For example, {"a": 1, "b": 2}.items() returns a view object like [("a", 1), ("b", 2)]2.
## keys(): 
This method returns a view object that contains the list of keys of the dictionary. This view object changes when the dictionary changes. For example, {"a": 1, "b": 2}.keys() returns a view object like ["a", "b"]2.
## pop(): 
This method removes and returns the value of the specified key in the dictionary. If the key is not found, it raises a KeyError or returns a default value if specified. For example, {"a": 1, "b": 2}.pop("a") returns 1 and removes "a" from the dictionary2.
## popitem(): 
This method removes and returns an arbitrary key-value pair from the dictionary. If the dictionary is empty, it raises a KeyError. For example, {"a": 1, "b": 2}.popitem() may return ("b", 2) and remove "b" from the dictionary2.
## setdefault(): 
This method returns the value of the specified key in the dictionary. If the key is not found, it inserts the key with a default value and returns that value. If no default value is specified, it uses None
## update(): 
This method updates the dictionary with the key-value pairs from another dictionary or an iterable of key-value pairs. If a key already exists in the dictionary, its value is overwritten by the new value. For example, {"a": 1, "b": 2}.update({"b": 3, "c": 4}) changes the dictionary to {"a": 1, "b": 3, "c": 4}.
## values(): 
This method returns a view object that contains the list of values of the dictionary. This view object changes when the dictionary changes. For example, {"a": 1, "b": 2}.values() returns a view object like [1, 2].
## in: 
This operator tests if a key is in the dictionary. It returns True if the key is found, and False otherwise. For example, "a" in {"a": 1, "b": 2} returns True and "c" in {"a": 1, "b": 2} returns False.
## not in: 
This operator tests if a key is not in the dictionary. It returns True if the key is not found, and False otherwise. For example, "c" not in {"a": 1, "b": 2} returns True and "a" not in {"a": 1, "b": 2} returns False.
# when to use dictionary and when to use default dictionary 

Use defaultdict when you want to create a dictionary that can handle missing keys more gracefully and efficiently. For example, if you want to create a dictionary of lists, sets, counters, or other collections, defaultdict can save you the hassle of checking if the key exists or not before adding values. 😊

Use defaultdict when you want to create a dictionary that can generate values for keys on the fly using a custom function. For example, if you want to create a dictionary that maps numbers to their square roots, factorials, or other mathematical functions, defaultdict can save you the time and space of calculating and storing them beforehand. 😊

Use normal dict when you want to create a dictionary that has a fixed set of keys and values that are known in advance. For example, if you want to create a dictionary that maps names to phone numbers, colors to hex codes, or countries to capitals, normal dict can be more straightforward and intuitive. 😊

Use normal dict when you want to create a dictionary that does not need a default value for missing keys or when you want to handle the KeyError exception yourself. For example, if you want to create a dictionary that maps words to their definitions, synonyms, or antonyms, normal dict can give you more control and flexibility over how to deal with unknown words. 😊
