
# 📅 Calendar

This section contains my **Calendar notes, formulas, shortcuts, examples, and problem-solving approaches** for aptitude and logical reasoning.

---

## 📚 Topics Covered

- Basic Calendar Concepts
- Days and Months
- Normal Year and Leap Year
- Odd Days
- Century Years
- Finding the Day of a Given Date
- Same Day, Different Year
- Same Year, Different Date
- Repeated Calendar
- Conditional Calendar Questions
- Practice Questions

---

## 1. 📖 Basic Calendar Concepts

A calendar helps us determine the **day of the week** corresponding to a particular date.

### Days of the Week

There are 7 days in a week:

```text
Sunday
Monday
Tuesday
Wednesday
Thursday
Friday
Saturday
```
---
## 2. 📆 Number of Days in a Year
```
Normal Year-

A normal year contains:

365 days

Since:

365 ÷ 7 = 52 weeks + 1 day

Therefore:

Normal Year = 1 Odd Day
```
```
Leap Year-

A leap year contains:

366 days

Since:

366 ÷ 7 = 52 weeks + 2 days

Therefore:

Leap Year = 2 Odd Days

```
---
## 3. 📅 Number of Days in Months
```
Month	          Days
January	           31
February          28/29
March	           31
April	           30
May	           31
June	           30
July	           31
August         	   31
September	   30
October	           31
November	   30
December           31
```
```
Important
February has 28 days in a Normal Year.
February has 29 days in a Leap Year.
```
---
## 4. 🔄 Leap Year
```
Rule

A year is generally a leap year if it is divisible by 4.
```
```
For century years:

Divisible by 400 → Leap Year
Not divisible by 400 → Not a Leap Year
```
```
Examples
1900 → Not a Leap Year
2000 → Leap Year
2100 → Not a Leap Year
2400 → Leap Year
```
```
Quick Check
1900 → Not divisible by 400 → Not Leap Year
2000 → Divisible by 400 → Leap Year
2100 → Not divisible by 400 → Not Leap Year
2400 → Divisible by 400 → Leap Year
```
---
## 5. 🧮 Odd Days
```
An Odd Day is the number of days left after removing complete weeks.
```
```
Since:

1 Week = 7 Days

we find the remainder after dividing the total number of days by 7.

Important Values
365 ÷ 7 = 52 weeks + 1 day
366 ÷ 7 = 52 weeks + 2 days

Therefore:

Normal Year → 1 Odd Day
Leap Year   → 2 Odd Days
```
```
Possible Odd Days

The remainder can be:

0, 1, 2, 3, 4, 5, or 6
```

## 6. 🏛️ Century Years
```
Important century odd-day values:

Years	Odd Days
100	       5
200	       3
300            1
400	       0
```
```
The pattern repeats:

500 → 5      900  → 5
600 → 3      1000 → 3
700 → 1      1100 → 1 
800 → 0      1200 → 0
```
---
## 7. 📌 Month Odd Days
```
For a normal year:

31 days → 3 Odd Days
30 days → 2 Odd Days
28 days → 0 Odd Days
```
```
For February in a leap year:

29 days → 1 Odd Day
```
```
Month-wise Values
January   →  3
February  →  0 (Normal Year)
March     →  3
April     →  2
May       →  3
June      →  2
July      →  3
August    →  3
September →  2
October   →  3
November  →  2
December  →  3
```
---
## 8. 🧠 Finding the Day of a Given Date
```
To find the day of a particular date, calculate the odd days from:
```
```
Completed centuries
Remaining completed years
Completed months
Remaining days

Then divide the total by 7 and use the remainder to determine the weekday.

```
```
General Approach

Completed Years
       ↓
Year Odd Days
       ↓
Completed Months
       ↓
Month Odd Days
       ↓
Remaining Date
       ↓
Total Odd Days
       ↓
Divide by 7
       ↓
Find the Day
```
---
## 9. 🔢 Type 1 — Same Day, Different Year
```
In this type:

The date is the same.
The year is different.
Example
1 January 1992 = Wednesday

Find the day on:

1 January 2003
Method

First find the difference between the years:

2003 - 1992 = 11 years

Then calculate the odd days contributed by the years between them.

Remember:

Normal Year → 1 Odd Day
Leap Year   → 2 Odd Days

Finally, add the calculated odd days to the given weekday.
```
---
## 10. 🔢 Type 2 — Same Year, Different Date
```
In this type:

The year remains the same.
The date changes.
Example
23 May 2003 = Friday

Find the day on:

23 December 2003
Method

Calculate the odd days between the two dates.

Consider the remaining days of the months:

May
June
July
August
September
October
November
December

Then:

Total Odd Days ÷ 7
→ Remainder

Move the given weekday forward according to the remainder.
```
---
## 11. 🔢 Type 3 — Find day on a particular date
```
In this type:

The date changes.
The year changes.
General Method

Calculate:

Odd Days of Completed Years
+
Odd Days of Completed Months
+
Remaining Days

Then:

Total Odd Days ÷ 7
→ Remainder
→ Required Day
Example

Find the day of:

28 May 2003

Break the calculation into:

Completed Years
+
Completed Months
+
Date

Then calculate the total odd days.
```
---
## 12. 🔢 Type 4 — Different Day and Different Year
```
In this type, both the date and year are different.

Example

Given:

6 October 1981 = Thursday

Find:

6 March 2004 = ?
Method
Find the difference between the years.
Calculate the year odd days.
Calculate the odd days between the required months/dates.
Add the odd days.
Divide by 7.
Move the given weekday according to the remainder.
```
---
## 13. 🔢 Type 5 — Month Repetition
```
A useful relationship from my preparation involves:

16 March

For corresponding-date questions, month odd-day values can be used.

Important month values odd days:

Januray    → 3
February   → 0/1
March      → 3
April      → 2
May        → 3
June       → 2
July       → 3
August     → 3
September  → 2
October    → 3
November   → 2
December   → 3

Completely, reminder is 0 when diveide by 7 to month and the next month is repeated month.
```
---
## 14. 🔢 Type 6-  Repeated Calendar
```
A calendar repeats when the same dates fall on the same weekdays again.

The repetition depends on the odd days contributed by normal and leap years.

Important values from my preparation:

Leap Year  → 28 Years
Normal Year → 6 Years
Normal Year → 11 Years
Normal Year → 11 Years
Leap Year  → 28 Years

The actual repetition should always be checked according to the leap-year sequence involved.
```
---
## 15. 🔢 Type 7- Conditional Calendar Questions
```
Questions like:
    Which day is not a last day of century?
```
---

