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

- Importing modules
  
  <br/>
  <br/>
  
  TypeScript
  ```typescript
    import { SomeClass } from "./SomeModule"
  ```

  Go
  ```go
    import "github.com/user/repo/SomePackage"
  ```

## Conclusion
In conclusion, I would like to offer some advice on learning a new programming language. The experience you gain while learning a new language is influenced by the languages you have previously mastered and your approach to understanding new concepts. Each individual's learning journey is unique.

Comparing the syntax of a new language with that of a language you are already familiar with can indeed facilitate quicker comprehension. However, it is crucial not to base your understanding on the logic of the previous language. Each programming language is distinct, with its own methods for solving problems, and it is unproductive to assume that concepts will translate directly from one language to another.

Approaching a new language with an open mind is beneficial. It is more effective to compare how different languages address similar problems rather than trying to interpret the new language through the lens of concepts from a language you already know.
