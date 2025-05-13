# 1. 📘 Type Inference in TypeScript

Nowadays, TypeScript enhances its intelligence. It can infer the type of a variable without declaring its type explicitly.

---

## ✅ Benefits of Type Inference

1. Code looks more clean
2. Code becomes more readable
3. No need to write types, which means less code
4. No need to repeatedly declare types

---

## 📌 Example

```ts
let message = "Hello, world!";

// Equivalent to:
let message: string = "Hello, world!"; // No need to explicitly declare type

message = 42; // ❌ Error: Type 'number' is not assignable to type 'string'
```

# 2. 📈 How TypeScript Improves Code Quality and Maintainability

TypeScript enhances code quality and project maintainability through its strong static type system and developer tooling. Below are key benefits that make it a preferred choice for scalable application development:

---

### ✅ 1. Type Checking

TypeScript checks types at compile time—**before the code runs**, preventing many common runtime errors.

```ts
function add(a: number, b: number) {
  return a + b;
}

add("5", 10); // ❌ Error: Argument of type 'string' is not assignable to parameter of type 'number'.
```

### ✅ 2. Early Error Detection

Errors are caught early in the development process, leading to:

- Fewer bugs in production
- Easier debugging
- Reduced time spent on testing to find bugs

### ✅ 3. Scalability

As projects grow, TypeScript’s strict typing and modular structure help maintain large project.

### ✅ 4. Better Collaboration

Types clarify intent and usage, making it easier for teams to collaborate.


