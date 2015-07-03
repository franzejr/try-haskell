#Haskell
Haskell is a purely-functional language, statically, implicitly typed, lazy.

#### Purely Functional
So in purely functional languages, a function has no side-effects. The only thing a function can do is calculate something and return it as a result. If you say that a variable a is equals to 8, we cannot say later that a is equals to 10. So, there is no liars on Purely Functional languages. That is called referential transparency. We may think it's a limiting, but let us thinkg better about that: if a functional always return the same thing, we can deduce things better and also we can create complex things by gluing simple functions together. It's more easy to test if we have those.

 - Referential Transparency (From Wikipédia)

This can help in proving correctness, simplifying an algorithm, assisting in modifying code without breaking it, or optimizing code by means of **memoization**, **common subexpression elimination**, **lazy evaluation**, or **parallelization**.

Referential transparency is one of the principles of functional programming; only referentially transparent functions can be memoized (transformed into equivalent functions which cache results). Some programming languages provide means to guarantee referential transparency. Some functional programming languages enforce referential transparency for all functions.

#### Lazy

#### Statically

#### Implicitily typed

### Everything is an object? What now ?

Most software developers are familiar with the OOP concepts, such as "everything is an object". Classes are a primary way to hiding implementation details and also a handy way to group related functionalities together. Haskell provides other solutions for these problems. So, when we have a classes we have the following features:
- Type with several representations
- Packing data & functions together
- Hiding implementation details
- Grouping related functionality

Let's see how Haskell can do those things for us.



