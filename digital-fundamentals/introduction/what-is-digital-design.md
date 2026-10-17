# Chapter 1: Introduction to Digital Electronics

**Source:** ChipVerify - Digital Fundamentals

**Status:** Completed

---

## Learning Objectives

- [ ] What does "digital" mean, and why do computers use 0s and 1s?
- [ ] How can switches implement AND and OR operations?
- [ ] What are transistors and logic gates?
- [ ] How are chips built from smaller components?

---

## My Answers

### 1. What does "digital" mean?

My Answer: Digital means representing information using discrete values. Computers use binary (0s and 1s) because electronic circuits can reliably distinguish between two voltage states, making it easier to process and store information.

### 2. How do switches implement logic?

My Answer: Simple switches can be arranged in different configurations to perform logical operations. For example, switches connected in series behave like an AND gate, while switches connected in parallel behave like an OR gate.

### 3. What are transistors and logic gates?

My Answer: Transistors are tiny electronic components that can act as switches, using an electrical signal to control the flow of current. Logic gates are circuits made from transistors arranged to perform logical operations such as AND, OR, and NOT.

### 4. How are chips constructed?

My Answer: Chips are constructed using multiple layers of materials built on a silicon wafer. These layers form transistors, electrical connections, and insulation that work together to create functioning electronic circuits.

---

## Practice Exercise

### 1. A car's interior light should turn on when the driver's door is open OR the passenger's door is open. Write its truth table.

**My Solution:**

| A | B | OR 
|---|---|-----|
| 0 | 0 |  0   |
| 0 | 1 |   1  |
| 1 | 0 |   1  |
| 1 | 1 |   1  |

### 2. A safe should open only when key A AND key B are both turned. Write its truth table.

**My Answer:**

| A | B | AND 
|---|---|-----|
| 0 | 0 |  0   |
| 0 | 1 |   0  |
| 1 | 0 |   0  |
| 1 | 1 |   1  |

### 3. Would you build each one with switches in series or in parallel?

**Car Interior Light (OR):**
Parallel, because either switch can complete
the circuit independently.

**Safe with Two Keys (AND):**
Series, because both switches must be closed
to complete the circuit.

---

## Summary
- Digital circuits use only two values, 0 and 1, which makes them tolerant of noise and easy to copy perfectly

- A bit is a single 0 or 1, carried as a LOW or HIGH voltage; groups of bits represent numbers, letters, and colours

- Switches in series make an AND decision; switches in parallel make an OR decision

- A transistor is a switch controlled by a voltage, so transistors can control each other

- Logic gates such as NOT, AND, and OR are small groups of transistors, and they combine into everything else

- Designers describe circuits in Verilog, and synthesis tools turn the description into gates

- A chip is built in layers, from physics to systems, and this series climbs them from the bottom up

---

## Chapter Review

**Can I explain these concepts without looking?**

- [ ] Yes, I understand everything.
- [x] I need to review some concepts.

**Date Completed:** 08/17/2026