# IS-210-Spring-2025-class

Dictionaries and Sets in Python/Jupyter Notebooks:

Dictionaries are collections of key-value pairs, allowing efficient data retrieval. Sets are used for mathematical operations or to ensure uniqueness.

1. Dictionaries:
   - Create a dictionary using curly braces `{}` with key-value pairs.
   - Access values using keys: `dictionary[key]`.
   - Use `dictionary.items()` to iterate through all keys and values.
   - Example:
    >>> fruits = {"apple": 3, "banana": 5, "cherry": 7}

    >>> print(fruits["banana"])  

  - Expected Output: 5
  Dictionaries for quick lookups where a key maps to a specific value.

2. Sets:
   - Create a set using curly braces `{}` or the `set()` function.
   - Perform union (`|`), intersection (`&`), and difference (`-`) operations on sets.
   - Example:
     >>> colors1 = {"red", "blue", "green"}

     >>> colors2 = {"blue", "yellow", "pink"}

     >>> combined = colors1 | colors2

     >>> print (combined)

   - Expected Output: {'red', 'blue', 'green', 'yellow', 'pink'}
     Sets are used to remove duplicates or test for shared elements between groups.
