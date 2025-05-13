# 📘 Type Inference in TypeScript

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
