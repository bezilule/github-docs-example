# Wrtiting Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, and share** code. 
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')
  
```
class Person
  # Constructor
  def initialize(name = "Unknown")
    @name = name  # instance variable
  end

  # Setter method for name
  def name=(name)
    @name = name
  end

  # Getter method for name
  def name
    @name
  end

  # Method to greet the person
  def greet
    puts "Hello, #{@name}!"
  end
end

```

- When you can you should attempt to apply syntax highlighting to your codeblocks.

  ```ruby
  class Person
  # Constructor
  def initialize(name = "Unknown")
    @name = name  # instance variable
  end

  # Setter method for name
  def name=(name)
    @name = name
  end

  # Getter method for name
  def name
    @name
  end

  # Method to greet the person
  def greet
    puts "Hello, #{@name}!"
  end
  
  ```

![Fall Image](https://github.com/bezilule/github-docs-example/assets/88293035/0185a43d-acee-4548-8732-f05c459cdea3)

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
NameError: undefined local variable or method `some_undefined_variable' for main:Object
```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use GitHub Flavored Markdown Task Lists

GitHub extends Markdown to have a list where you can check off items. [<sup> [1] <sup>](#external-references)

- [x] Finish Step 1
- [] Finish Step 2
- [x] Finish Step 3

## Step 4 Use Emojis (Optional)

GitHub Flavored Markdown (GFM) Supports emoji shortcodes. Here are some examples:

| Name | Short | Emoji |
| --- | --- | ---|
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | :cloud_with_lightning | 🌩️ |

## Step 5 - how to create a table

You can use the following format to create tables:

```md
| Name | Short | Emoji |
| --- | --- | ---|
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | :cloud_with_lightning | 🌩️ |
```
GitHub extends the functionality of Markdown tables to provide more alignment and table cell formatting options.
[<sup> [2] <sup>](#external-references)

## External References 

- [GitHub Flavored Markdown Spec](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text) 

- [GitHub Flavored Markdown Spec](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists) <sup> [1] <sup>

- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)

- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup> [2] <sup>







