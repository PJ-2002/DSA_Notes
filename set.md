## Set build-in functions:

### len(set): 
This function returns the number of elements in the set. For example, len({1, 2, 3}) returns 3.
### max(set) and min(set): 
These functions return the largest and smallest element in the set, respectively. For example, max({1, 2, 3}) returns 3 and min({1, 2, 3}) returns 1.
### sum(set): 
This function returns the sum of all the elements in the set. For example, sum({1, 2, 3}) returns 6.
### set(iterable): 
This function converts an iterable (such as a string, tuple, or list) into a set. For example, set("abc") returns {a, b, c}.
### sorted(set): 
This function returns a new list with the elements of the original set sorted in ascending order. For example, sorted({3, 1, 2}) returns [1, 2, 3].
### .add():
To add a single element to a set, you can use the add() method. For example, my_set.add(4) will add 4 to my_set.
### .update()
To add multiple elements to a set, you can use the update() method. This method takes an iterable (such as a list, tuple, or another set) and adds all its elements to the set. For example, my_set.update([5, 6, 7]) will add 5, 6, and 7 to my_set.
### .remove()
To remove an element from a set, you can use the remove() method. This method takes the element as an argument and removes it from the set. If the element is not in the set, it raises a KeyError. For example, my_set.remove(4) will remove 4 from my_set.
### .discard()
To remove an element from a set without raising an error if it is not present, you can use the discard() method. This method also takes the element as an argument and removes it from the set if it exists. For example, my_set.discard(8) will remove 8 from my_set if it is there, or do nothing otherwise.
### .pop()
To remove and return a random element from a set, you can use the pop() method. This method takes no arguments and returns an arbitrary element from the set. If the set is empty, it raises a KeyError. For example, my_set.pop() will return and remove some element from my_set.
### .clear()
To remove all elements from a set, you can use the clear() method. This method takes no arguments and empties the set. For example, my_set.clear() will make my_set an empty set.
