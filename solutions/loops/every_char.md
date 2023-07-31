## Every Character

#Given a variable of a string, print character of the string on its own line.

### Solution

```python
string = "python"
for char in string:
    print(char)
````

#Another solution using a counter
string = "python"
index = 0

while index < len(string):
    print(string[index])
    index += 1