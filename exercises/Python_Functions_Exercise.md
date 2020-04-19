# Python Functions Exercise 🚀

👨🏻‍🏫 **Instructor: Homayoun Beheshti - TA: Ali Montajebi**

**Exercise Question 1: Create a function that can accept two arguments name and age and print its value**

**Exercise Question 2: Write a function** `**func1()**` **such that it can accept a variable length of argument and print all arguments value**

    func1(20, 40, 60)
    func1(80, 100)

**Expected Output**:s
After `func1(20, 40, 60)`:
20
40
60
After `func1(80, 100)`:
80
100

**Exercise Question 3: Write a function** `**calculation()**` **such that it can accept two variables and calculate the addition and subtraction of it. And also it must return both addition and subtraction in a single return call**

For example:

```pthon
def calculation(a, b):
    # Your Code

res = calculation(40, 10)
print(res)
```

A res should produce result 50, 30

**Exercise Question 4: Create a function** `**showEmployee()**` **in such a way that it should accept employee name, and it’s salary and display both, and if the salary is missing in function call it should show it as 9000**

**Expected Output**:

    showEmployee("Ben", 9000)
    showEmployee("Ben")

Should Produce:
Employee Ben salary is: 9000
Employee Ben salary is: 9000

**Exercise Question 5: Create an inner function to calculate the addition in the following way**

- Create an outer function that will accept two parameters `a` and `b`
- Create an inner function inside an outer function that will calculate the addition of `a` and `b`
- At last, an outer function will add 5 into addition and return it

**Exercise Question 6: Assign a different name to function and call it through the new name**
Below is the function `displayStudent(name, age)`. Assign a new name `showStudent(name, age)` to it and call through the new name

```pyhton
def displayStudent(name, age):
    print(name, age)

displayStudent("Emma", 26)
```

You should be able to call the same function using

```pyhton
showStudent(name, age)
```

**Exercise Question 7:** What is the output of the following code

```pyhton
def outerFun(a, b):
    def innerFun(c, d):
        return c + d
    return innerFun(a, b)

res = outerFun(5, 10)
print(res)
```

**Exercise Question 8:** What is the output of the following function call

```pyhton
def fun1(name, age=20):
    print(name, age)

fun1('Emma', 25)
```

**Exercise Question 9:** Select which true for Python function

[ ] A function is a code block that only executes when it is called.
[ ] Python function always returns a value.
[ ] A function only executes when it is called and we can reuse it in a program
[ ] Python doesn’t support nested function

**Exercise Question 10:** What is the output of the following function call

```pyhton
def outerFun(a, b):
    def innerFun(c, d):
        return c + d
    return innerFun(a, b)
    return a

result = outerFun(5, 10)
print(result)
```

**Exercise Question 11:** Select which is true for Python function

[ ] A Python function can return only a single value
[ ] A function can take an unlimited number of arguments.
[ ] A Python function can return multiple values
[ ] Python function doesn’t return anything unless and until you add a return statement
