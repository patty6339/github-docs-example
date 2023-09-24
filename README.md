# Writing Good Documentation

Documentations are important as they can help other engineers understand how your app works. 
## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code. A good _Cloud Engineer_ uses Codeblocks whenever possible.

A good codeblock allows others to copy and paste the code to replicate or research issues <sup>[1]</sup>

```
# Define the Person class
class Person:
    # Constructor to initialize the person's name
    def __init__(self, name):
        self.name = name
    
    # Method to print a greeting
    def greet(self):
        print(f"Hello, my name is {self.name}!")

# Create an instance of the Person class
person1 = Person("John Doe")

# Call the greet() method on the instance
person1.greet()

```

Always **Color Code** your codeblocks whenever possible by adding the name of the programming language at the end of the first backticks as shown below:

```python
# Define the Person class
class Person:
    # Constructor to initialize the person's name
    def __init__(self, name):
        self.name = name
    
    # Method to print a greeting
    def greet(self):
        print(f"Hello, my name is {self.name}!")

# Create an instance of the Person class
person1 = Person("John Doe")

# Call the greet() method on the instance
person1.greet()

```

**Note:** Always use backticks when adding codeblocks to a markup file and **never** use single quotations, the image below shows where the backticks can be found on your keyboard. <sup>[2]</sup> **Remember**- the location of the backtick key can vary depending on your [keyboard layout](https://kbd-intl.narod.ru/english/layouts). A _screenshot_ of a backtick key from an English Standard keyboard is shown below:

![ezgif com-webp-to-jpg](https://github.com/patty6339/github-docs-example/assets/21007127/d3e01af1-b83c-4592-9471-14fa414ab604)

## Adding an error codeblock to the markdown file ##
```bash
Traceback (most recent call last):
  File "<stdin>", line 2, in <module>
NameError: name 'undefined_variable' is not defined
```
> Including the programming languages after the first backticks helps to color code your codeblock

## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items.

- [x] Finish Step 1
- [x] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use emojis (Optional)
Github Flavored Markup (GFM) supports emoji shortcodes. Here are some examples:

| Name | Shortcode | Emoji
| --- | --- | ---
|Cloud |`:cloud:`|:cloud:
|Cloud with Lightning | `:cloud_with_lightning:` | :cloud_with_lightning:


## References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) <sup>[1]</sup>
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) <sup>[2]</sup>
- [GFM-Emojis Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

