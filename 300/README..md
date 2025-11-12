# 300 - Learning Our Subject

Here’s your complete “LEGO blocks” reference for building code:

## 1. BUILDING BLOCKS (Code Structures)

### Data Containers

- **Variable**: Named storage for a single value
- **Constant**: Variable that can’t change (immutable)
- **Array**: Ordered collection of same-type items (fixed size in some languages)
- **List**: Dynamic collection (can grow/shrink)
- **Dictionary/Map/Hash**: Key-value pairs (like a real dictionary)
- **Set**: Collection of unique items (no duplicates)
- **Tuple**: Immutable ordered collection
- **Stack**: Last-In-First-Out (LIFO) collection
- **Queue**: First-In-First-Out (FIFO) collection
- **Struct/Record**: Lightweight data container (simpler than class)

### Code Organization Blocks

- **Function**: Reusable block of code (standalone)
- **Method**: Function inside a class
- **Procedure**: Function that doesn’t return a value
- **Constructor**: Special method to create objects
- **Destructor**: Special method to clean up objects (C++, not in Java/Python)
- **Class**: Blueprint for creating objects
- **Interface**: Contract defining what methods a class must have
- **Abstract Class**: Partial blueprint (can’t instantiate directly)
- **Module**: File containing related code
- **Package/Namespace**: Collection of related modules
- **Library**: Collection of reusable code

### Control Flow Blocks

- **Conditional/Branch**: Decision-making (`if`, `else`, `elif/else if`)
- **Switch/Case**: Multiple-choice selection
- **Loop**: Repeating code block
  - **For Loop**: Iterate a specific number of times
  - **While Loop**: Repeat while condition is true
  - **Do-While Loop**: Execute at least once, then repeat while true
  - **For-Each Loop**: Iterate over collection items
- **Break**: Exit a loop early
- **Continue**: Skip to next loop iteration
- **Return**: Exit function and optionally return value
- **Throw/Raise**: Trigger an error/exception
- **Try-Catch-Finally**: Handle errors gracefully

### Object-Oriented Blocks

- **Object/Instance**: Created from a class blueprint
- **Property/Attribute/Field**: Data stored in an object
- **Getter**: Method to retrieve a property value
- **Setter**: Method to modify a property value
- **Static Member**: Belongs to class, not individual objects
- **Instance Member**: Unique to each object

## 2. CONNECTORS (How Blocks Link)

### Operators

