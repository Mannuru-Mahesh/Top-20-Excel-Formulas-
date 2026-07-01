# Top 20 Excel Formulas Every Beginner Should Know

This repository contains the **Top 20 Microsoft Excel formulas** with syntax, explanations, and examples. These formulas are useful for data analysis, reporting, finance, and everyday spreadsheet tasks.

---

## 1. SUM()

### Purpose
Adds numbers together.

### Syntax
```excel
=SUM(number1, number2, ...)
```

### Example
```excel
=SUM(A1:A10)
```

Result: Adds all values from A1 to A10.

---

## 2. AVERAGE()

### Purpose
Calculates the average of numbers.

### Syntax
```excel
=AVERAGE(range)
```

### Example
```excel
=AVERAGE(B1:B10)
```

---

## 3. COUNT()

### Purpose
Counts cells containing numbers.

### Syntax
```excel
=COUNT(range)
```

### Example
```excel
=COUNT(A1:A20)
```

---

## 4. COUNTA()

### Purpose
Counts all non-empty cells.

### Syntax
```excel
=COUNTA(range)
```

### Example
```excel
=COUNTA(A1:A20)
```

---

## 5. MAX()

### Purpose
Returns the largest value.

### Syntax
```excel
=MAX(range)
```

### Example
```excel
=MAX(C1:C20)
```

---

## 6. MIN()

### Purpose
Returns the smallest value.

### Syntax
```excel
=MIN(range)
```

### Example
```excel
=MIN(C1:C20)
```

---

## 7. IF()

### Purpose
Returns different values based on a condition.

### Syntax
```excel
=IF(condition, value_if_true, value_if_false)
```

### Example
```excel
=IF(A2>=35,"Pass","Fail")
```

---

## 8. AND()

### Purpose
Checks if all conditions are TRUE.

### Syntax
```excel
=AND(condition1, condition2)
```

### Example
```excel
=AND(A2>=35,B2>=35)
```

---

## 9. OR()

### Purpose
Checks if any condition is TRUE.

### Syntax
```excel
=OR(condition1, condition2)
```

### Example
```excel
=OR(A2>=35,B2>=35)
```

---

## 10. NOT()

### Purpose
Reverses TRUE/FALSE.

### Syntax
```excel
=NOT(condition)
```

### Example
```excel
=NOT(A2>100)
```

---

## 11. VLOOKUP()

### Purpose
Searches vertically for a value.

### Syntax
```excel
=VLOOKUP(lookup_value, table_array, col_index_num, FALSE)
```

### Example
```excel
=VLOOKUP(101,A2:D20,3,FALSE)
```

---

## 12. HLOOKUP()

### Purpose
Searches horizontally.

### Syntax
```excel
=HLOOKUP(value, table, row_number, FALSE)
```

### Example
```excel
=HLOOKUP("Math",A1:H5,3,FALSE)
```

---

## 13. XLOOKUP()

### Purpose
Modern replacement for VLOOKUP.

### Syntax
```excel
=XLOOKUP(lookup_value, lookup_array, return_array)
```

### Example
```excel
=XLOOKUP(101,A2:A20,C2:C20)
```

---

## 14. INDEX()

### Purpose
Returns a value at a specified row and column.

### Syntax
```excel
=INDEX(array,row,column)
```

### Example
```excel
=INDEX(A2:C10,4,2)
```

---

## 15. MATCH()

### Purpose
Returns the position of a value.

### Syntax
```excel
=MATCH(value,range,0)
```

### Example
```excel
=MATCH("Apple",A2:A10,0)
```

---

## 16. CONCAT()

### Purpose
Joins multiple text strings.

### Syntax
```excel
=CONCAT(text1,text2,...)
```

### Example
```excel
=CONCAT(A2," ",B2)
```

---

## 17. LEFT()

### Purpose
Returns characters from the left.

### Syntax
```excel
=LEFT(text,num_chars)
```

### Example
```excel
=LEFT(A2,4)
```

---

## 18. RIGHT()

### Purpose
Returns characters from the right.

### Syntax
```excel
=RIGHT(text,num_chars)
```

### Example
```excel
=RIGHT(A2,3)
```

---

## 19. MID()

### Purpose
Extracts characters from the middle.

### Syntax
```excel
=MID(text,start_num,num_chars)
```

### Example
```excel
=MID(A2,3,5)
```

---

## 20. TODAY()

### Purpose
Returns today's date.

### Syntax
```excel
=TODAY()
```

### Example
```excel
=TODAY()
```

---

# Bonus Formulas

- `NOW()`
- `SUMIF()`
- `SUMIFS()`
- `COUNTIF()`
- `COUNTIFS()`
- `IFERROR()`
- `TEXT()`
- `ROUND()`
- `ROUNDUP()`
- `ROUNDDOWN()`

---

# Applications

These formulas are commonly used in:

- 📊 Data Analysis
- 💰 Financial Reports
- 📈 Dashboards
- 👨‍💼 HR Management
- 🛒 Sales Reports
- 📦 Inventory Tracking
- 🎓 Student Marksheets
- 📅 Attendance Systems

---

# Skills You'll Learn

- Data Manipulation
- Conditional Logic
- Lookup Functions
- Text Processing
- Date & Time Functions
- Financial Calculations
- Dynamic Reporting

---

## Author

**Mannuru Mahesh**

M.Tech Data Science Student |Data Analytics & AI Enthusiast

⭐ If this repository helps you, don't forget to Star it!
