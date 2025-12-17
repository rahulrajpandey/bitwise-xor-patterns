# XOR & Bit Manipulation – Practice Roadmap

This document lists XOR-based and bit-manipulation problems in a structured order,
from fundamentals to advanced patterns, with the goal of building strong intuition
and interview readiness.

---

## LEVEL 1 — XOR Basics (Mental Model Building)

*Goal: Understand XOR as mod-2 cancellation.*

1. **XOR properties and laws**
    - `a ^ a = 0`
    - `a ^ 0 = a`
    - XOR is **commutative** and **associative**

2. **Single Number**
    - All numbers appear twice except one

3. **XOR of array elements**

4. **XOR of range `1..n`**
    - Pattern recognition

5. **Missing Number (`1..n`) using XOR**

---

## LEVEL 2 — XOR as Comparison / Set Difference

*Goal: Use XOR to compare two sets or detect differences.*

6. **Find the duplicate number (`1..n`)**

7. **Find missing and repeating number**

8. **XOR of two numbers without using XOR operator**
    - Construct XOR using `AND`, `OR`, `NOT`

---

## LEVEL 3 — Partitioning Using XOR

*Goal: Separate numbers using a distinguishing bit.*

9. **Two Single Numbers**
    - All appear twice except two unique numbers

10. **Find two numbers with odd occurrences**

11. **Two Missing Numbers (`1..n`)**
    - XOR + rightmost set bit partitioning

12. **Divide numbers into two groups using a bit mask**

---

## LEVEL 4 — Beyond XOR: Frequency Modulo Problems

*Goal: Handle cases where XOR alone fails.*

13. **Single Number II**
    - All numbers appear 3 times except one
    - Bit counting (mod 3)

14. **Find element appearing once when others appear `k` times**

15. **Single Number III (variation)**
    - Two appear once, others appear thrice

---

## LEVEL 5 — Finite State Machine (FSM) Bitwise Patterns

*Goal: Optimize bit-counting logic using state transitions.*

16. **Single Number II using FSM**
    - No extra memory
    - Handles negative numbers

17. **FSM-based solution for arbitrary repetition counts**

---

## LEVEL 6 — Prefix XOR & Subarray Logic

*Goal: Use XOR like prefix sums.*

18. **Subarray with XOR = K**

19. **Count subarrays with equal XOR**

20. **Longest subarray with XOR = K**

21. **XOR queries of a subarray**

22. **Prefix XOR array and prefix XOR matrix**

---

## LEVEL 7 — Greedy & Optimization with Bits

*Goal: Higher-order reasoning and bitwise greedy thinking.*

23. **Maximum XOR of two numbers in an array**

24. **Maximum XOR with an element from array (queries)**

25. **Minimum XOR pair**

26. **Bitwise Trie for XOR optimization**

---

## LEVEL 8 — Advanced & Edge-Case Heavy Problems

*Goal: Pattern generalization and tricky reasoning.*

27. **Find element that appears odd number of times (generalized)**

28. **Find k-th bit of XOR of a range**

29. **XOR of all pairings**

30. **Gray Code generation**

31. **Missing number using XOR (revisited with constraints)**

32. **Negative numbers and XOR**
    - Two’s complement intuition

33. **When XOR fails and why**

34. **XOR vs HashMap — trade-offs**

---

## LEVEL 9 — Conceptual & System-Thinking Applications

*Goal: Apply XOR beyond DSA into real systems.*

35. **Design a system to detect odd-frequency events**

36. **Streaming XOR anomaly detection**

37. **XOR-based deduplication ideas**

38. **Why XOR is used in RAID parity**

39. **XOR in fault tolerance and recovery**

---

## Goal of This Roadmap

- Build intuition, not memorization
- Recognize XOR problem patterns instantly
- Be able to derive solutions in interviews
- Write clean, explainable solutions

Each problem will include:
- Intuition
- Step-by-step reasoning
- Edge cases
- Clean Java implementation