# Linux File Commands Mini Project

A beginner-friendly Linux project demonstrating fundamental file and directory operations using basic Linux commands. This project covers creating directories and files, writing data to files, viewing file contents, navigating directories, and deleting files/directories.

---

## 📌 Objective

The objective of this project is to gain hands-on experience with essential Linux file management commands that are commonly used by developers, system administrators, and DevOps engineers.

---

## 🛠️ Commands Demonstrated

### 1. `pwd`

Displays the current working directory.

```bash
pwd
```

Example Output:

```
/home/vboxuser
```

---

### 2. `cd`

Changes the current directory.

```bash
cd Desktop
```

```bash
cd proj2
```

Move to the parent directory:

```bash
cd ..
```

---

### 3. `mkdir`

Creates a new directory.

```bash
mkdir proj2
```

---

### 4. `touch`

Creates an empty file.

```bash
touch fil1
```

---

### 5. `echo`

Writes text into a file.

Using `>` (overwrite):

```bash
echo "1. Green shirt guy" > fil1
```

Using `>>` (append):

```bash
echo "2. Cloud with DevOps" >> fil1
echo "3. Hello World" >> fil1
```

---

### 6. `cat`

Displays the contents of a file.

```bash
cat fil1
```

Example Output:

```
1. Green shirt guy
2. Cloud with DevOps
3. Hello World
```

---

### 7. `rm`

Deletes a file.

```bash
rm fil1
```

---

### 8. `rmdir`

Deletes an empty directory.

```bash
rmdir proj2
```

> **Note:** A directory must be empty before it can be removed using `rmdir`.

---

## 📂 Workflow

```
Home Directory
        │
        ▼
Desktop
        │
        ▼
Create proj2
        │
        ▼
Create fil1
        │
        ▼
Write multiple lines
        │
        ▼
Display file contents
        │
        ▼
Delete file
        │
        ▼
Return to parent directory
        │
        ▼
Delete empty directory
```

---

## 📚 Concepts Learned

- Understanding the Linux directory structure
- Navigating between directories
- Creating directories
- Creating empty files
- Writing and appending text to files
- Viewing file contents
- Removing files
- Removing empty directories
- Difference between `>` and `>>`
- Using relative directory paths

---

## ▶️ Sample Commands

```bash
pwd

cd Desktop

mkdir proj2

cd proj2

touch fil1

echo "1. Green shirt guy" > fil1
echo "2. Cloud with DevOps" >> fil1
echo "3. Hello World" >> fil1

cat fil1

rm fil1

cd ..

rmdir proj2
```

---

## 🎯 Learning Outcome

After completing this project, you will be able to:

- Navigate the Linux file system confidently.
- Create and manage directories.
- Create, edit, and view text files using terminal commands.
- Understand the difference between overwriting and appending data.
- Delete files and directories safely using Linux commands.

---

## 💻 Technologies Used

- Ubuntu Linux
- Bash Shell
- Linux Terminal

---

## 📸 Project Screenshot

Add your terminal screenshot here after uploading it to the repository.

Example:

```
project-screenshot.png
```

Then display it in GitHub using:

```markdown
![Project Screenshot](project-screenshot.png)
```

---

## 👨‍💻 Author

**Abhishek**

B.Tech Computer Science & Engineering

Learning Linux, DevOps, and Backend Development