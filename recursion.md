RECURSION

1. Base Case
   Condition that stops recursion.

2. Recursive Case
   Solve a smaller version of the same problem.

3. Trust the Function
   Assume recursive calls work correctly.

Example:

fib(5)
= fib(4) + fib(3)

Don't think about all calls at once.
Think:
"If fib(4) and fib(3) work,
then fib(5) works."

4. Recursion Tree

fib(4)
├── fib(3)
└── fib(2)

Visualize recursive calls as a tree.
