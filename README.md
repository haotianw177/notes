<!-- 


# Heading 1
## Heading 2
### Heading 3

**This text is bold**
*This text is italic*

- Item 1
- Item 2
  - Subitem 1
  - Subitem 2

1. First item
2. Second item
3. Third item

add code block: ```   code   ```



 -->

### access index elements and it's value   
The notation `dummy[i]` (where "dummy" is a placeholder variable name) is a common way across many programming languages to access an element at a specific index i in a collection, whether that collection is a string, list, array, or another data structure that supports indexing or key-based access.

In lists/arrays/strings, `dummy[i]` accesses the element at index i (the numerical position).
In dictionaries, `dummy[i] `accesses the value associated with the key i (since dictionaries use keys, not indices).

```
dictionary = {'a': 2, 'b': 1}  # Initial state of the dictionary

dictionary['a'] -= 1  # Decreases the value of 'a' by 1

print(dictionary)  # Output: {'a': 1, 'b': 1} 
```

The syntax `dummy[i]` always accesses the value at the specified index (in lists, arrays, and strings) or key (in dictionaries). Whether it's a list, string, or dictionary, this notation retrieves the value at the given location (position or key). The value you're accessing depends on the data structure, but it’s always the value, not the element or key itself.

### two pointers:
Single `i` in a loop: Locks you into comparing at the same index.\
Two pointers: Allows independent movement of the pointers, move freely base on whatever condition.

In programming, pointers (or variables acting as pointers in high-level languages) are variables that keep track of which index you're currently at in a string or array. These variables (such as `sPointer` and `tPointer`) hold integer values that represent the current index of the characters you are comparing in strings `s` and `t`.

### boolean and return
`return sPointer == len(s)` return the comparison result(T or F) of whether this statement is `True` of `False`

### Algorithm
## in-place algorithm
 an in-place algorithm is an algorithm that operates directly on the input data structure without requiring extra space proportional to the input size. In other words, it modifies the input in place, without creating a separate copy of the data structure. An algorithm which is not in-place is sometimes called not-in-place or out-of-place.

<!-- x -->