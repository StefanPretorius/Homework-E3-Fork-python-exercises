## Stream of Numbers

1. Print the numbers between 0 and 10
2. Print the number between 0 and -10

### Solution

1.

```python
for i in range(0, 11):
    print(i)
```
#Using a while loop to display 0 to 10
i = 0

while i < 11:
    print(i)
    i += 1

2.

```python
for i in range (0, -11, -1):
    print(i)
```
#Using a while loop to display 0 to 10
i = 0

while i > -11:
    print(i)
    i -= 1