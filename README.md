# Python Classes and Objects

A comprehensive guide to learning Object-Oriented Programming (OOP) in Python.

## Topics Covered

- Classes and Objects
- Constructor (`__init__`) method
- Instance attributes and methods  
- Class attributes and methods
- Inheritance and Polymorphism
- Encapsulation
- Method overriding
- Properties and decorators

## Project Structure

```
python_classes/
├── basic_class.py        # Simple class examples
├── inheritance.py        # Inheritance demonstrations
├── polymorphism.py      # Polymorphic behavior
├── encapsulation.py     # Private/protected members
└── properties.py        # Property decorators
```

## Getting Started

1. Clone this repository:
```bash
git clone https://github.com/yourusername/python_classes.git
```

2. Navigate to the project directory:
```bash
cd python_classes
```

3. Run any example:
```bash
python basic_class.py
```

## Examples

### Basic Class
```python
class Dog:
    def __init__(self, name):
        self.name = name
    
    def bark(self):
        return f"{self.name} says woof!"
```

## Learning Resources

- Python Official Documentation on [Classes](https://docs.python.org/3/tutorial/classes.html)
- Real Python's [OOP Tutorial](https://realpython.com/python3-object-oriented-programming/)

## Contributing

Feel free to contribute examples, fixes, or improvements through pull requests.

## License

MIT License - feel free to use this code for learning purposes.