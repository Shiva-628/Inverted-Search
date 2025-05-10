# 🔍 Inverted Search – File-Based Word Indexing System  
Author: Shiva K V   
Institute: Emertxe Information Technologies Pvt. Ltd.

## 📄 Overview
This project implements an **Inverted Index** — a data structure that maps each word to the list of files it appears in — allowing fast and efficient full-text search across multiple text files.

Inspired by search engine internals, this C-based project performs indexing and querying functionalities using data structures like linked lists and dynamic memory handling.

## 🎯 Objectives
- Build a searchable word-to-file map from a set of `.txt` documents.
- Support quick querying of words to retrieve the relevant file names.
- Store and reuse the index using a persistent database file.

## 🧠 Concepts Used
- Pointers and structures in C
- File handling and I/O
- Tokenization and filtering
- Linked lists and sorting
- Dynamic memory allocation

## 📋 Prerequisites
To understand and build this project, familiarity with the following is required:
- Basic C programming
- Dynamic memory allocation
- Data structures (Linked List, Hash Table)
- File handling (reading/writing)

## 💻 How to Compile & Run

### 🛠️ Compile
```bash
gcc main_index.c index.c -o index.out
gcc main_search.c search.c -o search.out


