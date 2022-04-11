---
published: false
---
## Virtual Memory Series

Topics to cover:
1. What is virtual memory
  1. Motivation: Keeping processes from trampling each other
  2. Also motivation: Paging out memory that's not in use (an extension of keeping processes from trampling each other)
  3. Also: Large virtual address space
  	1. Allocating 1GB is 50% of your max space in x86; Allocating 1Gb is .00078% of your max space on x64.
2. Using virtual memory: OS-level calls and what the standard library leaves out
  1. Notes on python's standard library
  2. `VirtualAlloc()` and `mmap()`
  3. Application: Dynamic array that never needs to be moved
    1. Could compare this performance with `std::vector`?
4. Mmap'd files
  5. Application: Loading files quickly
2. Malloc implementations


2. Aside: How To Find Out What Your Program Is Doing
  1. Primary sources: MSDN, linux man pages
  2. Examining source code
  3. Heap vs. Stack
