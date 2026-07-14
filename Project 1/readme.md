# Linux Search Project

A beginner-friendly Linux mini project demonstrating the use of basic Linux commands for file creation, searching, and text processing. This project simulates a simple company directory with department-wise files and showcases how commands like `cat`, `grep`, `find`, `sort`, `uniq`, and `tr` can be used to manage and search data efficiently.

---

## 📁 Project Structure

```
Linux_Search_Project/
│
├── Finance/
│   ├── budget.txt
│   └── accounts.txt
│
├── HR/
│   ├── hr1.txt
│   └── hr2.txt
│
├── IT/
│   ├── devops.txt
│   └── server.txt
│
└── Sales/
    ├── sales1.txt
    └── sales2.txt
```

---

## 🎯 Objective

The purpose of this project is to learn and practice:

- Creating files and directories
- Writing content into files
- Searching files by name
- Searching text inside files
- Finding duplicate words across files
- Using Linux command-line utilities effectively

---

## 🛠️ Commands Used

### 1. `cat`

Used to create files and write content.

```bash
cat > Finance/budget.txt << EOF
Budget 500000
Expense 250000
Profit 250000
EOF
```

---

### 2. `find`

Searches for files matching a specific pattern.

```bash
find . -type f -name "*.txt"
```

Example Output:

```
./HR/hr1.txt
./HR/hr2.txt
./IT/devops.txt
./IT/server.txt
./Finance/budget.txt
./Finance/accounts.txt
./Sales/sales1.txt
./Sales/sales2.txt
```

---

### 3. `grep`

Searches for specific keywords inside files.

Search recursively:

```bash
grep -rl "Salary" .
```

Search for another keyword:

```bash
grep -rl "Budget" .
```

---

### 4. `tr`

Converts spaces into new lines.

```bash
tr ' ' '\n'
```

---

### 5. `sort`

Sorts all extracted words alphabetically.

```bash
sort
```

---

### 6. `uniq`

Finds duplicate entries.

```bash
uniq -d
```

---

### Combined Command

Find duplicate words across all text files:

```bash
cat */*.txt | tr ' ' '\n' | sort | uniq -d
```

Example Output:

```
250000
Budget
Department
Docker
Employee
HR
Linux
Salary
Server
```

---

## 📚 Concepts Learned

- Linux file system navigation
- Creating and managing directories
- Creating files using `cat`
- Recursive file searching using `find`
- Content searching using `grep`
- Text manipulation using `tr`
- Sorting text using `sort`
- Finding duplicate values using `uniq`
- Combining multiple commands using pipes (`|`)

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone <repository-url>
```

2. Open the project folder.

```bash
cd Linux_Search_Project
```

3. Execute any of the commands shown above.

Example:

```bash
find . -type f -name "*.txt"
```

or

```bash
grep -rl "Salary" .
```

---

## 📖 Learning Outcome

This project provides hands-on practice with essential Linux command-line tools used by system administrators, DevOps engineers, cybersecurity professionals, and software developers for searching, filtering, and processing files.

---

## 👨‍💻 Author

**Abhishek**

B.Tech Computer Science & Engineering

Learning Linux, DevOps
