0x18. C - Dynamic libraries

Requirements
*   Allowed editors: `vi`, `vim`, `emacs`.
*   All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options `-Wall -Werror -Wextra -pedantic -std=gnu89`.
*   Your code should use the `Betty` style. It will be checked using `betty-style.pl` and `betty-doc.pl`.
*   All your files should end with a new line.
*   You are not allowed to use global variables.
*   No more than 5 functions per file.
*   You are allowed to use the standard library.
*   The `main.c` files are used to test your functions, but you don’t have to push them to your repo.
*   The prototypes of all your functions should be included in your header file called `hash_tables.h`.
*   All your header files should be include guarded.

Project Description
Learn about what is a hash function.
What makes a good hash function.
What is a hash table, how do they work and how to use them.
What is a collision and what are the main ways of dealing with collisions in the context of a hash table.
What are the advantages and drawbacks of using hash tables.
What are the most common use cases of hash tables.


0. >>> ht = {} - Write a function that creates a hash table.
	File: `0-hash_table_create.c`.
1. djb2 - Write a hash function implementing the djb2 algorithm.
	File: `1-djb2.c`.
2. key -> index - Write a function that gives you the index of a key.
	File: `2-key_index.c`.
3. >>> ht['betty'] = 'cool' - Write a function that adds an element to the hash table.
	File: `3-hash_table_set.c`.
4. >>> ht['betty'] - Write a function that retrieves a value associated with a key.
	File: `4-hash_table_get.c`.
5. >>> print(ht) - Write a function that prints a hash table.
	File: `5-hash_table_print.c`.
6. >>> del ht - Write a function that deletes a hash table.
	File: `6-hash_table_delete.c`.
7. $ht['Betty'] = 'Cool' - Rewrite the previous functions using the given data structures
	File: `100-sorted_hash_table.c`.