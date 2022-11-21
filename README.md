# DATA STRUCTURES AND ALGORITHMS
## ALGORITHMS

Algorithm is a set of well-defined instructions to solve a problem.

### Characteristics
1. Well defined inputs and outputs
2. Each step of the algorithm is clear and unambiguous
3. It should be language independent.

### Efficiency / Performance of an algorithm

The runtime of an algorithm depends on the programming language, the computer used to implememnt the program on, other programs running at the same time quanlity of the operating system.

<u>Time complexity</u> -- time taken by the algorithm to run as a function of input time.<br/>
<u>Space complexity</u> -- Space complexity is the amount of memory taken by the algorithm to run, as a function of input size.
<br/>
If your app needs to quick and has plenty of memory to work with, you don't have to worry about space complexity. If you have little memory to work with, you should pick a solution that is relatively slower but need less space.

## Representation of complexity
*Asymptotic notations* -- mathematical tools to represent time and space complexity.
These include the following :
1. Big O Notation (O - Notation) -- worst case complexity
2. Omega Notation (&Omega; - Notation) -- best case complexity
3. Big O Notation (&Theta; - Notation) -- average case complexity

We focus on Big O Notation which describes the complexity of an algorithm using algebraic terms.

### Characteristics of the Big O Notation

- It is expressed in terms of the input.
- It focuses on the bigger picture -- the part of the algorithm with the most impact.

<table>
  <tr>
    <th>Big O Notation</th>
    <th>Symbol</th>
    <th>Example Algorithms</th>
  </tr>
  <tr>
    <td>Constant</td>
    <td>O(1)</td>
    <td>Sorting Algorithms</td>
  </tr>
  <tr>
    <td>Linear</td>
    <td>O(n)</td>
    <td>Sum of all first Natural Numbers</td>
  </tr>
  <tr>
    <td>Quadratic</td>
    <td>O(n^2)</td>
    <td>Functions with nested for loops</td>
  </tr>
  <tr>
    <td>Cubic</td>
    <td>O(n^3)</td>
   <td>Functions with 2 nested for loops</td>
  </tr>
  <tr>
    <td>Logarithmic</td>
    <td>O(log n)</td>
  </tr>
</table>