- **Assignment**: `=` (store value)
- **Arithmetic**: `+`, `-`, `*`, `/`, `%` (modulo), `**` (power)
- **Comparison**: `==`, `!=`, `<`, `>`, `<=`, `>=`
- **Logical**: `AND`, `OR`, `NOT` (or `&&`, `||`, `!`)
- **Bitwise**: `&`, `|`, `^`, `~`, `<<`, `>>` (work on binary)
- **Ternary/Conditional**: `condition ? true_value : false_value`
- **Membership**: `in`, `not in` (Python)
- **Identity**: `is`, `is not` (Python - checks if same object)
- **Increment/Decrement**: `++`, `--` (Java/C#, not Python)
- **Compound Assignment**: `+=`, `-=`, `*=`, `/=`

### Function/Method Parts

- **Parameter/Formal Parameter**: Variable in function definition
- **Argument/Actual Parameter**: Value passed when calling
- **Default Parameter**: Parameter with preset value
- **Keyword Argument**: Named parameter when calling
- **Variable Arguments**: `*args` (Python), `params` (C#), `...` (Java varargs)
- **Return Value**: What function gives back
- **Return Type**: Data type of return value
- **Void**: Returns nothing

## 3. DECORATORS/MODIFIERS (Block Properties)

### Access Control

- **Public**: Accessible everywhere
- **Private**: Only within same class
- **Protected**: Class and subclasses only
- **Internal/Package-Private**: Same module/package only

### Behavior Modifiers

- **Static**: Belongs to class, not instance
- **Final/Sealed**: Cannot be changed/overridden
- **Abstract**: Must be implemented by subclass
- **Virtual**: Can be overridden
- **Override**: Replaces parent class implementation
- **Const/Readonly**: Cannot be modified
- **Async**: Runs asynchronously (non-blocking)
- **Synchronized**: Thread-safe (only one thread at a time)

### Python-Specific Decorators

- **@staticmethod**: Method doesn’t need instance
- **@classmethod**: Method receives class as first argument
- **@property**: Makes method accessible like an attribute
- **@abstractmethod**: Must be implemented by subclass

## 4. DATA TYPES (Block Content Types)

### Primitive Types

- **Integer/Int**: Whole numbers
- **Float/Double**: Decimal numbers
- **Boolean/Bool**: True or False
- **Character/Char**: Single letter/symbol
- **String**: Text (sequence of characters)
- **Byte**: Small integer (0-255)

### Reference Types

- **Object**: Base type for all classes (Java, C#)
- **Null/None/nil**: Represents “no value”
- **Any/Dynamic**: Can be any type

### Special Types

- **Enum/Enumeration**: Named set of constants
- **Generic/Type Parameter**: Placeholder type (`List<T>`)
- **Optional**: May or may not contain a value
- **Pointer/Reference**: Memory address (C/C++)

## 5. SPECIAL CONCEPTS

### Object-Oriented Principles

- **Encapsulation**: Hiding internal details
- **Inheritance**: Child class gets parent features
- **Polymorphism**: Same interface, different implementations
- **Abstraction**: Simplifying complex reality
- **Composition**: Building complex objects from simple ones

### Code Reuse Patterns

- **Inheritance**: “Is-a” relationship
- **Composition**: “Has-a” relationship
- **Delegation**: Passing responsibility to another object
- **Mixin**: Reusable piece of behavior (Python)
- **Trait**: Reusable piece of behavior (Rust, PHP)

### Memory & Scope

- **Scope**: Where variable is accessible
  - **Global Scope**: Accessible everywhere
  - **Local Scope**: Only in function/block
  - **Class Scope**: Within class
- **Lifetime**: How long variable exists
- **Garbage Collection**: Automatic memory cleanup
- **Reference**: Points to object in memory
- **Value**: Actual data stored directly

### Error Handling

- **Exception**: Error object
- **Try Block**: Code that might fail
- **Catch/Except Block**: Handle specific errors
- **Finally Block**: Runs regardless of errors
- **Throw/Raise**: Create an error
- **Assert**: Check condition, fail if false

### Advanced Concepts

- **Lambda/Anonymous Function**: Function without name
- **Closure**: Function that remembers its environment
- **Callback**: Function passed as argument
- **Iterator**: Object that produces sequence of values
- **Generator**: Function that yields values lazily (Python)
- **Coroutine**: Function that can pause and resume
- **Recursion**: Function calling itself
- **Higher-Order Function**: Takes/returns functions

### Comments & Documentation

- **Single-line Comment**: `//` or `#`
- **Multi-line Comment**: `/* */` or `'''`
- **Docstring**: Function/class documentation (Python)
- **JavaDoc/XML Doc**: Structured documentation (Java/C#)

## 6. PROGRAM STRUCTURE

### File Organization

- **Import/Include/Using**: Bring in external code
- **Export/Public API**: Make code available to others
- **Main Function/Entry Point**: Where program starts
- **Header File**: Interface declaration (C/C++)
- **Implementation File**: Actual code (C/C++)

### Execution Flow

- **Compilation**: Source code → machine code
- **Interpretation**: Execute code line by line
- **Transpilation**: Source code → another language
- **Runtime**: When program is executing
- **Compile-time**: When code is being compiled

## LEGO BLOCK HIERARCHY

```
Program
├── Packages/Namespaces
│   ├── Modules/Files
│   │   ├── Classes
│   │   │   ├── Properties/Fields
│   │   │   ├── Constructors
│   │   │   └── Methods
│   │   │       ├── Parameters
│   │   │       ├── Local Variables
│   │   │       ├── Control Flow
│   │   │       │   ├── Conditionals
│   │   │       │   └── Loops
│   │   │       └── Return Statement
│   │   └── Functions (standalone)
│   └── Interfaces
└── Main Entry Point
```

## Quick Example with Labels

```python
# MODULE level

# IMPORT statement
from typing import List

# CLASS definition
class Calculator:
    # STATIC PROPERTY (class variable)
    version: str = "1.0"
    
    # CONSTRUCTOR
    def __init__(self, name: str):
        # INSTANCE PROPERTY (instance variable)
        self.name = name
    
    # INSTANCE METHOD
    def add(self, a: int, b: int) -> int:
        # PARAMETER: a, b
        # RETURN TYPE: int
        
        # LOCAL VARIABLE
        result = a + b
        
        # CONDITIONAL (if statement)
        if result > 100:
            # EXCEPTION (raise error)
            raise ValueError("Result too large")
        
        # RETURN STATEMENT
        return result
    
    # STATIC METHOD
    @staticmethod
    def multiply(numbers: List[int]) -> int:
        # LOCAL VARIABLE with initial value
        product = 1
        
        # FOR-EACH LOOP
        for num in numbers:
            # COMPOUND ASSIGNMENT OPERATOR
            product *= num
        
        return product

# FUNCTION (standalone, outside class)
def main():
    # OBJECT INSTANTIATION (creating instance)
    calc = Calculator("MyCalc")
    
    # METHOD CALL with ARGUMENTS
    sum_result = calc.add(5, 10)
    
    # FUNCTION CALL
    print(f"Result: {sum_result}")

# ENTRY POINT CHECK
if __name__ == "__main__":
    main()
```

This is your complete “LEGO instruction manual”! Each concept is a block you can recognize and combine to build any program. Would you like me to elaborate on any specific block or show how certain blocks combine in common patterns?​​​​​​​​​​​​​​​​
