# Python — Conditions and Loops
**Date:** June 15, 2026  
**Topics Covered:** If/Else Conditions, For Loops

---

## If/Else — The Rules
1. Every condition line ends with a colon `:`
2. Code inside must be indented (Tab)
3. `=` stores a value. `==` checks equality

## If/Else Structure
```python
if condition:
    # runs if True
elif another_condition:
    # runs if first is False but this is True
else:
    # runs if everything above is False
```

## SQL vs Python Comparison
|           SQL          |    Python    |
|------------------------|--------------|
| CASE WHEN x > 100 THEN | if x > 100:  |
|   WHEN x > 50 THEN     | elif x > 50: |
|         ELSE           |    else:     |
|         AND            |    and       |
|         OR             |    or        |

## For Loop Structure
```python
for item in my_list:
    # do something with item
    # indented — mandatory
```

## For Loop — SQL Equivalent
Python for loop = SQL processing each row one by one
GROUP BY in SQL = for loop + if/else combined in Python

## What I Struggled With
- no confusion
