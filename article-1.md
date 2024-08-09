# How to learn Go when you already know TypeScript very well?

## Introduction
For TypeScript developers, diving into Go can be an exciting vecture into a new paradigm of programming. Both languages are known for their efficiency and performance but differ significantly in syntax, design principles, and use cases. If you're well-versed in TypeScript and are looking to expand your skillset to inckude Go, this guide will help bridge the gap between the two languages.

## Understanding the differences
Before you dive into the code, it's essential to grasp the fundamental differences between TypeScript and Go:
- **Typing System:** TypeScript is a superset of JavaScript that adds static types, allowing for type safety and robust tooling. Go, on the other hand, has a statically typed nature but is designed to be simpler and more minimalistic.   
- **Concurrency:** Go shines with its built-in support for concurrency through goroutines and channels. TypeScript relies on asynchronous programming using promises and async/await.   
- **Object Orientation:** TypeScript supports classes and inheritence, while Go uses structs and interfaces, focusing more on composition rather than inheritence.

## Basic Syntax Comparison
- Defining variables
  <br/>
  <br/>
  TypeScript
  ```typescript
    let message: string = "Hello devs!";
  ```

  Go
  ```go
    var message string = "Hello devs!"
  ```
- Defining functions
  <br/>
  <br/>
  TypeScript
  ```typescript
    function add(num1: number, num2: number): number {
      return (num1+num2);
    }
  ```

  Go
  ```go
    func add(num1 int, num2 int) int {
      return (num1+num2)
    }
  ```
- Structs & Interfaces
  <br/>
  <br/>
  TypeScript
  ```typescript
    interface Student {
      name: string;
      rollNumber: number;
    }
  ```

  Go
  ```go
    type Student {
      Name string
      RollNumber int
    }
  ```
