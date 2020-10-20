hello-world
===========

Learn to code in [Python](https://www.python.org/) in 10 minutes. 🚀

Requirements:

* 💻 A computer with a web browser.
* 🍺 A beer! (optional)

## The Chef in Making (🥣 + 🧂 + 🥄 + 🔥 = 💥)

#### 🍞 The Editor

* Open [repl.it](https://repl.it/) on your browser, click **<> Start coding**, choose **Python** from the **Language** dropdown, and click **Create repl**.
* Click **Run ►** to run a program. Click **Stop ■** to stop a running program.

![repl.it](repl.it.gif)

#### 🥩 Hello World

A *hello world* program is the first thing every programmer learns.

```python
print('hello world')
```

#### 🧀 Variables

```python
food = 'cheeseburger'
print(food)
```

If you are feeling adventurous, read on...

## The Cheeseburger (🍞 + 🥩 + 🧀 = 🍔)

We will learn how to write a simple program that tells you the price of a cheeseburger.

```python
food = 'cheeseburger'
price = 15

print('Charge $' + str(price) + ' for ' + food)
```

What we've learned:
* A `print()` statement, used to display output to the user.
* A *variable*, used to store data by simply assigning a value using `=`.

If you are feeling unstoppable, read on...

## The Quarter Pounder (🍞 + 🧀 + 🥩 + 🧀 + 🍅 + 🥬 + 🧅 = 🍔)

We will learn how to write a simple program to score free food!

```python
food = 'cheeseburger'

cost = 15
tax = 3
price = cost + tax

time = 800

if time > 730:
  print('Dinner is free! Thank Travis. 🥳')
else:
  print('Your + ' food + 'costs $' + str(price) + '. Pay up. 😔')
```

What we've learned:
* An *operator*, like `+`, used to performed arithmetic operations on variables.
* An `if...else` construct, used to execute different operations based on a condition.

If you are feeling relentless, read on...

## The Big Mac (🍞 + 🥬 + 🧀 + 🥩 + 🍞 + 🧀 + 🥬 + 🥩 = 🍔)

We will learn how to write a simple program that let's the user pick an item from a menu.

```python
menu = """
  Choose item:
  1 - cheeseburger
  2 - taco
  3 - crepe

  0 - exit
  """

food_1_cost = 15
food_2_cost = 5
food_3_cost = 11

choice = None
while choice != 0:
  choice = int(input(menu))

  if choice == 1:
    print('Charge $' + str(food_1_cost) + ' for cheeseburger')
  elif choice == 2:
    print('Charge $' + str(food_2_cost) + ' for taco')
  elif choice == 3:
    print('Charge $' + str(food_3_cost) + ' for crepe')
  else:
    print('No food for you.')
```

What we've learned:
* A `while` construct, used to execute some operation repeatedly.
* An `input()` statement, is used to receive an input from the user.
