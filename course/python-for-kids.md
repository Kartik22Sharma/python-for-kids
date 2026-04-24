---
title: "🐍 Python for Kids"
subtitle: "A Fun Adventure for Ages 5–10"
author: "Your Python Teacher"
date: "2026"
toc: true
toc-depth: 2
---

\newpage

# Hi there, little coder! 👋

Welcome to the world of **Python**! 🐍

Python is not a snake in this book — it's a special way to **talk to computers** and tell them what to do. Pretty cool, right? 😎

In this book, you will learn how to:

- 🎨 Make the computer draw
- 🎮 Build little games
- 🤖 Make a chatbot that talks to you
- 🎲 Roll a pretend dice

Let's start our adventure! 🚀

\newpage

# Chapter 1: 🐍 Welcome to Python

## What is Python?

Imagine you have a **robot helper** at home. 🤖

You want the robot to bring you a cookie 🍪. But the robot only understands one special language. If you speak that language, the robot will do whatever you ask!

**Python is that special language** — but for computers, not robots.

## Why Python is awesome

- 🟢 It is **easy** to learn
- 🟢 The words look like English
- 🟢 Grown-ups use it to make **YouTube, Instagram, and Netflix** work!
- 🟢 You can make fun stuff with it

## What will we make?

By the end of this book, you will make:

- 🎲 A dice roller
- ❓ A quiz game
- 🤖 A chatbot

> 💡 **Tip:** Don't worry if something feels hard at first. Every coder started as a beginner. Even the people who made Google! 🌟

\newpage

# Chapter 2: 💻 Getting Ready

## Where do we write Python?

We need a special place to write our Python code. Think of it like a **notebook just for computer instructions** 📓.

### The easy way (no install!)

Ask a grown-up to open one of these websites with you:

- 🌐 **https://trinket.io**
- 🌐 **https://replit.com**

Both are free and work in your browser! 🎉

## Your first Python code 🥳

Type this:

```python
print("Hello, world!")
```

Press the **Run** button ▶️

You should see:

```
Hello, world!
```

🎉 **Woohoo! You just wrote your first computer program!**

## What does `print` do?

`print` is like shouting through a megaphone 📢. Whatever you put inside the `( )` will show up on the screen.

Try this:

```python
print("I love pizza!")
print("My cat is funny 🐱")
```

## 🧑‍💻 Try it yourself

Change the words inside `print(" ")` to say:

1. Your name
2. Your favorite food
3. Your favorite animal

> ⚠️ **Watch out:** Don't forget the quotes `" "` around your words!

### Answer example:

```python
print("My name is Riya")
print("I love mangoes")
print("My favorite animal is a panda")
```

\newpage

# Chapter 3: 📦 Variables — The Magic Boxes

## What is a variable?

A **variable** is like a **magic box** 📦. You can put stuff inside it and give the box a name!

Imagine you have a box labeled **"toys"**. You put a teddy bear inside. Later, when you say "toys", everyone knows you mean the teddy bear.

## Making a variable

```python
name = "Riya"
age = 7
```

Here we made two boxes:

- 📦 A box called `name` with the word **Riya** inside
- 📦 A box called `age` with the number **7** inside

## Using a variable

```python
name = "Riya"
print(name)
```

The computer will show:

```
Riya
```

It looked inside the box and showed us what was there! 🎁

## Changing what's inside

You can change what's in the box anytime:

```python
age = 7
print(age)
age = 8   # happy birthday! 🎂
print(age)
```

Output:

```
7
8
```

## 💡 Rules for box names

- ✅ Use simple words: `name`, `age`, `color`
- ✅ No spaces — use `_` instead: `my_dog`
- ❌ Don't start with a number: `1name` is bad
- ❌ Don't use spaces: `my name` is bad

## 🧑‍💻 Try it yourself

Make three variables about you:

1. Your name
2. Your age
3. Your favorite color

Then `print` them all!

### Answer:

```python
name = "Arjun"
age = 8
color = "blue"
print(name)
print(age)
print(color)
```

\newpage

# Chapter 4: 🎨 Data Types

## What is a data type?

Just like in school we have different subjects (Math, English, Art), computers have different **types of information**.

The 4 main types are:

