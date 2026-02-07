# 🔎 Inverted Search using C

A C-based implementation of an Inverted Search system that indexes words from multiple files and enables efficient keyword-based searching using data structures.

This project builds an inverted index to map words to the files in which they appear.

---

## 🚀 Features

- 📂 Reads multiple input text files  
- 🧠 Builds an inverted index for fast searching  
- 🔍 Searches word occurrences across files  
- 📊 Displays file name and word frequency  
- 🔗 Uses Linked List for storing word and file details  
- ⚡ Efficient lookup using hashing technique  

---

## ⚙️ Working Principle

1️⃣ Read multiple text files.  
2️⃣ Extract words from each file.  
3️⃣ Normalize words (ignore case, remove special characters).  
4️⃣ Store each unique word in a main linked list (index list).  
5️⃣ For each word, maintain a sub-list containing:
   - File name  
   - Word occurrence count


6️⃣ When a search query is given:
   - Locate the word in the index  
   - Display corresponding file details and frequencies  

---

## 🧠 Data Structures Used

- 🔗 Linked List for main word index  
- 📁 Sub Linked List for file details  
- #️⃣ Hash table for faster word indexing  

---

## 📚 Concepts Used

- 📌 File handling in C  
- 🔗 Linked List implementation  
- 🧠 Hashing technique  
- 🔍 String processing and comparison  
- 📊 Frequency counting logic  

---


## 👨‍💻 Author

S Sreedhar
