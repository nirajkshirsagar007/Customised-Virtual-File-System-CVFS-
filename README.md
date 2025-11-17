# Customised Virtual File System (CVFS)

A custom implementation of a Virtual File System (VFS) built entirely in **C Programming**.  
This project simulates the core functionality of the Linux file system and provides a custom shell interface to interact with the virtual environment.

---

## 🚀 Project Overview
The CVFS project offers a practical understanding of:
- System calls
- File handling
- Memory management
- Operating system internals

It mimics the Linux file system by implementing core system calls and custom data structures, while remaining platform-independent.

---

## ✨ Key Features
- **Custom Shell Interface**
  - Linux-like commands for file operations (`create`, `open`, `read`, `write`, `delete`, `ls`, `exit`).
- **System Call Simulation**
  - Implements `open`, `read`, `write`, `lseek`, `close`, `rm`, etc.
- **File System Data Structures**
  - Incore Inode Table  
  - File Table  
  - UAREA (User Area)  
  - User File Descriptor Table
- **Platform Independent**
  - Works across operating systems.
- **Database-like Functionality**
  - Structured file handling with a customised database management layer.

---

## 📚 Learning Outcomes
- Deep understanding of Linux File System internals.
- Practical knowledge of OS data structures (inode, file tables, UAREA).
- Strong grasp of system programming in C.
- Hands-on experience with shell design & command interpreter.
- Application of low-level logic building for OS-like environments.

---

## 🖥️ Example Usage
```bash
$ ./Myexe
Marvellous CVFS> create Demo.txt
Marvellous CVFS> write Demo.txt "Jay Ganesh"
Marvellous CVFS> read Demo.txt
Jay Ganesh
Marvellous CVFS> ls
Demo.txt
Marvellous CVFS> rm Demo.txt
Marvellous CVFS> exit
