# Python List Exercise 🚌

**Exercise Question 1: Given a Python list you should be able to display Python list in the following order**
```python
aLsit = [100, 200, 300, 400, 500]
```

**Expected output:**
```python
[500, 400, 300, 200, 100]
```


**Exercise Question 2: Concatenate two lists index-wise**
```python
list1 = ["M", "na", "i", "Ke"]
list2 = ["y", "me", "s", "lly"]
```
**Expected output:**
```python
['My', 'name', 'is', 'Kelly']
````
**Exercise Question 3: Remove empty strings from the list of strings**
```python
list1 = ["Mike", "", "Emma", "Kelly", "", "Brad"]
````
**Expected output:**
```python
["Mike", "Emma", "Kelly", "Brad"]
````
**Exercise Question 4: Add item 7000 after 6000 in the following Python List**
```python
list1 = [10, 20, [300, 400, [5000, 6000], 500], 30, 40]
````
**Expected output:**
```python
[10, 20, [300, 400, [5000, 6000, 7000], 500], 30, 40]
````
**Exercise Question 5: Given a nested list extend it with adding sub list** `**["h", "i", "j"]**` **in a such a way that it will look like the following list**

Given List:
```python
list1 = ["a", "b", ["c", ["d", "e", ["f", "g"], "k"], "l"], "m", "n"]
````
Sub List to be added = `["h", "i", "j"]`

**Expected output:**
```python
['a', 'b', ['c', ['d', 'e', ['f', 'g', 'h', 'i', 'j'], 'k'], 'l'], 'm', 'n']
```
**Exercise Question 6: Given a Python list, find value 20 in the list, and if it is present, replace it with 200. Only update the first occurrence of a value**
```python
list1 = [5, 10, 15, 20, 25, 50, 20]
````
**Expected output:**
```python
list1 = [5, 10, 15, 200, 25, 50, 20]
````
**Exercise Question 7: What is the output of the following code?**
```python
my_list = ["Hello", "Python"]
print("-".join(my_list))
```
**Exercise Question 8: Select all the correct options to copy a list.**
```python
aList = ['a', 'b', 'c', 'd']
````
[ ] newList = copy(aList)
[ ] newList = aList.copy()
[ ] newList.copy(aList)
[ ] newList = list(aList)

**Exercise Question 9: Select all the correct options to join two lists in Python.**
```python
listOne  =  ['a', 'b', 'c', 'd']
listTwo =  ['e', 'f', 'g']
```
[ ] newList = listOne + listTwo
[ ] newList = extend(listOne, listTwo)
[ ] newList = listOne.extend(listTwo)
[ ] newList.extend(listOne, listTwo)

**Exercise Question 10: What is the output of the following list function?**
```python
sampleList = [10, 20, 30, 40, 50]
sampleList.append(60)
print(sampleList)

sampleList.append(60)
print(sampleList)
```
**Exercise Question 11: What is the output of the following code?**
```python
aList = ["PYnative", [4, 8, 12, 16]]
print(aList\[0\][1])
print(aList\[1\][3])
````

**Exercise Question 12: What is the output of the following?**
```python
l = [None] * 10
print(len(l))
```
**Exercise Question 13: What is the output of the following?**
```python
aList = [5, 10, 15, 25]
print(aList[::-2])
```
**Exercise Question 14: What is the output of the following list operation?**
```python
aList = [10, 20, 30, 40, 50, 60, 70, 80]
print(aList[2:5])
print(aList[:4])
print(aList[3:])
```
**Exercise Question 15: What is the output of the following code?**
```python
sampleList = [10, 20, 30, 40]
del sampleList[0:6]
print(sampleList)
```
**Exercise Question 16: What is the output of the following list function?**
```python
sampleList = [10, 20, 30, 40, 50]
sampleList.pop()
print(sampleList)

sampleList.pop(2)
print(sampleList)
```

**Exercise Question 17: What is the output of the following list assignment?**
```python
aList = [4, 8, 12, 16]
aList[1:4] = [20, 24, 28]
print(aList)
```

**Exercise Question 18: In Python,** `**list**` **is mutable:**

[ ] False
[ ] True

**Exercise Question 19: What is the output of the following code?**
```python
list1 = ['xyz', 'zara', 'PYnative']
print(max(list1))
```