| Type | What it is | Example |
|---|---|---|
| 🔢 `int` | A whole number | `7`, `100`, `-3` |
| 🔸 `float` | A number with a dot | `3.5`, `1.14` |
| 📝 `str` | Words (a "string") | `"hello"`, `"cat"` |
| ✅ `bool` | True or False | `True`, `False` |

## Examples

```python
age = 7                  # int (whole number)
height = 1.25            # float (number with dot)
name = "Riya"            # str (words in quotes)
is_happy = True          # bool (yes/no)
```

## How to check the type

Python can tell you the type!

```python
age = 7
print(type(age))
```

You will see:

```
<class 'int'>
```

That means `age` is an **int** (a whole number). 🎯

## 📝 Strings are special

Strings are words. They must always be in quotes!

```python
greeting = "Hello"     # ✅ good
greeting = Hello       # ❌ BAD — no quotes
```

You can add strings together:

```python
first = "Peanut"
second = "Butter"
print(first + " " + second)
```

Output:

```
Peanut Butter
```

🥜 Yum!

## 🧑‍💻 Try it yourself

1. Make a variable with your name (string)
2. Make a variable with your age (int)
3. Make a variable saying if you like ice cream (bool)
4. Print them all

### Answer:

```python
name = "Meera"
age = 6
likes_ice_cream = True
print(name)
print(age)
print(likes_ice_cream)
```

\newpage

# Chapter 5: 💬 Input & Output — Talking to the Computer

## Two magic words

- `print()` — the computer **tells you** something 📢
- `input()` — the computer **asks you** something 🎤

## Asking a question

```python
name = input("What is your name? ")
print("Hello, " + name + "!")
```

When you run this, the computer asks:

```
What is your name?
```

You type **Riya** and press Enter.

Then it says:

```
Hello, Riya!
```

🎉 You just had a conversation with a computer!

## How it works

1. `input("What is your name? ")` → computer asks the question
2. Whatever you type gets put in the box called `name`
3. `print()` uses the box to say hi

## A bigger example

```python
name = input("What is your name? ")
food = input("What is your favorite food? ")
print("Hi " + name + "! I also love " + food + "!")
```

## ⚠️ Watch out: input is always a string!

Even if you type `7`, the computer sees it as the word `"7"`, not the number 7.

To turn it into a number, wrap it with `int()`:

```python
age = input("How old are you? ")
age = int(age)           # turn the word into a real number
print("Next year you will be", age + 1)
```

## 🧑‍💻 Try it yourself

Make a program that:

1. Asks for your name
2. Asks for your favorite animal
3. Says: "Hi [name]! [animal] is a great animal!"

### Answer:

```python
name = input("Name? ")
animal = input("Favorite animal? ")
print("Hi " + name + "! " + animal + " is a great animal!")
```

\newpage

# Chapter 6: 🧮 Math — The Super Calculator

Python is an **amazing calculator**! 🧮

## The basic math signs

| Sign | What it does | Example | Answer |
|---|---|---|---|
| `+` | Add | `2 + 3` | `5` |
| `-` | Minus | `7 - 4` | `3` |
| `*` | Times | `3 * 4` | `12` |
| `/` | Divide | `10 / 2` | `5.0` |
| `//` | Divide (no decimal) | `10 // 3` | `3` |
| `%` | Leftover | `10 % 3` | `1` |
| `**` | Power | `2 ** 3` | `8` |

## 🍕 Pizza example

Imagine you have **8 slices of pizza** and **4 friends**.

```python
slices = 8
friends = 4
each = slices / friends
print("Each friend gets", each, "slices")
```

Output:

```
Each friend gets 2.0 slices
```

🍕 Yum! Everyone is happy! 😋

## 🎂 Birthday example

You have 12 cupcakes. You give 3 to your sister.

```python
cupcakes = 12
cupcakes = cupcakes - 3
print("I have", cupcakes, "cupcakes left 🧁")
```

Output:

```
I have 9 cupcakes left 🧁
```

## 🧑‍💻 Try it yourself

1. If you have 20 candies and share with 5 friends, how many does each get?
2. If a chocolate bar has 10 pieces and you eat 3, how many are left?

### Answer:

```python
# 1
print(20 / 5)     # 4.0

# 2
print(10 - 3)     # 7
```

\newpage

# Chapter 7: 🤔 Making Choices — `if`, `elif`, `else`

## Choices, choices!

Every day you make choices:

