# Linux Cheatsheet – Day 2

## Navigation

### `pwd`
Displays the full path of the current working directory.

```bash
pwd
```

---

### `ls`
Lists the contents of the current directory.

```bash
ls
```

Useful options:

```bash
ls -l    # Long listing format
ls -a    # Show hidden files
ls -la   # Long listing with hidden files
```

---

### `cd`
Changes the current directory.

```bash
cd linux
```

Special cases:

```bash
cd ..
```

Move up one directory.

```bash
cd ~
```

Go to the home directory.

```bash
cd /
```

Go to the root directory.

---

## Files and Directories

### `mkdir`
Creates a new directory.

```bash
mkdir scripts
```

Create nested directories:

```bash
mkdir -p projects/python/day2
```

---

### `touch`
Creates an empty file.

```bash
touch hello.py
```

---

### `cp`
Copies a file or directory.

Copy a file:

```bash
cp hello.py backup.py
```

Copy a directory:

```bash
cp -r project backup
```

---

### `mv`
Moves or renames a file or directory.

Move a file:

```bash
mv hello.py python/
```

Rename a file:

```bash
mv old.txt new.txt
```

---

### `rm`
Removes a file.

```bash
rm file.txt
```

Remove a directory and its contents:

```bash
rm -r project
```

> **Warning:** Files deleted with `rm` are not moved to a recycle bin.

---

### `rmdir`
Removes an empty directory.

```bash
rmdir scripts
```

---

## Useful Commands

### `tree`
Displays the directory structure in a tree format.

```bash
tree
```

---

### `history`
Shows previously executed commands.

```bash
history
```

---

### `clear`
Clears the terminal screen.

```bash
clear
```

---

## Package Management

### `sudo apt update`
Updates the package index.

```bash
sudo apt update
```

---

### `sudo apt install`
Installs a package.

```bash
sudo apt install tree
```

---

## Useful Keyboard Shortcuts

- **Tab** – Auto-complete commands and file names.
- **↑ (Arrow Up)** – Recall the previous command.
- **Ctrl + C** – Stop the currently running command.