# Day 01 – Understanding Lookup Logic

## 🎯 Objective

Before learning lookup formulas such as VLOOKUP, XLOOKUP, INDEX, and MATCH, it is important to understand the concept of a lookup.

A lookup is simply:

> Find a value in a table and return related information from another column.

---

## 📖 What is a Lookup?

Think about everyday examples.

### Example 1: Employee ID Card

You know:

```text
Employee ID = 104
```

You want:

```text
Employee Name
Department
Salary
```

You search for Employee ID 104 and retrieve the related information.

That is a lookup.

---

### Example 2: Product Catalog

You know:

```text
Product Code = P1001
```

You want:

```text
Product Name
Price
Category
```

Again, you search for a value and return related information.

That is a lookup.

---

## 💼 Why Are Lookups Important?

In real-world business scenarios, information is often stored across multiple tables.

### Employee Table

| EmpID | Name  | Department |
| ----- | ----- | ---------- |
| 101   | Amit  | IT         |
| 102   | Rahul | Sales      |
| 103   | Priya | HR         |

### Salary Table

| EmpID | Salary |
| ----- | ------ |
| 101   | 50000  |
| 102   | 45000  |
| 103   | 40000  |

Suppose you know:

```text
EmpID = 102
```

And you need:

```text
Salary = 45000
```

Instead of manually searching every time, Excel lookup functions can automate this process.

---

## 🧪 Practice Dataset

Create a workbook named:

```text
Day01_Concepts.xlsx
```

Create **Sheet1** and enter the following data:

| EmpID | Name  | Department | Salary |
| ----- | ----- | ---------- | ------ |
| 101   | Amit  | IT         | 50000  |
| 102   | Rahul | Sales      | 45000  |
| 103   | Priya | HR         | 40000  |
| 104   | Neha  | IT         | 55000  |
| 105   | Karan | Finance    | 60000  |

---

## 📝 Exercise 1

Without using any formulas, answer the following questions manually.

### Question 1

What is the Department of EmpID 104?

**Answer:** IT

### Question 2

What is the Salary of EmpID 102?

**Answer:** 45000

### Question 3

What is the Name of EmpID 105?

**Answer:** Karan

---

## 📝 Exercise 2

Create a lookup area below the table.

| Lookup ID |
| --------- |
| 103       |

Now manually identify the following information.

### Name

Search for EmpID 103.

**Answer:** Priya

### Department

**Answer:** HR

### Salary

**Answer:** 40000

---

## 🌎 Real-World Thinking Exercise

Imagine your company has a dataset like this:

| EmpID | Name | Department | Salary |
| ----- | ---- | ---------- | ------ |
| 10001 | ...  | ...        | ...    |
| 10002 | ...  | ...        | ...    |
| ...   | ...  | ...        | ...    |

with more than **10,000 employees**.

Can you manually search for information every time?

**No.**

This is why Excel provides lookup functions such as:

* VLOOKUP
* XLOOKUP
* INDEX
* MATCH

These functions automate the exact process you performed manually in the exercises above.

---

## 🚀 Mini Challenge

Add five additional employees to the dataset.

Example:

| EmpID | Name   | Department | Salary |
| ----- | ------ | ---------- | ------ |
| 106   | Rohan  | IT         | 52000  |
| 107   | Simran | HR         | 47000  |
| 108   | Arjun  | Sales      | 49000  |
| 109   | Meera  | Finance    | 61000  |
| 110   | Vikram | IT         | 58000  |

Create five lookup questions and answer them manually.

Examples:

* What is the Department of EmpID 108?
* What is the Salary of EmpID 109?
* What is the Name of EmpID 107?
* What is the Department of EmpID 110?
* What is the Salary of EmpID 106?

---

## ✅ Key Takeaway

You are not learning formulas yet.

For now, focus on understanding the lookup process:

```text
Search Value
      ↓
Find Matching Row
      ↓
Return Information
```

This simple concept is the foundation of every lookup function in Excel.

Tomorrow we will begin working with our first lookup formula: **VLOOKUP**.
