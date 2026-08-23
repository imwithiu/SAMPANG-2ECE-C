**ECE 2112: Advanced Computer Programming and Algorithms** 

## **– University of Santo Tomas Faculty of Engineering Electronics Engineering Department** 

# **EXPERIMENT 1: INTRODUCTION TO PYTHON PROGRAMMING** 

**Name:** Sampang, Zechariah D. **Date Submitted:** AUGUST 23, 2026 **Section:** 2ECE ~~-~~ C 

## **I. Intended Learning Outcomes** 

At the end of this laboratory activity, the student should be able to: 

1. use basic Python functions, operators, and string operations; 

2. manipulate strings using indexing, slicing, and built-in string methods; 

3. apply sequence unpacking to manipulate the elements of a list; and 

4. construct simple Python functions that return a specified result. 

## **II. Instructions** 

Write a Python program in a Jupyter Notebook to solve each of the following problems. 

- Use the exact function names specified in each problem. 

- Place each problem in a separate, clearly labeled section of the notebook. 

- Each function must **return** the required result unless printed output is explicitly requested. 

- Do not use external Python libraries. 

- Use only basic Python operations, string methods, slicing, and sequence unpacking. Loops and classes are not required. 

- Test each function using the examples provided. Additional valid inputs may be used when grading the notebook. 

## **III. Programming Problems** 

### **A. WORD ROTATION PROBLEM** 

Create a function named `rotate` ~~`w`~~ `ord()` that accepts a non-empty string. Move the **first character** of the string to the end while keeping all remaining characters in their original order. Preserve the capitalization of every character. 

## **Function format:** `rotate word(text)` 

## **Examples:** 

```
rotate_word("python")->"ythonp"
rotate_word("logic")->"ogicl"
rotate_word("Code")->"odeC"
rotate_word("A")->"A"
```

**Requirement:** Use string indexing or slicing to construct the returned string. 

### **B. USERNAME BUILDER PROBLEM** 

Create a function named `make username()` that accepts two strings: `first` ~~`n`~~ `ame` and `last` ~~`n`~~ `ame` . The function must: 

1. convert all letters to lowercase; 

2. remove all spaces from the first name; 

3. remove all spaces from the last name; and 

4. join the processed first and last names using one period ( `.` ). 

Page 1 — Experiment No. 1 

**Function format:** `make username(first` ~~`n`~~ `ame, last` ~~`n`~~ `ame)` 

## **Examples:** 

```
make_username("Ada","Lovelace")->"ada.lovelace"
make_username("Alan","Turing")->"alan.turing"
make_username("AnaMaria","DeLeon")->"anamaria.deleon"
```

**Requirement:** Use basic string methods and string concatenation. Return the completed username. 

### **C. BOOKEND SWAP PROBLEM** 

Create a function named `swap` ~~`b`~~ `ookends()` that accepts a list containing at least two elements. Unpack the list into three variables: 

- `first` – the first element; 

- `middle` – a list containing everything between the first and last elements; and 

- `last` – the last element. 

Using these variables, return a **new list** in which the first and last elements have exchanged positions. The elements in `middle` must remain in their original order. Do not modify the input list. 

## **Function format:** `swap bookends(items)` 

## **Examples:** 

```
swap_bookends([1,2,3,4,5,6])->[6,2,3,4,5,1]
swap_bookends(["red","green","blue"])->["blue","green","red"]
swap_bookends([8,3])->[3,8]
```

**Requirement:** Use extended sequence unpacking in the following form: 

```
first,*middle,last=items
```

## **IV. Submission Requirements** 

Submit one Jupyter Notebook file ( `.ipynb` ) containing: 

1. your name and section; 

2. clearly labeled solutions for Problems A, B, and C; 

3. the three required Python functions; and 

4. executed test cells showing the expected output for the provided examples. 

The notebook must execute from beginning to end without errors. 

## **V. Grading** 

|**Component**|**Points**|
|---|---|
|Word Rotation Problem|25|
|Username Builder Problem|30|
|Bookend Swap Problem|35|
|Code readability, organization, and required test cases|10|
|**Total**|**100**|



_End of Experiment 1_ 

Page 2 — Experiment No. 1 

