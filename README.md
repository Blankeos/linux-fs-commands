# 😎 Essentials of File Management using the CLI on Linux

> by Carlo Antonio Taleon BSCS-4A

## How to Guide:

### 1️⃣ Navigation

```sh
cd dirname # change directory to dirname
ls # list files
```

- Tilde `~` - user's home directory
- Relative - `myPath`
- Absolute - `/myPath`
- Dot
  - `.` - current directory
  - `./` - current directory
  - `..` - parent directory
  - `./myPath` is the same as `myPath`

### 2️⃣ Creating/Deleting Folders & Files

- Create a single folder `mkdir folder1`
- Delete folders `rm -r folder1`
- Create multiple folders `mkdir folder1 folder2`
- Create nested folders `mkdir folder1`
- Working with spaces `mkdir "another file"` or `mkdir another\ folder`
- Create empty files `touch file.txt`
- Create files with content `cat > file.txt` and `Ctrl+D` when done.
- View files `cat file.txt`

### 3️⃣ Moving Folders/Files

- Move a single folder `mv folder1 folder2`
- Move a single file `mv file.txt folder2/file.txt` (You can also rename)
- Move multiple files:
  ```sh
  mv file1.txt file2.txt folder2 # folder2 is treated as the target directory
  # or
  mv -t folder2 file1.txt # you can also define the target directory with -t
  ```

### 4️⃣ Manipulating Files

- **Replace** on files `cat > file.txt` and `Ctrl+D` when done.
- **Concatenate** content on files `cat >> file.txt`

## Cheatsheet

```sh
mkdir # create directories
rm # delete files
cd # change directory
ls # list files on console
touch # create files without content
cat # create files with content, view files, concatenate files with `>`, replace with `>>`.
mv # move or rename files & directories
```
