# CPSC 100 Interactive Demos

Interactive walkthroughs for CPSC 100: Introduction to Computer Programming at Selkirk College.

Each demo steps through a flow diagram one box at a time. As you follow the arrows, you can watch the variables, the output and the trace table change. Use **Next** / **Back**, or the arrow keys.

## Week 4: Branching

| Demo | What it shows |
|---|---|
| [Grade Classifier](https://rbrad070.github.io/cpsc100-demos/grade-classifier/) | Follow a score through an `if` / `else if` / `else` chain of diamonds. Swap the order of the tests to see why the strictest boundary must come first. |

## Week 5: Loops

| Demo | What it shows |
|---|---|
| [While Loop](https://rbrad070.github.io/cpsc100-demos/while-loop/) | Print the numbers from `num` up to 9. The test comes before the loop body, so the body can run zero times. |
| [Do..While Loop](https://rbrad070.github.io/cpsc100-demos/do-while/) | Keep asking for a menu option until the user picks 1 to 4. The loop body always runs at least once. |
| [Nested Loops](https://rbrad070.github.io/cpsc100-demos/nested-loops/) | An inner loop inside an outer loop. Watch the output grid fill one row at a time as `inner` resets for every row. |

## Week 6: Strings and Arrays

| Demo | What it shows |
|---|---|
| [Letter Counter](https://rbrad070.github.io/cpsc100-demos/count-letter/) | Walk a string one index at a time until the `'\0'` terminator, counting how many times a letter appears. |
| [Palindrome Checker](https://rbrad070.github.io/cpsc100-demos/palindrome/) | Move two indices, `left` and `right`, inward from both ends of a word, and use `break` to stop at the first mismatch. |
| [Array Index Explorer](https://rbrad070.github.io/cpsc100-demos/array-index/) | Read and write `marks[i]` for any index. C doesn't check bounds, so an out-of-range index quietly reads or overwrites a neighbouring variable. |
| [2D Array](https://rbrad070.github.io/cpsc100-demos/2d-array/) | Walk a 2D grid with a nested loop and watch each element light up in both the grid view and the single strip of memory C really uses (row-major order). |

You can type your own word into the string demos, or your own values into the 2D array demo, to see how the loop behaves.
