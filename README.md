# List Operations Example (`pyclass2.py`)

This Python script demonstrates basic list operations, including adding, inserting, extending, removing, and sorting elements in a list. It also shows how to find the index of a specific value.

## Code Overview

The script performs the following steps:

1. **Creates an empty list** and prints it.
2. **Appends** several integers (`10`, `20`, `30`, `40`) to the list, printing the list after each addition.
3. **Inserts** the value `15` at index 1 and prints the updated list.
4. **Extends** the list by adding multiple values (`50`, `60`, `70`) at once, then prints the list.
5. **Removes** the last element using `pop()` and prints the list.
6. **Sorts** the list in ascending order and prints the sorted list.
7. **Finds the index** of the value `30` in the sorted list and prints the list again.

## Example Output

```
[]
[10, 20, 30]
[10, 20, 30, 40]
[10, 15, 20, 30, 40]
[10, 15, 20, 30, 40, 50, 60, 70]
[10, 15, 20, 30, 40, 50, 60]
[10, 15, 20, 30, 40, 50, 60]
[10, 15, 20, 30, 40, 50, 60]
```

## Notes

- The script demonstrates how to use common list methods: `append()`, `insert()`, `extend()`, `pop()`, `sort()`, and `index()`.
- The call to `myList.index(30)` finds the position of `30` in the sorted list, but does not print it. To display the index, you could use:
  ```python
  print(myList.index(30))
  ```

---

Feel free to modify the script to experiment with other list operations!
