# Python — Functions and Dictionaries
**Date:** June 16, 2026  
**Topics Covered:** Functions (def, parameters, return), Dictionaries

---

## Functions — The 4 Parts
```python
def function_name(parameter1, parameter2):
    # indented code — the work
    return result
```

|     Part      |                 What it does                             |
|---------------|----------------------------------------------------------|
| def           | tells Python you are creating a function                 |
| function_name | you choose this — use underscores, no spaces             |
| parameters    | inputs the function needs — like SQL function arguments  |
| return        | sends the answer back out — without this, answer is lost |

## Defining vs Calling
- **Define** = write the recipe (nothing happens yet)
- **Call** = cook the food (actually runs and gives output)

## SQL Equivalent
|               SQL               |      Python        |
|---------------------------------|--------------------|
| CREATE VIEW or stored procedure | def my_function(): |
|      Input parameters           |  Parameters in ()  |
|       SELECT result             |   return result    |

---

## Dictionaries — Key Concepts

```python
my_dict = {"key": value, "key2": value2}  # create
my_dict["key"]                             # access
my_dict["new_key"] = new_value            # add/update
"key" in my_dict                          # check if exists
my_dict.items()                           # get key+value pairs for looping
```

## SQL Equivalent
Dictionary = one row from a GROUP BY result  
{area: approval_rate} = SELECT area, approval_rate FROM summary

## Dictionary of Lists
- Each key = one column name  
- Each value = list of all values in that column  
- This is how Pandas DataFrames work internally

## What I Struggled With
- got little confusion in functions, by practicing got clarity

