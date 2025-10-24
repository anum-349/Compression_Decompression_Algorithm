# 📦 File Compression and Decompression System

*A simple C++ project to compress and decompress files using Run-Length Encoding (RLE)*

---

## 🧩 **Overview**

This project implements a **File Compression and Decompression System** using the **Run-Length Encoding (RLE)** algorithm in **C++**. It reduces file size by replacing consecutive repeating bytes with a single instance and a count. The system can compress and decompress any binary file (e.g., `.docx`, `.txt`, `.bin`) while maintaining data integrity.

---

## ⚙️ **Features**

* 🔹 Compress files using **Run-Length Encoding**
* 🔹 Decompress files back to their original format
* 🔹 Handles both **text and binary files**
* 🔹 Simple **menu-based interface** for user interaction
* 🔹 Demonstrates file handling and byte-level operations in C++

---

## 🧠 **How It Works**

* The **Compress()** function scans the file and replaces consecutive identical bytes with a count and the character.
* The **DeCompress()** function reconstructs the original data by repeating each byte according to its count.
* Files are read and written in **binary mode** to preserve their format.

---

## 🧰 **Technologies Used**

* **Language:** C++
* **Algorithm:** Run-Length Encoding (RLE)
* **Libraries:**

  * `<fstream>` for file handling
  * `<vector>` for dynamic storage
  * `<iostream>` for console input/output

---

## 🚀 **How to Run**

### 1. **Compile the program**

```bash
g++ compression.cpp -o compression
```

### 2. **Run the executable**

```bash
./compression
```

### 3. **Follow the menu options:**

```
1: Compress File
2: DeCompress File
3: Exit
```

### 4. **File Setup:**

* Place the file you want to compress as `compression.docx` in the project directory.
* The program will generate:

  * `Compressed.txt` → compressed version of your file
  * `DeCompressed.docx` → restored version after decompression

---

## 📊 **Example Workflow**

1️⃣ Select option **1** to compress `compression.docx`.
2️⃣ The program generates a compressed file named `Compressed.txt`.
3️⃣ Select option **2** to decompress it back into `DeCompressed.docx`.
4️⃣ Compare both files to verify accuracy.

---

## 🎯 **Outcome**

The project successfully demonstrates the **fundamental concept of data compression**, reducing file size for repetitive data and accurately restoring original files during decompression. It enhanced understanding of **file I/O operations**, **binary data handling**, and **algorithmic logic implementation in C++**.
