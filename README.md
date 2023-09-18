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


![Coffee Mug](https://github.com/bezilule/github-docs-example/assets/88293035/507ef33b-1986-42dd-ad45-0f4b2dfc31ec)











