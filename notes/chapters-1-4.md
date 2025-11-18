# C# Notes - Chapters 1-4

## Chapter 1: .NET Basics

- .NET provides CLR (safe execution environment)
- Supports multiple languages: C#, VB, VC++
- CLI compilation flow: C# → IL → CLR → Native Code
- CLR components: Class Loader, Memory Manager, Garbage Collector, JIT Compiler, Exception Manager, Thread Manager, Security Manager

## Chapter 2: Basic Syntax

### Types
**Primitive**: sbyte, byte, short, int, long, float, double, decimal, char, bool
**Non-primitive**: string, Classes, Interfaces, Structures, Enumerations

### Operators
- Increment/Decrement: n++, ++n, n--, --n
- Logical: && (AND), || (OR), ^ (XOR)
- Concatenation: "string1" + "string2"

### Control Flow
- if-else, switch-case
- while, do-while, for
- break, continue, goto

## Chapter 3: Arrays
- Creating arrays
- Login forms and menu examples

## Chapter 4: OOP Basics

### Class Components
Fields, Methods, Constructors, Properties, Events, Destructors

### Access Modifiers
- `internal`: Same assembly only
- `public`: All assemblies

### Class Modifiers
- `static`: Only static members
- `abstract`: Can have abstract methods
- `sealed`: Cannot be inherited
- `partial`: Multiple parts combine into one

### Objects
```csharp
ClassName refVar = new ClassName();
```

- Objects stored in heap
- Reference variables stored in stack
- Objects are anonymous, need reference variable to access

---

**Comparison with Java:**
- Main method: `static void Main()` vs Java's `public static void main(String[] args)`
- Namespaces vs packages
- C# has Properties (built-in), Java uses getters/setters
- `using` vs `import`