## 16. 📝 Practice Questions

Question 1
```
If:

3 March 2024 = Sunday

what day will be:

13 March 2024?

# Solution
13 - 3 = 10 days

10 ÷ 7 = 1 week + 3 days

Sunday + 3 days = Wednesday

Answer: Wednesday
```
Question 2
```
Find the day of the week on:

27 July 2004

Use:

Completed Years
+
Month Odd Days
+
Date

and calculate the remainder after division by 7.
```
Question 3
```
If:

16 April 1974 = Tuesday

find the day on:

16 April 1976

Count the odd days contributed by the intervening years.
```
Question 4
```
If:

23 May 2003 = Friday

what day was:

23 December 2003?

Calculate the odd days between the two dates.
```
Question 5
```
Find the day of:

28 May 2003

using the odd-day method.
```
Question 6
```
Find the day of the week for:

28 May 1991

using the odd-day method.
```
Question 7
```
What day of the week was:

1 March 1990?

Use the century and month odd-day method.
```
Question 8
```
Find which year has the same calendar as a given year.

Use the repeated-calendar method and compare the odd days.
```
---
## 17. 🧠 Problem-Solving Strategy
```
For Calendar questions, follow this sequence:

Step 1 → Identify the question type
        ↓
Step 2 → Check Normal Year / Leap Year
        ↓
Step 3 → Calculate Year Odd Days
        ↓
Step 4 → Calculate Month Odd Days
        ↓
Step 5 → Add Remaining Date Days
        ↓
Step 6 → Divide Total by 7
        ↓
Step 7 → Use the Remainder
        ↓
Step 8 → Find the Required Weekday
```
---
## 18. 📌 Quick Revision
```
Year
Normal Year = 365 Days = 1 Odd Day
Leap Year   = 366 Days = 2 Odd Days
Month
31 Days = 3 Odd Days
30 Days = 2 Odd Days
28 Days = 0 Odd Days
29 Days = 1 Odd Day
Century
100 Years = 5 Odd Days
200 Years = 3 Odd Days
300 Years = 1 Odd Day
400 Years = 0 Odd Days
```
---
## 19. 🎯 Exam Tips
```
Always check whether the year is a Leap Year.
Pay special attention to February.
For century years, check the 400-year rule.
Reduce large numbers of days by dividing by 7.
Identify the question type before starting the calculation.
For same-year questions, calculate the days between the two dates.
For different-year questions, calculate the year odd days.
Use odd days to simplify large calculations.
Recheck leap-year involvement when crossing February.
```
---
## 📈 My Learning Progress
```
Calendar
Status: ✅ Completed
```
---
## 📚 Learning Resources
```
I learned and practiced these concepts using educational resources such as:

Physics Wallah (PW)
Adda247
Other educational YouTube resources

These notes represent my own learning, understanding, calculations, and problem-solving practice.
```
---
## ⭐ Revision Formula
```
Identify → Calculate Odd Days → Divide by 7 → Find the Day
```
---
