# Binary and Hexadecimal Math

## Overview

Computers do not understand decimal numbers like humans do. Instead, they store and process all information using the **binary number system**, which consists of only two digits: **0** and **1**.

Because binary numbers can become very long, programmers also use the **hexadecimal number system**, which provides a shorter and more readable way to represent binary values.

Understanding binary and hexadecimal is an important part of computer science and helps explain how computers store data, memory addresses, colors, and machine instructions.

---

## Why It Matters

Learning binary and hexadecimal helps you:

- Understand how computers store data
- Learn how memory works
- Understand networking concepts like IP addresses
- Read memory addresses and machine code
- Work with colors in web development
- Build a stronger computer science foundation

Many areas of software engineering rely on these number systems.

---

# Number Systems

Different number systems use different sets of digits.

| Number System | Base | Digits Used |
|--------------|------|-------------|
| Decimal | 10 | 0–9 |
| Binary | 2 | 0, 1 |
| Hexadecimal | 16 | 0–9, A–F |

Humans normally use decimal, while computers use binary.

---

# Binary Numbers

Binary is a **base-2** number system.

It uses only two digits:

- 0
- 1

Each binary digit is called a **bit**.

Examples:

```text
0
1
10
101
1101
100101
```

---

## Why Computers Use Binary

Computer hardware contains billions of tiny electronic switches called **transistors**.

Each transistor has only two possible states:

- OFF → 0
- ON → 1

Because transistors naturally have two states, binary is the perfect language for computers.

---

## Understanding Binary Values

Each position in a binary number represents a power of 2.

Example:

```text
Binary: 1101

Positions:

8   4   2   1
1   1   0   1
```

Now add the values where there is a **1**.

```text
8 + 4 + 1 = 13
```

Therefore:

```text
1101₂ = 13₁₀
```

---

## More Binary Examples

| Binary | Decimal |
|---------|---------:|
| 0 | 0 |
| 1 | 1 |
| 10 | 2 |
| 11 | 3 |
| 100 | 4 |
| 101 | 5 |
| 110 | 6 |
| 111 | 7 |
| 1000 | 8 |

---

# Bits and Bytes

A **bit** is a single binary digit.

Example:

```text
1
```

A **byte** consists of **8 bits**.

Example:

```text
01010110
```

One byte can represent **256 different values (0–255).**

---

# Hexadecimal Numbers

Hexadecimal is a **base-16** number system.

It uses:

```text
0 1 2 3 4 5 6 7 8 9 A B C D E F
```

Letters represent numbers:

| Hex | Decimal |
|-----|---------:|
| A | 10 |
| B | 11 |
| C | 12 |
| D | 13 |
| E | 14 |
| F | 15 |

---

## Why Hexadecimal Exists

Binary numbers quickly become long and difficult to read.

Example:

```text
Binary

1111111111111111
```

The same value in hexadecimal is:

```text
FFFF
```

Hexadecimal makes binary much shorter and easier for humans to work with.

---

## Binary to Hexadecimal

Every group of **4 binary bits** equals **1 hexadecimal digit**.

Example:

```text
Binary

1010

↓

Hexadecimal

A
```

Another example:

```text
Binary

11111111

↓

1111 1111

↓

F    F

↓

FF
```

---

## Real-World Uses

Binary and hexadecimal are used in many areas of computing.

Examples include:

- Computer memory
- CPUs
- Operating systems
- Machine code
- IP addresses
- MAC addresses
- File formats
- Debugging tools
- Web colors

---

## Example: Web Colors

Web developers use hexadecimal to define colors.

Examples:

```text
#FFFFFF
```

White

```text
#000000
```

Black

```text
#FF0000
```

Red

```text
#00FF00
```

Green

```text
#0000FF
```

Blue

---

## Common Mistakes Beginners Make

Beginners often:

- Think computers understand decimal numbers directly.
- Confuse binary with hexadecimal.
- Forget that hexadecimal is simply a shorter way of writing binary.
- Memorize conversions instead of understanding how they work.

Understanding the concepts is more important than memorizing every conversion.

---

## Key Takeaways

- Computers store all data using binary.
- Binary uses only **0** and **1**.
- A **bit** is one binary digit.
- A **byte** contains **8 bits**.
- Hexadecimal is a shorter representation of binary.
- Hexadecimal is commonly used in programming, networking, and web development.

---

## Summary

Binary and hexadecimal are essential number systems in computer science. Binary is the language computers use internally because electronic hardware operates using two states: on and off. Hexadecimal provides a compact and human-friendly way to represent binary values, making it widely used in programming, networking, memory management, and web development. Understanding these systems gives software engineers a deeper understanding of how computers process and store information.
