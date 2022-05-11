# Python Session NO.1

## Headlines

- **Display "Hello World!!"**
- **Variables**
- **String method**
- **User input**
- **Math functions**
- **String slicing**
- **If statements**

---

## Topic

### Display "Hello World!!"

- **To display anything just use print() function**

```python
print("Hello world!!")
```

---

### Variables

- **Variable is a container for a value look like methods in algebra x = 5+2 so x = 7**
- **There is 3 types of variable strings, numbers,and booleans...**

#### Strings

- **a series of characters**

  ```python
    f_name = "Ahmed"
    l_name = "Sobhi"
  ```

- **You also can sum strings together**
  ```python
  name = f_name + " " + l_name
  ```
- **To display variable...**
  ```python
   print(name)  # not "name"
   print(f"Hello {name}")  # This method calling a format
   print("Hello " + name)  # There is another one
   print("Hello", name)
  ```
- **There is something called methods we use it to know some thing like type of variable or lenght of it**
- **type() = a Data type of thing**
  ```python
  print(type(name))
  ```

#### int (integer)

- **a whole number**
  ```python
  age = 21  # if you add "" to number it will be string
  ```
- **We also can use math on numbers like add**
- **think about it is looking like x= 7 (+1) and you also you can write it by (age += 1)**
  `python age = age + 1 `
- **There is another data type in numbers that's called float...**
- **Float look like 2.00 number not just 2**
  ```python
    height = 168.5
  ```

#### Boolean

- **Boolean = briefly it is either yes (True) or no (False)**

```python
  human = False
  print("Are you a human:",human)
```

#### Multiple assignment

- **Multiple assignment are allows us to assign multiple variables at the same time in one line of code**

```python
name, age, joker = "Ahmed", 21, True
print(f"Name: {name}\nAge: {age}\nAre you joker: {joker}")  # \n = new line
```

---

### String methods

#### len()

- **Get the length of variable or anything**

```python
   name = "ahmed"
   print(len(name))
```

#### find()

- **Get the location of character, and it's start with 0 not 1**

```python
   name = "ahmed"
   print(len(name))
```

#### capitalize()

- **It is make variable capitalized**

```python
   name = "ahmed"
   print(name.capitalize())
```

#### upper() & lower()

- **The first make all characters CAPITALISE and the second make them small letter**

```python
   name = "ahmed"
   print(name.upper())
   print(name.lower())
```

#### isdigit()

- **Check if it is a number or not**

```python
   name = "ahmed"
   print(name.isdigit())

```

#### isalpha()

- **Check if it is an alphabet or not**

```python
   name = "ahmed"
   print(name.isalpha())
```

#### count()

- **Count how many characters in the variable**

```python
   name = "ahmed"
   print(name.count("e"))
```

#### replace("x","y")

- **Replace character "x" by "y"**

```python
   name = "ahmed"
   print(name.replace("d","dd"))
```

---

### User input

- **we use input() to get input from user in python**
  ```python
  name = input("What is your name?: ")
  # it is look like str(input())
  print(f"Hello {name}")
  ```
- **what about get integer from user just int?**
  - for that we must use type casting
    ```python
    age = int(input("what is your age ?: "))
    age +=5
    print(f"After 5 years you will have {age}")
    ```

### Math functions

- First we should import math functions by using "import math"
