# Python Dictionary Exercise 📘
👨🏻‍🏫 **Instructor: Homayoun Beheshti -  TA: Ali Montajebi**

## dictionary exercise 1: Below are the two lists convert it into the dictionary

```python
keys = ['Ten', 'Twenty', 'Thirty']
values = [10, 20, 30]
```

**Expected output:**

```python
{'Ten': 10, 'Twenty': 20, 'Thirty': 30}
```

## dictionary exercise 2: Merge following two Python dictionaries into one

```python
dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}
dict2 = {'Thirty': 30, 'Fourty': 40, 'Fifty': 50}
```

**Expected output:**

```python
{'Ten': 10, 'Twenty': 20, 'Thirty': 30}
```

## dictionary exercise 3: Access the value of key ‘history’

```python
sampleDict = { 
    "class":{ 
        "student":{ 
            "name":"Mike",
            "marks":{ 
            "physics":70,
            "history":80
            }
        }
    }
}
```

**Expected output:**
80


## dictionary exercise 4: Initialize dictionary with default values

**Given**:

```python
employees = ['Kelly', 'Emma', 'John']
defaults = {"designation": 'Application Developer', "salary": 8000}
```

## dictionary exercise 5: Create a new dictionary by extracting the following keys from a given dictionary

**Given dictionary**:

```python
sampleDict = {
    "name": "Kelly",
    "age":25,
    "salary": 8000,
    "city": "New york"
    
}
```

**Keys to extract**

```python
keys = ["name", "salary"]
```

**Expected output:**

```python
{'name': 'Kelly', 'salary': 8000}
```

## dictionary exercise 6: Delete set of keys from Python Dictionary

**Given**:

```python
sampleDict = {
    "name": "Kelly",
    "age":25,
    "salary": 8000,
    "city": "New york"
    
}
```

```python
keysToRemove = ["name", "salary"]
```

**Expected output:**

```python
{'city': 'New york', 'age': 25}
```

## dictionary exercise 7: Check if a value *200* exists in a dictionary

```python
sampleDict = {'a': 100, 'b': 200, 'c': 300}
```

**Expected output:**


    True


## dictionary exercise 8: Rename key `city` to `location` in the following dictionary

```python
sampleDict = {
    "name": "Kelly",
    "age":25,
    "salary": 8000,
    "city": "New york"
}

sampleDict['location'] = sampleDict.pop('city')
print(sampleDict)
```

**Expected output:**

```python
{
    "name": "Kelly",
    "age":25,
    "salary": 8000,
    "location": "New york"
}
```


## dictionary exercise 9: Get the key corresponding to the minimum value from the following dictionary

```python
sampleDict = {
    'Physics': 82,
    'Math': 65,
    'history': 75
}
```

**Expected output:**
Math


## dictionary exercise 10: Given a Python dictionary, Change Brad’s salary to 8500

```python
sampleDict = {
        'emp1': {'name': 'Jhon', 'salary': 7500},
        'emp2': {'name': 'Emma', 'salary': 8000},
        'emp3': {'name': 'Brad', 'salary': 6500}
}
```

**Expected output:**

```python
sampleDict = {
        'emp1': {'name': 'Jhon', 'salary': 7500},
        'emp2': {'name': 'Emma', 'salary': 8000},
        'emp3': {'name': 'Brad', 'salary': 8500}
}
```

