# Bitwise XOR Patterns

This repository is for mastering XOR-based bit manipulation problems.

## Goals
- Build intuition for XOR operations
- Understand common problem patterns
- Practice interview-grade solutions

## Topics
- XOR basics
- Single Number problems
- Two unique numbers
- Bit counting & FSM techniques

## Build
```
mvn clean compile
```

---

## Notes

**Two’s Complement (Negative Numbers)**
```
-x = (~x) + 1
```

**Representation of -1**
```
-1 = all bits set
-1 + 1 = 0   (via overflow wrap)
```

**Bitwise NOT vs Logical NOT**
  - Bitwise NOT (~) flips all bits
  - Logical NOT (!) is boolean
    ```
    ~0  = -1
    !0  = 1
    ```

**Core Bitwise Identities**
```
a ^ a    = 0
a ^ 0    = a
x ^ -1   = ~x
~(-1)    = 0
~0       = -1
```

XOR is bitwise difference detection, meaning if XOR of two numbers are not zero, then there is definitely at-least one-bit difference in the binary representation of these two numbers.

**Binary Representation Uniqueness**
 - Within the same width & interpretation:
 - Two different numbers can never have the same bit pattern
 - Same bits can be interpreted differently:
   - Signed vs unsigned
     Example (8-bit):
     ```
      10000000 → -128 (signed), 128 (unsigned)
     ```

Rightmost Set bit Extraction: `x & -x`