- ☔ Is it raining? → Take an umbrella
- 😎 Is it sunny? → Wear sunglasses
- 🧥 Is it cold? → Wear a jacket

Computers can make choices too using `if`!

## The `if` word

```python
weather = "rain"

if weather == "rain":
    print("Take an umbrella! ☔")
```

> 💡 **Tip:** Notice the two `=` signs (`==`)? One `=` means "put this in the box". Two `==` means "is this equal to?"

## Adding an `else`

```python
weather = "sun"

if weather == "rain":
    print("Take an umbrella! ☔")
else:
    print("Wear sunglasses! 😎")
```

`else` means "if the first thing is NOT true, do this instead".

## Adding `elif` (more choices!)

`elif` means "else if" — another choice to check.

```python
weather = "snow"

if weather == "rain":
    print("Take an umbrella! ☔")
elif weather == "snow":
    print("Wear a big coat! 🧥❄️")
elif weather == "sun":
    print("Wear sunglasses! 😎")
else:
    print("I don't know this weather 🤔")
```

## ⚠️ Watch out: Indentation!

The line **inside** the `if` must be pushed to the right. Use 4 spaces or press Tab.

```python
if age >= 6:
    print("You can read this book!")   # ← pushed right
```

## 🧑‍💻 Try it yourself

Ask the user their age. Say:

- "You are a baby!" if under 3
- "You are a kid!" if 3 to 12
- "You are a teen!" if 13 to 19
- "You are a grown-up!" if older

### Answer:

```python
age = int(input("How old are you? "))

if age < 3:
    print("You are a baby! 👶")
elif age <= 12:
    print("You are a kid! 🧒")
elif age <= 19:
    print("You are a teen!")
else:
    print("You are a grown-up!")
```

\newpage

# Chapter 8: 🔁 Loops — Doing Things Again and Again

## What is a loop?

A **loop** makes the computer do the same thing many times.

Think about brushing your teeth 🪥:

1. Brush tooth 1
2. Brush tooth 2
3. Brush tooth 3
4. ... and so on!

Instead of writing the same thing 20 times, we use a **loop**!

## The `for` loop

```python
for tooth in range(4):
    print("Brush tooth number", tooth + 1, "🪥")
```

Output:

```
Brush tooth number 1 🪥
Brush tooth number 2 🪥
Brush tooth number 3 🪥
Brush tooth number 4 🪥
```

### What is `range(4)`?

`range(4)` gives us the numbers 0, 1, 2, 3 (four numbers, starting from 0).

## The `while` loop

`while` keeps going **as long as** something is true.

```python
sheep = 1
while sheep <= 5:
    print(sheep, "sheep 🐑")
    sheep = sheep + 1
```

Output:

```
1 sheep 🐑
2 sheep 🐑
3 sheep 🐑
4 sheep 🐑
5 sheep 🐑
```

## ⚠️ Watch out: forever loops!

If you forget to change the number, the loop runs FOREVER! 😱

```python
# BAD! This will never stop!
sheep = 1
while sheep <= 5:
    print(sheep)
    # forgot to add +1
```

Always make sure the loop has a way to stop!

## 🧑‍💻 Try it yourself

1. Use a `for` loop to count from 1 to 10.
2. Use a `while` loop to say "I love Python" 3 times.

### Answer:

```python
# 1
for i in range(1, 11):
    print(i)

# 2
count = 0
while count < 3:
    print("I love Python! 🐍")
    count = count + 1
```

\newpage

# Chapter 9: 🎒 Lists — Your School Bag

## What is a list?

A **list** is like your **school bag** 🎒. It can hold many things at once!

```python
bag = ["book", "pencil", "lunchbox", "water bottle"]
print(bag)
```

## Getting one thing from the list

Lists use **numbers** to find things. But watch out — **lists start at 0**, not 1!

```python
bag = ["book", "pencil", "lunchbox", "water bottle"]
print(bag[0])   # book
print(bag[1])   # pencil
print(bag[2])   # lunchbox
```

| Position | Item |
|---|---|
| 0 | book 📖 |
| 1 | pencil ✏️ |
| 2 | lunchbox 🍱 |
| 3 | water bottle 💧 |

## Adding things to the list

```python
bag = ["book", "pencil"]
bag.append("eraser")
print(bag)
```

Output:

```
['book', 'pencil', 'eraser']
```

