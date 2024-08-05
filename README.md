# C - Binary Trees

![C Programming](https://img.shields.io/badge/C-Programming-blue.svg)
![Holberton School](https://img.shields.io/badge/Holberton-School-red.svg)

## Description

This repository contains programs written for the Binary Trees project at Holberton School. In this project, we explore the concept of binary trees, their implementation, and various operations that can be performed on them using the C programming language.

## Project Overview

* **Team:** Project to be done in teams of 2 people
  - Fassih Belmokhtar
  - Salomon Diallo
* **Due time** 1 week 

## Objectives to assimilate 

The objectives of this project, you should be able to explain:

* The structure of a binary tree: a root node with at most two children per node
* Types of binary trees: simple binary trees vs binary search trees (BST)
* Advantages of binary trees: efficiency for searching, insertion, and deletion
* Tree properties: depth, height, and size
* Traversal methods: preorder, inorder, and postorder
* Special forms of trees: complete, full, perfect, and balanced
* Implementation in C: using structures and pointers

## Requirements

* Ubuntu 20.04 LTS
* gcc compiler with flags: -Wall -Werror -Wextra -pedantic -std=gnu89
* Betty style compliant code
* No global variables
* No more than 5 functions per file
* Allowed to use the standard library

## Project Files

* `binary_trees.h`: Header file with all function prototypes and data structures
* Various C files implementing binary tree operations

## Data Structures

```c
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
typedef struct binary_tree_s bst_t;
typedef struct binary_tree_s avl_t;
typedef struct binary_tree_s heap_t;
```

## Author

* **Noziop** - [GitHub Profile](https://github.com/Noziop)
* **M02laleague** - [GitHub Profile](https://github.com/M02laleague)

## Acknowledgments

* **Holberton School** - providing the opportunity to learn and grow as a software engineer

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


<p align="center">
  <img
   src="https://cdn.prod.website-files.com/64107f65f30b69371e3d6bfa/65c6179aa44b63fa4f31e7ad_Holberton-Logo-Cherry.svg"
   alt="Holberton School logo">
</p>
