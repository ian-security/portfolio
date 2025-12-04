
# Bandit War Games
## Level 0
**goal:** Use `man` pages (for example `man ls` and `man du`).
**command:**
```bash
man ls
man du
```
## Level 1
**goal:** List files and inspect contents with `ls`, `file`, and `cat`.
**command:**
```bash
ls
cat filename
file filename
```
## Level 2
**goal:** Access files whose names begin with a dash (`-`).
**command:**
```bash
cat ./-filename
```
## Level 3
**goal:** Read a file that contains spaces in its name.
**command:**
```bash
cat "spaces in filename"
```
## Level 4
**goal:** List hidden files (dotfiles) using `ls -a`.
**command:**
```bash
ls -a
```
## Level 5
**goal:** Identify a file's type with `file` and display its contents with `cat`.
**command:**
```bash
file ./-file07
cat ./-file07
```