## Removing things

```python
bag = ["book", "pencil", "eraser"]
bag.remove("pencil")
print(bag)
```

Output:

```
['book', 'eraser']
```

## How many things are in the list?

```python
bag = ["book", "pencil", "eraser"]
print(len(bag))   # 3
```

`len` means "length" — how many items are inside.

## Looping through a list

```python
fruits = ["apple 🍎", "banana 🍌", "mango 🥭"]

for fruit in fruits:
    print("I love", fruit)
```

## 🧑‍💻 Try it yourself

1. Make a list of 5 animals
2. Print the second animal
3. Add a new animal to the end
4. Loop through and print each animal

### Answer:

```python
animals = ["cat", "dog", "fish", "cow", "duck"]
print(animals[1])          # dog
animals.append("rabbit")
for a in animals:
    print(a)
```

\newpage

# Chapter 10: 📞 Dictionaries — Your Phonebook

## What is a dictionary?

A **dictionary** is like a **tiny phonebook** 📞. For every name, you have a phone number.

```python
phonebook = {
    "Mom": "9999-11-22",
    "Dad": "9999-33-44",
    "Best Friend": "9999-55-66"
}
```

- The **name** is called a **key** 🔑
- The **phone number** is called a **value** 📱

## Looking up a number

```python
phonebook = {"Mom": "9999-11-22", "Dad": "9999-33-44"}
print(phonebook["Mom"])
```

Output:

```
9999-11-22
```

## Adding a new person

```python
phonebook["Grandma"] = "8888-22-33"
print(phonebook)
```

## Removing a person

```python
del phonebook["Dad"]
```

## A fun example: Favorite colors

```python
favorite_color = {
    "Riya": "pink 💗",
    "Arjun": "blue 💙",
    "Meera": "green 💚"
}

name = input("Whose color? ")
print(name + "'s favorite color is", favorite_color[name])
```

## 🧑‍💻 Try it yourself

Make a dictionary with 3 of your friends and their favorite foods. Print your best friend's food!

### Answer:

```python
foods = {
    "Ankit": "pizza 🍕",
    "Priya": "pasta 🍝",
    "Sam": "ice cream 🍦"
}
print("Priya loves", foods["Priya"])
```

\newpage

# Chapter 11: ✨ Functions — Magic Spells

## What is a function?

A **function** is like a **magic spell** 🪄. You create it once, and then you can use it again and again!

Think of a sandwich recipe 🥪. You write the recipe **once**. Then you can make 100 sandwiches without writing it again!

## Making a function

We use the word `def` (short for "define", meaning "make").

```python
def say_hello():
    print("Hello, friend! 👋")
```

This made a magic spell called `say_hello`. But it won't run unless we **call** it:

```python
say_hello()
say_hello()
say_hello()
```

Output:

```
Hello, friend! 👋
Hello, friend! 👋
Hello, friend! 👋
```

## Functions with inputs (parameters)

We can send stuff to our function using `( )`.

```python
def greet(name):
    print("Hi", name, "! 🎉")

greet("Riya")
greet("Arjun")
greet("Meera")
```

Output:

```
Hi Riya ! 🎉
Hi Arjun ! 🎉
Hi Meera ! 🎉
```

## Functions that give something back (return)

Functions can do math and give back an answer.

```python
def add(a, b):
    return a + b

result = add(3, 5)
print(result)       # 8
```

## 🎂 Real example: Birthday card

```python
def birthday_card(name, age):
    print("🎂 Happy Birthday", name + "!")
    print("You are now", age, "years old! 🎉")

birthday_card("Riya", 8)
birthday_card("Arjun", 7)
```

## 🧑‍💻 Try it yourself

Make a function called `pizza` that takes a number and prints "I want N slices of pizza 🍕"

### Answer:

```python
def pizza(slices):
    print("I want", slices, "slices of pizza 🍕")

pizza(3)
pizza(8)
```

\newpage

# Chapter 12: 🎮 Mini Projects — Let's Build!

Time to build real things! 🛠️

## Project 1: 🎲 Dice Roller

A dice has 6 sides, showing 1 to 6. Let's make a computer dice!

```python
import random

print("🎲 Let's roll a dice!")
input("Press Enter to roll... ")
number = random.randint(1, 6)
print("You got:", number)
```

### How it works

