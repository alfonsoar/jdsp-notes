# Chapter 5

Chapter 5 starts off by cataloging the importance of being able to decouple JS applications and the concept of "modules". In the past modules (ie. packages like `react`, `jQuery`, `bootstrap`) in javascript did not have a single standard which led to the creation of Asynchronous Module Definition (AMD) and CommonJS. Eventually the governing body for JavaScript, TC39 introduced "ECMAScript modules" (ES Modules) with ES2015 specification. Since then these have become the defacto way of importing / exporting in JavaScript applications and is supported by all major browsers. 

- `import` declarations in a module bind exports in a local module, which can be renamed. 
- `export` declarations bind a modules local variable so they are visible outside the module while ensuring they cannot be modified. 

## Module objects 

Given

```ts
export function foo() {
    return 'foo';
}

export function bar() {
    return 'bar';
}

export function baz() {
    return 'baz';
}
```

Module objects allow you to import all exports like so: 

```ts
import * as Functions from './functions.ts';

console.log(Functions.foo()); // Prints "foo"
console.log(Functions.foo() + " " + Functions.bar()); // Prints "foo bar"
```
