# **Terminal Navigation Practice Sheet**

## **Objective**

To learn and practice basic terminal commands for navigating directories, creating folders, viewing files, and managing files using the command prompt or VS Code terminal.

## **1. Basic Terminal Commands**

| Command | Description                             |
| ------- | --------------------------------------- |
| `pwd`   | Displays the current working directory. |
| `ls`    | Lists files and folders (Linux/Mac).    |
| `dir`   | Lists files and folders (Windows).      |
| `cd`    | Changes the current directory.          |
| `cd ..` | Moves one directory backward.           |
| `mkdir` | Creates a new directory.                |
| `rmdir` | Removes an empty directory.             |
| `clear` | Clears the terminal (Linux/Mac).        |
| `cls`   | Clears the terminal (Windows).          |
| `touch` | Creates a new file (Linux/Mac).         |

## **2. Practice Tasks**

Perform the following tasks using your terminal.

**Task 1: Check Current Directory**

```
cd
```

**Task 2: Create a New Folder**

```
mkdir MyPractice
```

**Task 3: Open the Created Folder**

```
cd MyPractice
```

**Task 4: Create a New File**

Windows:

```
type nul > index.html
```

Linux/Mac:

```
touch index.html
```

**Task 5: List All Files**

Windows:

```
dir
```

Linux/Mac:

```
ls
```

**Task 6: Move Back to the Previous Directory**

```
cd ..
```

**Task 7: Clear the Terminal**

Windows:

```
cls
```

Linux/Mac:

```
clear
```

## **3. Practical Exercise**

Create the following folder structure using terminal commands:

```
MyPractice/
│
├── HTML/
│   └── index.html
│
├── CSS/
│   └── style.css
│
└── JavaScript/
    └── script.js
```

**Windows commands (VS Code Terminal):**

```
mkdir MyPractice
cd MyPractice

mkdir HTML CSS JavaScript

type nul > HTML\index.html
type nul > CSS\style.css
type nul > JavaScript\script.js

dir
```

## **4. Questions for Practice**

1. What is a terminal?
2. What is the use of the `cd` command?
3. Which command is used to create a new folder?
4. What is the difference between `cd` and `cd ..`?
5. Which command displays files and folders in Windows?
6. How can we create a new file using the terminal?

## **5. Conclusion**

I successfully practiced basic terminal navigation commands. I learned how to create folders, create files, navigate between directories, list files, and manage the terminal using different commands.

**Result:** Basic terminal navigation and file management commands were successfully practiced.