- `import random` → load Python's random tool
- `random.randint(1, 6)` → pick a random number between 1 and 6
- `input()` → wait for the kid to press Enter

### Make it better! 🚀

Let the kid roll many times:

```python
import random

while True:
    answer = input("Roll again? (yes/no) ")
    if answer == "no":
        print("Bye! 👋")
        break
    print("🎲", random.randint(1, 6))
```

---

## Project 2: ❓ Quiz Game

```python
score = 0

print("🎉 Welcome to the Quiz! 🎉")

# Question 1
a1 = input("1) What color is the sun? ")
if a1 == "yellow":
    print("✅ Correct!")
    score = score + 1
else:
    print("❌ Wrong. It's yellow.")

# Question 2
a2 = input("2) How many legs does a spider have? ")
if a2 == "8":
    print("✅ Correct!")
    score = score + 1
else:
    print("❌ Wrong. It's 8.")

# Question 3
a3 = input("3) What is 5 + 3? ")
if a3 == "8":
    print("✅ Correct!")
    score = score + 1
else:
    print("❌ Wrong. It's 8.")

print("🏆 Your score is:", score, "out of 3")
```

### Make it better! 🚀

Add your own questions, or give a fun message based on score:

```python
if score == 3:
    print("🌟 Perfect! You're a genius!")
elif score >= 1:
    print("😊 Good job! Try again!")
else:
    print("💪 Don't give up! Try once more!")
```

---

## Project 3: 🤖 Emoji Chatbot

```python
print("🤖 Hello! I am EmojiBot. Talk to me!")
print("(type 'bye' to stop)")

while True:
    message = input("You: ")

    if message == "bye":
        print("🤖: Goodbye! 👋")
        break
    elif "hello" in message or "hi" in message:
        print("🤖: Hi there! 😄")
    elif "pizza" in message:
        print("🤖: Yum! I love pizza! 🍕")
    elif "dog" in message:
        print("🤖: Woof woof! 🐶")
    elif "cat" in message:
        print("🤖: Meow! 🐱")
    elif "happy" in message:
        print("🤖: Yay! Me too! 🎉")
    elif "sad" in message:
        print("🤖: Oh no 😢. Here's a hug! 🤗")
    else:
        print("🤖: Tell me more! 🤔")
```

### How it works

- `while True:` → keep talking forever (until "bye")
- `"pizza" in message` → checks if the word "pizza" is inside what the user typed
- Different replies for different words!

### Make it better! 🚀

- Add more keywords (soccer, school, mom, dad)
- Add emojis that match the mood
- Add your friend's name to make it personal!

\newpage

# Chapter 13: 🚀 What's Next?

🎉 **Congratulations, little coder!** 🎉

You now know:

- ✅ How to `print` words
- ✅ How to use variables 📦
- ✅ Different data types 🎨
- ✅ How to ask questions with `input` 💬
- ✅ How to do math 🧮
- ✅ How to make choices with `if` 🤔
- ✅ How to loop 🔁
- ✅ Lists 🎒 and dictionaries 📞
- ✅ Functions ✨
- ✅ How to build games and chatbots! 🎮🤖

## What can you try next?

- 🎨 **Turtle graphics** — draw pictures with Python! (search "python turtle")
- 🕹️ **Pygame** — make real games
- 🌐 **Websites** — make your own web pages
- 🤖 **Robots** — program real robots!

## 📖 Glossary (Tricky Words, Explained Simply)

| Word | What it means |
|---|---|
| **Variable** | A box 📦 that holds something |
| **String** | Words inside quotes |
| **Integer (int)** | A whole number |
| **Float** | A number with a dot |
| **Boolean (bool)** | True or False |
| **Function** | A magic spell you can use again and again |
| **Loop** | Doing something many times |
| **List** | A school bag holding many things |
| **Dictionary** | A phonebook with keys and values |
| **Input** | When the computer asks you something |
| **Output** | When the computer shows you something |
| **Import** | Borrowing a tool from Python's toolbox |
| **Parameter** | Stuff you give to a function |
| **Return** | Something a function gives back |
| **Run** | Telling the computer to do your code |

## 💖 Remember...

Every great coder started by writing `print("Hello")` — just like you!

Keep practicing, keep having fun, and **never stop asking "What if I try this?"** 🌟

Happy coding! 🐍✨

— Your Python Teacher
