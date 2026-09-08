# PA3 | ECE2112 | EXPERIMENT 3 | DIONALDO, PVA
---
### **PANDAS**
#### Submitted by Pierre Van Aken A. Dionaldo | 2ECE-A | 09.09.2026

This repository showcases the objective and detailed discussion of the experiment from the Programming Assignment 3 last September 8, 2026 where the class discussed Module 3 - **Python Data Analysis (PANDAS)**

---
### **Objectives**
---
At the end of this laboratory activity, the student should be able to:

1. load a CSV dataset into a Pandas DataFrame;
2. select rows and columns using positional and label-based indexing;
3. filter records using conditions on a DataFrame column; and
4. extract a well-defined subset of data without changing the source data.

The students are also expected to use the same cars.csv dataset supplied for Experiment 3. Write the solutions in one Jupyter Notebook and import Pandas as pd. The dataset contains the Model column together with the vehicle variables used in the original experiment.

- Load the CSV file into a DataFrame named cars.
- Use Pandas subsetting, slicing, indexing, and Boolean conditions. Do not manually type any requested table or answer.
- Do not modify values in cars; create a new DataFrame or Series for each requested subset.
- Preserve the row order of the source dataset unless stated otherwise.
- Display every requested result in an executed notebook cell.


---
### **Programming Problems**
---
#### **A. POSITIONAL AND LABEL-BASED SLICING**

After loading cars, complete the following operations.

a. Display the shape and complete list of column names of cars.
b. Using positional slicing, create cars 6 to 10 containing rows 6 through 10 of the dataset, where
the first data row is row 1.
c. From cars 6 to 10, display only the columns Model, mpg, cyl, hp, and gear, in that order.

**Requirement**: The row selection in part (b) must use iloc; the column selection in part (c) must use column labels.

**CODE**
```

```

**OUTPUT**
```

```

The following functions and methods in this code are:
- `code`: 
- `code`:
- `code`:

---
#### **B. MODEL LOOKUP**

Use Boolean indexing on the Model column to answer both requests.

a. Display the complete row for Toyota Corolla.
b. For Pontiac Firebird, display only Model, mpg, hp, and wt.

Store the two results in toyota and pontiac, respectively. Do not use a hard-coded row number to locate either model.

**CODE**
```

```

**OUTPUT**
```

```

The following functions and methods in this code are:
- `code`: 
- `code`:
- `code`:

---
#### **C. MULTI-MODEL SUBSETTING**

Create a DataFrame named selected cars containing only the records for three models: Datsun 710,
Lotus Europa, and Ferrari Dino.

For these records, retain only Model, mpg, cyl, hp, and gear. Select the rows by their model values
rather than by row numbers. Display selected cars and its shape.

**Required check**: The final DataFrame must contain exactly three rows and five columns.

**CODE**
```

```

**OUTPUT**
```

```

The following functions and methods in this code are:
- `code`: 
- `code`:
- `code`:

---
### **END OF NOTEBOOK**
