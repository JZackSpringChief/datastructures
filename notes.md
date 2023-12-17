Intro to Data Structures

Abstract data type(ADT) is a mathematical model for data types, where a data type is defined by its behavior (semantics) from the point of view of a user of the data, specifically in terms of possible values, possible operations on data of this type, and the behavior of the operations.

A data structure is a data organization, management and storage format that enables efficient access and modification. More precisely, a data structure is a collection of data values, the relationships among them, and the functions or operations that can be applied to the data.

- ADT is an abstract description of how a specific set of data can be organized and which operations can be performed on that set of data.
- A data structure is a concreate implementation of an ADT.
- ADT can describe a stack as a data type which allows to store data and perform Push, Pop, Peek operations.
- Stack has an abstract definition and a concreate implementation.
- Data structures are based on primitive data types(int, string etc.)
- Primitive data types are basic building blocks.

Intro to Algorithms

- Algorithm is a correctly defined computational procedure which has an input and an output.
- Algorithm is a sequence of steps transforming an input to an output.
- We need algorithms for solving correctly defined computational problems.
- Algorithm is always formalized and it non-ambiguously defines the computatinsal procedure for reaching the desired results.

Example of a sorting problem:

- Input: a sequence of N numbers <a1, a2, a3, ...an>
- Output: a permutations(reordering)<a'1, a'2, a'3, ...a'n>

instance of a problem: <12, 10, 7, 2, 8, 3>
Output:<2, 3, 7, 8, 10, 12>

- Algorithm is correct if for any input(correct) it produces a correct output.
- Algorithm includes:
  - description of correct input
  - full description of computational steps
  - description of a correct output
- Algorithms often provide an implementation in pseudo-code.

ex of psudo code.
for j = 2 to A.length
key = A[j];
//insert A[j] into the soted sequence A[1..j-1]
i = j - 1
while i > 0 and A[i] > key
do A[i+1] = A[i]
i = i -1
A[i+1] = key

Intro to Algorithm Analysis

- how much time will out algorithm take for solving a problem?
- how much memory will our algorithm consume for solving a problem?
