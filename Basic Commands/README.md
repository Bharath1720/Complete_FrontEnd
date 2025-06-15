# Super Simple Linux Commands Cheat Sheet

This is a collection of the most basic Linux commands, written in the easiest way possible—so simple that anyone can understand!  
Each command comes with an explanation and a real example.

---

## 1. Navigation Commands

- **`pwd`**  
  _Shows the folder you are in now._  
  **Example:**  
  ```
  pwd
  ```
  _Output might be:_  
  `/home/bharath`

- **`ls`**  
  _Shows files and folders in the current folder._  
  **Example:**  
  ```
  ls
  ```
  _Output:_  
  `file1.txt  myfolder  photo.png`

- **`cd foldername`**  
  _Go into a folder named "foldername"._  
  **Example:**  
  ```
  cd myfolder
  ```

- **`cd ..`**  
  _Go back to the previous folder (one step up)._  
  **Example:**  
  ```
  cd ..
  ```

- **`cd ../..`**  
  _Go back two folders (two steps up)._  
  **Example:**  
  ```
  cd ../..
  ```

- **`cd ~`**  
  _Go to your home folder._  
  **Example:**  
  ```
  cd ~
  ```

- **`cd /directory1/directory2`**  
  _Go directly to that folder path (absolute path)._  
  **Example:**  
  ```
  cd /home/bharath/Documents
  ```

---

## 2. Paths

- **Relative path:**  
  _A path from where you are now, NOT starting with `/`._  
  **Example:**  
  ```
  cd subfolder
  ```

- **Absolute path:**  
  _A path starting from the root `/`, the exact location._  
  **Example:**  
  ```
  cd /home/bharath/Documents
  ```

---

## 3. Listing Files

- **`ls -ls`**  
  _Shows files with more details and sizes._  
  **Example:**  
  ```
  ls -ls
  ```

- **`ls -a`**  
  _Shows all files, even hidden ones (files starting with a dot)._
  **Example:**  
  ```
  ls -a
  ```

- **`ls -lh`**  
  _Shows file sizes in a human way (KB, MB)._
  **Example:**  
  ```
  ls -lh
  ```

- **`ls -h`**  
  _Shows sizes in human way, often used with other `ls` options._
  **Example:**  
  ```
  ls -lh
  ```

---

## 4. Creating, Deleting, and Viewing

- **`mkdir foldername`**  
  _Make a new folder._
  **Example:**  
  ```
  mkdir newfolder
  ```

- **`mkdir folder1/subfolder`**  
  _Make a folder and a subfolder inside it._
  **Example:**  
  ```
  mkdir folder1/subfolder
  ```

- **`rmdir foldername`**  
  _Delete an empty folder._
  **Example:**  
  ```
  rmdir oldfolder
  ```

- **`rm -r foldername`**  
  _Delete a folder and everything inside it._
  **Example:**  
  ```
  rm -r unwantedfolder
  ```

- **`touch filename`**  
  _Make a new empty file._
  **Example:**  
  ```
  touch file.txt
  ```

- **`cat filename`**  
  _Show what is inside a file._
  **Example:**  
  ```
  cat notes.txt
  ```

- **`rm filename`**  
  _Delete a file._
  **Example:**  
  ```
  rm file.txt
  ```

- **`clear`**  
  _Clear the terminal screen._
  **Example:**  
  ```
  clear
  ```

- **`rm -rf foldername`**  
  _Force delete a folder and everything inside (no warning!)._
  **Example:**  
  ```
  rm -rf dangerousfolder
  ```
  **Warning:** This command deletes everything in that folder without asking!

- **`rm -rf /`**  
  _NEVER run this! It deletes your whole computer!_

---

## 5. Searching & Redirecting

- **`ls | grep something`**  
  _Show only files/folders matching "something"._
  **Example:**  
  ```
  ls | grep report
  ```
  _Shows only the files with "report" in the name._

- **`ls > file.txt`**  
  _Save the list of files into file.txt instead of showing on screen._
  **Example:**  
  ```
  ls > files.txt
  ```

---

## 6. Copying and Moving

- **`cp file1 file2`**  
  _Copy file1 to file2 (make a duplicate)._
  **Example:**  
  ```
  cp notes.txt backup.txt
  ```

- **`mv file1 file2`**  
  _Move or rename file1 to file2._
  **Example:**  
  ```
  mv oldname.txt newname.txt
  ```

---
