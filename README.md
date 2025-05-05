# Python Refresher
A repo to brush up on Python.

![Python](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png)

## In This Document:
  - [What](#what)
  - [Why](#why)
  - [Why Not](#why-not)
  - [How Do You](#how-do-you)

<details>
<summary>What</summary>
  
## What
Python is [the most popular programming language today](https://www.tiobe.com/tiobe-index/).
- It was created in 1991 by Guido van Rossum.
- It's easy to learn, read, and write. It reads like English. It's executable pseudocode.
- It's dynamically typed.
- It's OOP.
- It's FP.
</details>

<details>
<summary>Why</summary>
  
## Why
- It's easy to learn, read, and write.
- It's perfect for coding interviews. The syntax gets out of the way so you focus on solving the problem.
- It's in high demand.
- It's very powerful.
- It's widely used for: 
  - Machine learning
  - AI
  - Data science
  - Backend development
  - DevOps, cloud computing, infrastructure, and automation
</details>

<details>
<summary>Why Not</summary>
  
## Why Not
- It has low performance (slow), so it's not used much for system programming and tools.
- It's not JavaScript, so it's not used much for UI and frontend development.
</details>

<details>
<summary>How Do You?</summary>
  
## How Do You?

<details>
<summary><em>input</em> data from the user:</summary>

```
input("Enter number: ")
```
</details>

<details>
<summary>store data in a <em>variable</em>:</summary>

```
age = 55
civilization_age = 10_000
very_big_number = 1.6e40
binary = 0b1100
average = 45.67
name = "Tim"
winner = True
placeholder = None

smallest_num = float("-Inf")
largest_num = float("Inf")
```
</details>

<details>
<summary>do math:</summary>
  
```
sum = a + b
sub = a - b
mul = a * b
div = a / b
floor_div = a // b
pow = a ** 2
rem = a % 2
```
</details>

<details>
<summary>do bit-wise <em>&</em> and <em>|</em>:</summary>

```
return 0b1100 & 0b1010
return 0b1100 | 0b1010
```
</details>

<details>
<summary>know the <em>type</em> of a variable:</summary>

```
print(type(a))
```
</details>

<details>
<summary><em>print</em> results:</summary>
  
```
print(result)
print(f"Result: {result}")
```
</details>

<details>
<summary>decide <em>if</em> you want to do something or <em>else</em>:</summary>
  
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
</details>

<details>
<summary>repeat something <em>for</em> a number of times:</summary>
  
```
for i in range(10):
    print(i)

for i in range(0, 10, 1):
    print(i)

for i in range(10, -1, -1):
    print(i)
```
</details>

<details>
<summary>repeat something <em>while</em> a condition is True:</summary>
  
```
i = 0
while i < 5:
    print(i)
    i += 1
```
</details>

<details>
<summary><em>def</em>ine a function to reuse and organize your code:</summary>
  
```
def sum(a, b):
    return a + b

print(sum(1, 2))
```
</details>

<details>
<summary>store a <em>list</em> of data and loop over it:</summary>
  
```
list = [1, 2, 3]

list[0] = 100
print(list[-1])
print(len(list))

for item in list:
    print(item)
```
</details>

<details>
<summary>get a slice of the list:</summary>
  
```
slice_a = list[0:5]
slice_b = list[:5]
slice_c = list[:]
slice_d = list[-1:-3:-1]
```
</details>

<details>
<summary>check if an item is <em>in</em> the list or <em>not</em>:</summary>
  
```
if item in list:
    print("Found")

if item not in list:
    print("Not found")
```
</details>

<details>
<summary><em>append</em> an item to the end of the list:</summary>
  
```
list.append(5)
```
</details>

<details>
<summary><em>pop</em> an item from the end of the list:</summary>
  
```
item = list.pop()
```
</details>

<details>
<summary><em>del</em>ete an item using its index:</summary>
  
```
del list[0]
```
</details>

<details>
<summary>concatenate two lists with the <em>+</em> operator:</summary>
  
```
merged = [1, 2, 3] + [4, 5, 6]
```
</details>

<details>
<summary><em>split</em> a string into an array of strings, then use the delimiter again as a joiner to <em>join</em> the strings back into one:</summary>
  
```
words = "Hello, World!".split(" ")
together_again = " ".join(words)
```
</details>

<details>
<summary>store immutable items, ordered, in a <em>tuple</em>:</summary>
  
```
person = ("Tim", 55, "M", True)
print(person[0])

one_item_tuple = (4,)
```
</details>

<details>
<summary>store key -> value pairs, ordered, as in a <em>dictionary</em>:</summary>
  
```
person = {"name": "Tim", "age": 55}

person["name"] = "Timothy"

del person["age"]

if "age" in person:
    print("He has age"!)

for key in person:
    print(person[key])
```
</details>

<details>
<summary>store unique items, unordered, in a <em>set</em>:</summary>
  
```
long = {1, 2, 3, 4, 5, 6}
nums = set()
nums.add(1)
nums.remove(5)
```
</details>

<details>
<summary><em>try</em> something and if it raises an <em>except</em>ion, handle it:</summary>
  
```
try:
    1 / 0
except Exception as e:
    print(e)
```
</details>

<details>
<summary><em>raise</em> an <em>Exception</em> yourself:</summary>
  
```
if funds < price:
    raise Exception("Too expensive for me")
```
</details>

<details>
<summary><em>open</em> a file <em>with</em> resources, i.e. close it after you're done</summary>
  
```
with open(path) as f:
    text = f.read()
```
</details>

<details>
<summary>read command line <em>arg</em>uments</summary>
  
```
book_path = sys.argv[1]
```
</details>

<details>
<summary><em>exit</em> the program with an error code of 1</summary>
  
```
sys.exit(1)
```
</details>
</details>
