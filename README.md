# OCaml Code Style Guide (OCCSG)
---
## Function
### 1. Function design
1.1. Prefer polymorphic functions to the ones with concrete types in their signaures.

1.2. Less arguments are preferable.

### 2. Naming

### 3. Labeled & optional arguments

### 4. Recursion

### 5. Partial application


## Module

### 1. Module usage

1.1. Open only extensively used modules.

1.2. Open modules at the top level of a module.

1.3. For most cases if you want to open a module - prefer local open:

```ocaml
let open Some_module in ...
(* or *)
Some_module.( ... )
```

### 2. Module names
### 3. Module type & signature
### 4. Module nesting

## Object
## Class
## Common Patterns

