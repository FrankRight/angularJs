# Typescript fundamentals Summary Notes

Typescript is object-oriented. Any Javascript code is valid Typescript. The opposite is not true. Typescript is transpiled to Javascript, since not all browser support typescript. Typescript converts all code to ES5.

## What is covered?

- Type annotations.
- Arrow functions.
- Interfaces.
- Classes.
- Access modifiers.
- Properties.
- Modules.

## Features of Typescript

- Strong typing - optional.
- Object oriented features.
- compile time errors captured.
- Access to great tools. Like intellisense.

## Installing typescript globally

npm install -g typescript

## Decalare variables

Use the keyword var or let. Let is preferable from ES6 onwards. All code will be converted to the var keyword declaration.

### Value unknown during declaration

We use type annotation as shown below

```typescript
let a: number;
```

## Types

The different types in typescript

- number
- boolean
- string
- any
- arrays
- enum

### Declaring arrays

example

```typescript
let arr: nums[] = [1, 2, 3];
```

### Using enum

Example

```typescript
enum Color {
  Red,
  Green,
  Blue,
}
```
