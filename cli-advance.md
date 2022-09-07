## File Extension

To check all files with extension filter.
Syntax => `*.extension`

`*` stands for **_ any file name _**

Example =================================

### Remove all files with .txt extension

=> rm \*.txt

### Remove all files with .txt extension recursivly

=> rm -r **/*.txt
==> **/ is stands for all folders/

## Create file/folder (recursivly)

As we know, when we use mkdir or touch to create folders/files.
Syntax => `$ mkdir [argument] or $ touch [argument]`

### `argument` can be;

---

dir1
dir1 dir2
dir{1,2,3}
dir1/dir2/dir3(parent-child)

---

---

file.txt
file1.txt file2.txt
file{1,2,3,4,5,6}.txt

---

Example =================================

### Create files text1.txt ... text10.txt

=> touch text{1,2,3,4,5,6,7,8,9,10}.txt

### Create folder as parent/child folders and last folder will have a find.txt file.

=> mkdir -p folder1/folder2/folder3 | touch folder1/folder2/folder3/find.txt
==> `Here, "-p" flag will create the parent directory if it is not created already.`
