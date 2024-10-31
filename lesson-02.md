# Loops
## `for` loop
Used for iterating over a sequence (like a list, tuple, string, or range).

Syntax:

```python
for item in sequence:
    # code to execute for each item
```
Example:
```python
for i in range(5):  # Iterates from 0 to 4
    print(i)
```    
2. while loop
Runs as long as a specified condition is True.
Syntax:
```python
while condition:
    # code to execute while condition is True
```
Example:
```python
count = 0
while count < 5:  # Runs until count is no longer less than 5
    print(count)
    count += 1
```

### Additional Keywords
* `break`: Exits the loop prematurely.
* `continue`: Skips to the next iteration without completing the current one.
Examples:
```python
for i in range(5):
    if i == 3:
        break  # Exits the loop when i is 3
    print(i)

for i in range(5):
    if i == 2:
        continue  # Skips printing when i is 2
    print(i)
```

These two loop types cover most use cases for repeating code in Python.