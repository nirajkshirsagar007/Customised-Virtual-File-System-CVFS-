# Customised-Virtual-File-System-CVFS-
a UNIX-inspired in-memory file system emulator with custom data structures, system call–like commands, and a user-friendly CLI.

This project implements a **Virtual File System (VFS)** in C++ language.  
It mimics basic UNIX-like file operations such as create, open, read, write, close, delete, and more — all inside memory, without using the actual OS file system.

---

## 📌 Project Overview

In this project we emulate all **data structures** which are used by the Operating System to manage file system–oriented tasks.

- As the name suggests, it is **virtual** because we maintain all records in **primary storage (RAM)**.
- We create all data structures required for File Subsystems such as:
  - Inode  
  - Inode Table  
  - File Table  
  - UAREA  
  - User File Descriptor Table (UFDT)  
  - Superblock  
  - Disk Inode  
  - List Block  
  - Data Block  
  - Boot Block  
- We provide implementations of all necessary system calls and commands of the File Subsystem:
  - `open`, `close`, `read`, `write`, `lseek`, `create`, `rm`, `ls`, `stat`, `fstat`, etc.
- While implementing these functionalities, we design our **own data structures** by referring to algorithms of **UNIX Operating Systems**.

---

## ✨ Features
- Create and manage regular files in memory
- Support for file permissions: **Read / Write / Read+Write**
- File operations: **open, close, read, write, lseek, truncate, delete**
- Commands similar to UNIX (`ls`, `stat`, `rm`, etc.)
- In-memory file system with **superblock** and **inode** structure
- Easy-to-use CLI with `help` and `man` commands

---
