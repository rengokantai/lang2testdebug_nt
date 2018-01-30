# lang2testdebug_nt

### 5 Error handling in Angular
Zones in Angular
scoped execution contexts.
groups asynchronous code into one context.

### 6 Understanding zones in Angular apps
What zones do
- make execution contexts for your code
- one zone per stack
- can access parent zones with child zones
- zones are immutable
- zones are not guaranteed
- async actions execute in the same zone

### 9 Understanding Angular decorator
What are
- Return a function
- Tell Angular metadata about your code
- Help with dependency injection
- Marked using an @ symbol
- Invoked at runtime with arguments

Decorator errors
- Angular emits errors only at runtime
