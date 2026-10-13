# python-list-element-frequency

## Topics Covered
- Python Lists
- Python Dictionaries
- For Loop
- `count()` Method

## Code
```python
l = [5,4,5,4,6,7,8,4,3,5,3,4]

d = {}

for i in l:
    d[i] = l.count(i)

print(d)
```

## Output
```python
{5: 3, 4: 4, 6: 1, 7: 1, 8: 1, 3: 2}
```

## Concepts Learned
- Finding the frequency of list elements.
- Storing elements and their counts in a dictionary.
- Using a for loop and the `count()` method.

## Author
**Mrudul Pawar**
