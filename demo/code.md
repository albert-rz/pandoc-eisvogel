# Code blocks

As seen in \ref{code:python_ex}

```{.python .numberLines #code:python_ex caption="Python function to add two numbers"}
import datetime

# Ask for the user's name
name = input("What's your name? ")

# Greet the user
print(f"Hello, {name}! Nice to meet you.")

# Get the current time
now = datetime.datetime.now()
print(f"The current time is {now.strftime('%Y-%m-%d %H:%M:%S')}.")

# Simple farewell message
print("Have a great day!")
```