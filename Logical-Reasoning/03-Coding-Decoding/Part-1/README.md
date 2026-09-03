
# Coding-Decoding – Part 1

This folder contains my **Coding-Decoding – Part 1** learning notes and practice.

> **Note:** This README documents the concepts and methods I have learned so far.  
> **Part 2 is currently in progress and will be added later.**

---

## 📚 Topics Learned in Part 1

### 1. Alphabet Place Value

The first step in coding-decoding is knowing the position of every alphabet letter:

| Letter | Position | Letter | Position |
|---|---:|---|---:|
| A | 1 | N | 14 |
| B | 2 | O | 15 |
| C | 3 | P | 16 |
| D | 4 | Q | 17 |
| E | 5 | R | 18 |
| F | 6 | S | 19 |
| G | 7 | T | 20 |
| H | 8 | U | 21 |
| I | 9 | V | 22 |
| J | 10 | W | 23 |
| K | 11 | X | 24 |
| L | 12 | Y | 25 |
| M | 13 | Z | 26 |

---

## 2. Opposite Letters

Opposite letters are paired from both ends of the alphabet:

| Letter | Opposite |
|---|---|
| A | Z |
| B | Y |
| C | X |
| D | W |
| E | V |
| F | U |
| G | T |
| H | S |
| I | R |
| J | Q |
| K | P |
| L | O |
| M | N |

### Formula

For a letter having position `n`:

**Opposite position = 27 − n**

Example:

- A = 1 → 27 − 1 = 26 → Z
- C = 3 → 27 − 3 = 24 → X
- M = 13 → 27 − 13 = 14 → N

---

# 3. Main Coding-Decoding Patterns

The notes cover the following major patterns.

## Pattern I – Reverse Order

The letters of a word are written in reverse order.

**Example:**

`RAGHAV` → `VAHGAR`

`COURSE` → `ESRUOC`

### Approach
1. Keep all letters unchanged.
2. Reverse only their order.

---

## Pattern II – Opposite Letters

Each letter is replaced by its opposite alphabet letter.

**Example:**

`COVER`

C → X  
O → L  
V → E  
E → V  
R → I

So the coded word becomes:

`XL EVI`

(Apply the opposite-letter rule to every character.)

---

## Pattern III – Add / Subtract

A fixed value is added to or subtracted from the position of each letter.

Example structure:

`Letter → Position → Apply +n / −n → New Position → New Letter`

For example, if the rule is `+1`:

A → B  
B → C  
C → D

If the rule is `−1`:

B → A  
C → B  
D → C

The practice questions also use different positive and negative shifts.

---

## Pattern IV – Interchanging Letters

Letters are rearranged by interchanging selected positions.

The notes specifically practice exchanging positions such as:

**2 ↔ 3 ↔ 4**

The important step is to carefully track the original position of each letter before applying the interchange.

---

# 4. Miscellaneous Coding Rules

The notes also cover special rules involving vowels and consonants.

### Vowels

The five vowels are:

`A, E, I, O, U`

### Consonants

The remaining alphabet letters are treated as consonants.

### Vowel / Consonant Based Operations

Some practice questions use rules such as:

- Apply `+1` / `−1` with the opposite letter rule.
- Apply one operation to vowels and another operation to consonants.
- Treat vowels and consonants differently while coding a word.

The exact rule must be identified from the question before solving.

---

# 5. Other Rules Practiced

Part 1 also includes practice with:

### Ascending Order

Letters or their position values may need to be arranged in ascending order before forming the answer.

### Reverse First / Reverse at the End

Some questions require reversing letters or numbers as part of the coding process.

### Cross / Opposite Operations

Some questions combine position changes with opposite-letter relationships.

### Direct Coding

If the same word is given with the same coded word repeatedly, the direct relationship between letters can be identified and applied to a new word.

---

# 6. Number / Position Based Coding

In addition to letter coding, the notes begin number-based coding.

A word can first be converted into alphabet positions:

`A = 1, B = 2, C = 3, ... Z = 26`

Example:

`CAT`

C = 3  
A = 1  
T = 20

So:

`CAT → 3 1 20`

These numerical values can then be manipulated according to the question's rule.

---

# 7. Practice Questions

Part 1 contains a substantial set of handwritten practice questions.

The practice includes:

- Direct letter coding
- Reverse-order coding
- Opposite-letter coding
- Addition/subtraction of alphabet positions
- Vowel/consonant based coding
- Ascending-order operations
- Interchanging positions
- Cross/opposite operations
- Mixed coding rules
- Number/position-based coding

The practice set extends through **Question 25**.

---

# 🧠 Problem-Solving Approach

When solving a Coding-Decoding question:

1. **Identify the type of coding.**
2. Convert letters into their **alphabet positions** if required.
3. Check whether the word is:
   - Reversed
   - Opposite-coded
   - Shifted by `+n` or `−n`
   - Rearranged
   - Divided into vowels/consonants
   - Converted into numbers
4. Compare the given word and coded word carefully.
5. Apply the same rule to the required word.
6. Verify the final answer.

---

# 📌 Quick Revision

| Pattern | Main Idea |
|---|---|
| Place Value | A=1 to Z=26 |
| Opposite Letters | A↔Z, B↔Y, ... M↔N |
| Reverse Order | Reverse the positions of letters |
| Add/Subtract | Shift alphabet positions by a given value |
| Interchange | Exchange selected letter positions |
| Vowel/Consonant | Apply different rules to vowels and consonants |
| Ascending Order | Arrange based on alphabet/position values |
| Number Coding | Convert letters into numerical positions |
| Mixed Coding | Combine two or more rules |

---

# 📈 Learning Progress

- [x] Alphabet Place Value
- [x] Opposite Letters
- [x] Reverse Order
- [x] Add / Subtract Coding
- [x] Interchanging Letters
- [x] Vowel / Consonant Based Coding
- [x] Ascending Order
- [x] Mixed Coding Practice
- [x] Number / Position Based Coding — started
- [ ] Coding-Decoding Part 2 — **In Progress**

---

## 📂 Part Structure

This repository is being updated progressively as I learn.

```text
Coding-Decoding/
│
├── Part-1/
│   └── README.md
│
└── Part-2/
    └── README.md   # Will be added after completing Part 2
```

---

## 🎯 Goal

Build strong fundamentals in **Coding-Decoding** for aptitude and competitive examinations by learning each pattern and solving practice questions step-by-step.

---

**Status:** Part 1 Completed ✅ | Part 2 In Progress 🔄
