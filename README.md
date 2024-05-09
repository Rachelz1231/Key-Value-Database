# Database System
Group Project by Jonathan Lam, Ching Hui, Yuchen Zeng

This project involved the development of a comprehensive database management system that was implemented in stages. Initially, it featured an in-memory data structure (Memtable) using an AVL tree for efficient data management and operations like insertions and queries. This was expanded to include a durable component with Sorted String Tables (SSTs) for data persistence. In subsequent phases, the system incorporated advanced features such as a buffer pool for caching and faster data retrieval, static B-Trees for structured storage, and Bloom filters within an LSM-tree structure to enhance performance by minimizing unnecessary disk accesses. Each stage of development included rigorous testing and performance analysis, ensuring the system's functionality and efficiency in handling large datasets and complex operations like scans, updates, and deletions.

To compile code run: `make`

To run executable run: `make run`

To remove executable run: `make clean`

The unittests for all tests will be located in tests/tests run it by executing `./tests/tests`

To make a unittest, create the file in the `tests` folder and follow the strucutre the other test files have. Then add that file to the `main_test.cc` file to run all tests.
