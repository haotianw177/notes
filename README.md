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

[OpenAI](https://www.openai.com)



 -->

### access index elements    
The notation `dummy[i]` (dummy means dummy variable) is a common way across many programming languages to access an element at a specific index `i` in a collection, whether that collection is a string, list, array, or even some other data structure that supports indexing.

In lists/arrays/strings, `dummy[i]` accesses the element at index `i`.
In dictionaries, `dummy[i]` accesses the value associated with the key `i`

```
dictionary = {'a': 2, 'b': 1}  # Initial state of the dictionary

dictionary['a'] -= 1  # Decreases the value of 'a' by 1

print(dictionary)  # Output: {'a': 1, 'b': 1} 
```

### two pointers:
Single `i` in a loop: Locks you into comparing at the same index.\
Two pointers: Allows independent movement of the pointers, move freely base on whatever condition.

In programming, pointers (or variables acting as pointers in high-level languages) are variables that keep track of which index you're currently at in a string or array. These variables (such as `sPointer` and `tPointer`) hold integer values that represent the current index of the characters you are comparing in strings `s` and `t`.

### boolean and return
`return sPointer == len(s)` return the comparison result(T or F) of whether this statement is `True` of `False`

<!-- x -->