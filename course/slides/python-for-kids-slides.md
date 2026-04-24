---
marp: true
theme: default
paginate: true
backgroundColor: "#FFF8E7"
color: "#333"
style: |
  section {
    font-size: 30px;
  }
  h1 {
    color: #2E86AB;
    font-size: 60px;
  }
  h2 {
    color: #E63946;
    font-size: 48px;
  }
  code {
    background: #FFE5B4;
    padding: 4px 8px;
    border-radius: 6px;
  }
  .huge {
    font-size: 120px;
    text-align: center;
  }
  .big {
    font-size: 70px;
    text-align: center;
  }
---

# 🐍 Python for Kids

## A Fun Coding Adventure! ✨

**Ages 5–10**

---

# 👋 Hi, Little Coder!

<div class="huge">🧒💻🐍</div>

Let's learn **Python** together!

---

# 🤔 What is Python?

A **special language** to talk to computers

<div class="huge">🗣️ ➡️ 💻</div>

---

# 🎁 What Can Python Do?

- 🎮 Make games
- 🎨 Draw pictures
- 🤖 Make chatbots
- 🎲 Roll dice
- 🌐 Build websites

---

# 🌟 Famous Python Apps

<div class="big">📺 🎵 📸</div>

YouTube • Spotify • Instagram

**All use Python!**

---

# 💻 Where Do We Code?

Free websites — no install! 🎉

- 🌐 **trinket.io**
- 🌐 **replit.com**

---

# 🥳 Your First Code!

```python
print("Hello, world!")
```

This is how we **say hello** to the computer!

---

# 📢 What Does `print` Do?

`print` = **Megaphone** 🎤

Whatever you put in `( )` shows on screen!

```python
print("I love pizza! 🍕")
```

---

# 📦 Variables = Magic Boxes

<div class="huge">📦</div>

A box that holds stuff with a name!

---

# 📦 Making a Box

```python
name = "Riya"
age = 7
```

- Box **`name`** holds "Riya"
- Box **`age`** holds 7

---

# 📦 Using the Box

```python
name = "Riya"
print(name)
```

Shows: **Riya** 🎉

---

# 🎨 Data Types

4 kinds of information:

| Type | Example |
|---|---|
| 🔢 Number | `7` |
| 🔸 Decimal | `3.5` |
| 📝 Text | `"hello"` |
| ✅ Yes/No | `True` |

---

# 📝 Strings = Words

Words must be in **quotes** `" "`

```python
name = "Riya"    # ✅ good
name = Riya      # ❌ bad!
```

---

# 💬 Talking to the Computer

- `print()` — computer **tells** you 📢
- `input()` — computer **asks** you 🎤

---

# 🎤 Asking Questions

```python
name = input("Your name? ")
print("Hi, " + name + "!")
```

The computer has a chat with you! 💬

---

# 🧮 Math Time!

Python is a **super calculator** 🧮

| Sign | Meaning |
|---|---|
| `+` | Add |
| `-` | Minus |
| `*` | Times |
| `/` | Divide |

---

# 🍕 Pizza Math

```python
slices = 8
friends = 4
print(slices / friends)
```

Answer: **2 slices each!** 🍕

---

# 🤔 Making Choices

<div class="huge">☔ or 😎?</div>

Let the computer choose!

---

# ☔ If It Rains...

```python
if weather == "rain":
    print("Take umbrella! ☔")
else:
    print("Sunglasses! 😎")
```

---

# 🎯 if / elif / else

- `if` — check this first
- `elif` — else check this
- `else` — otherwise do this

**More choices = more `elif`!**

---

# 🔁 Loops = Do Again!

<div class="huge">🪥🪥🪥🪥</div>

Brush every tooth? Use a loop!

---

# 🔁 For Loop

```python
for tooth in range(4):
    print("Brush! 🪥")
```

Prints "Brush!" 4 times!

---

# 🐑 While Loop

```python
sheep = 1
while sheep <= 5:
    print(sheep, "🐑")
    sheep = sheep + 1
```

Count sheep to fall asleep! 😴

---

# 🎒 Lists = School Bag

<div class="huge">🎒</div>

Holds many things at once!

---

# 🎒 Making a List

```python
bag = ["book", "pencil", "lunchbox"]
print(bag[0])   # book
```

Lists start at **0**, not 1!

---

# ➕ Adding to List

```python
bag.append("eraser")
```

Puts "eraser" at the end! ✨

---

# ➖ Removing from List

```python
bag.remove("pencil")
```

Takes "pencil" out! 🗑️

---

# 📞 Dictionary = Phonebook

```python
phonebook = {
    "Mom": "9999-11-22",
    "Dad": "9999-33-44"
}
```

Each **name** has a **number**!

---

# 🔑 Keys & Values

- 🔑 **Key** = Mom's name
- 📱 **Value** = Mom's number

```python
print(phonebook["Mom"])
```

---

# ✨ Functions = Magic Spells

<div class="huge">🪄</div>

Write once, use many times!

---

# ✨ Making a Spell

```python
def say_hi():
    print("Hi! 👋")

say_hi()
say_hi()
```

Say hi 2 times! 🎉

---

# 🎁 Functions with Gifts

```python
def greet(name):
    print("Hi", name, "!")

greet("Riya")
greet("Arjun")
```

---

# 🎮 Time to Build Games!

<div class="huge">🎲❓🤖</div>

Dice • Quiz • Chatbot

---

# 🎲 Dice Roller

```python
import random
roll = random.randint(1, 6)
print("🎲", roll)
```

Random number from **1 to 6**!

---

# ❓ Quiz Game

```python
ans = input("5 + 3? ")
if ans == "8":
    print("✅ Correct!")
else:
    print("❌ Wrong!")
```

---

# 🤖 Chatbot

```python
msg = input("You: ")
if "pizza" in msg:
    print("🤖 Yum! 🍕")
```

Chatbot replies based on your words!

---

# 🎉 You Did It!

<div class="huge">🏆🎊🌟</div>

You are now a **real coder!**

---

# 🚀 What's Next?

- 🎨 Turtle (draw with code)
- 🕹️ Pygame (real games)
- 🌐 Websites
- 🤖 Program robots!

---

# 💖 Remember...

<div class="big">Every coder started with</div>

```python
print("Hello!")
```

**Keep coding! Keep smiling!** 😊

---

# 🐍✨ Thank You! ✨🐍

## Happy Coding, Little Friend! 💖

<div class="huge">🎉</div>
