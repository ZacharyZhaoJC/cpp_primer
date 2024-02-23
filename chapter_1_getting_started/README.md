# Chapter 1 : Getting Started

The way to learn a new programming language is to write programs. In this
chapter, we’ll write a program to solve a simple problem for a bookstore.

Our store keeps a file of transactions, each of which records the sale of one
or more copies of a single book. Each transaction contains three data elements:

    0-201-70353-X 4 24.99

The first element is an ISBN (International Standard Book Number, a unique book
identifier), the second is the number of copies sold, and the last is the price
at which each of these copies was sold. From time to time, the bookstore owner
reads this file and for each book computes the number of copies sold, the total
revenue from that book, and the average sales price.

To be able to write this program, we need to cover a few basic C++ features. In
addition, we’ll need to know how to compile and execute a program.

Although we haven’t yet designed our program, it’s easy to see that it must

#### • Deﬁne variables

#### • Do input and output

#### • Use a data structure to hold the data

#### • Test whether two records have the same ISBN

#### • Contain a loop that will process every record in the transaction file

We’ll start by reviewing how to solve these sub-problems in C++ and then write
our bookstore program.