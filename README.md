# Python Refresher
A repo to brush up on Python.

![Python](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png)

## In This Document:
  - [What](#what)
  - [Why](#why)
  - [Why Not](#why-not)
  - [How Do You](#how-do-you)

## What
Python is [the most popular programming language today](https://www.tiobe.com/tiobe-index/).
- It was created in 1991 by Guido van Rossum.
- It's easy to learn, read, and write. It reads like English. It's executable pseudocode.
- It's dynamically typed.
- It's OOP.
- It's FP.

## Why
- It's easy to learn, read, and write.
- It's in high demand.
- It's widely used for: 
  - Machine learning
  - AI
  - Data science
  - Backend development
  - DevOps, cloud computing, infrastructure, and automation

## Why Not
- It has low performance (slow), so it's not used much for system programming and tools.
- It's not JavaScript, so it's not used much for UI and frontend development.

## How Do You?

**input** data from the user:
```
input("Enter number: ")
```

store data in a **variable**:
```
age = 55
average = 45.67
name = "Tim"
winner = True
```

do math:
```
sum = a + b
sub = a - b
mul = a * b
div = a / b
floor_div = a // b
pow = a ** 2
```

**print** results:
```
print(result)
print(f"Result: {result}")
```

decide **if** you want to do something or **else**:
```
if a > b:
    print(a)
elif b < a:
    print(b)
else:
    print("Equal")

if a and b:
    print("AND")
elif a or b:
    print("OR")
elif not c:
    print("NOT")
```

repeat something **for** a number of times:
```
for i in range(10):
    print(i)

for i in range(0, 10, 1):
    print(i)

for i in range(10, -1, -1):
    print(i)
```

repeat something **while** a condition is True:
```
i = 0
while i < 5:
    print(i)
    i += 1
```

**def**ine a function to reuse and organize your code:
```
def sum(a, b):
    return a + b

print(sum(1, 2))
```

store a **list** of data and loop over it:
```
list = [1, 2, 3]

list[0] = 100
print(list[-1])

for item in list:
    print(item)
```

get a slice of the list:
```
slice_a = list[0:5]
slice_b = list[:5]
slice_c = list[:]
slice_d = list[-1:-3:-1]
```

check if an item is **in** the list or **not**:
```
if item in list:
    print("Found")

if item not in list:
    print("Not found")
```

**append** an item to the end of the list:
```
list.append(5)
```

**pop** an item from the end of the list:
```
item = list.pop()
```

**del**ete an item using its index:
```
del list[0]
```

store key -> value pairs, ordered, as in a **dictionary**:
```
person = {"name": "Tim", "age": 55}

person["name"] = "Timothy"

del person["age"]

for key in person:
    print(person[key])
```

store unique items, unordered, in a **set**:
```
long = {1, 2, 3, 4, 5, 6}
nums = set()
nums.add(1)
nums.remove(5)
```

store immutable items, ordered, in a **tuple**:
```
person = ("Tim", 55, "M", True)
print(person[0])
```

**try** something and if it raises an **except**ion, handle it:
```
try:
    1 / 0
except Exception as e:
    print(e)
```

**raise** an **Exception** yourself:
```
if funds < price:
    raise Exception("Too expensive for me")
```

















