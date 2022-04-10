---
published: false
---
## Virtual Memory Series

Topics to cover:
1. What is virtual memory
  1. Motivation: Keeping processes from trampling each other
  2. Also motivation: Paging out memory that's not in use (an extension of keeping processes from trampling each other)
  3. Also: Large virtual address space
2. OS-level calls and what the standard library leaves out
  1. Notes on python's standard library
2. Malloc implementations
3. Swap files
4. Mmap'd files
  5. Application: Loading files quickly


2. Aside: How To Find Out What Your Program Is Doing
  1. Primary sources: MSDN, linux man pages
  2. Examining source code
  3. Heap vs. Stack 