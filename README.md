# lab03-grammars

# Jiefu Ling and Shixuan Fang
# Wheat Grammar
Premise: F \
Angle: 20 \
Rule: F->FF[-FF]F[-FF]FF- \
<img width="500" alt="square1" src="https://github.com/Jeff-Ling/lab03-grammars/blob/main/1.png">
<img width="500" alt="square2" src="https://github.com/Jeff-Ling/lab03-grammars/blob/main/2.png">
<img width="500" alt="square3" src="https://github.com/Jeff-Ling/lab03-grammars/blob/main/3.png">

# Square Grammar
Premise: +F \
Angle: 90 \
Rule: F->F-F+F+F-F \
<img width="500" alt="square1" src="https://github.com/Jeff-Ling/lab03-grammars/blob/main/4.png">
<img width="500" alt="square2" src="https://github.com/Jeff-Ling/lab03-grammars/blob/main/5.png">
<img width="500" alt="square3" src="https://github.com/Jeff-Ling/lab03-grammars/blob/main/6.png">

# Custom Plant
Branch: \
  Premise: FFFA \
  Angle: 30 \
  Rule: A->[B]////[B]////[B] \
        B->-FFFAK \

Leaf: \
  Premise: [A][B] \
  Angle: 20 \
  Rule: A->[+A{.].C.} \
        B->[-B{.].C.} \
        C->FFFC \ \
<img width="500" alt="square1" src="https://github.com/Jeff-Ling/lab03-grammars/blob/main/7.png">
<img width="500" alt="square2" src="https://github.com/Jeff-Ling/lab03-grammars/blob/main/8.png">
<img width="500" alt="square3" src="https://github.com/Jeff-Ling/lab03-grammars/blob/main/9.png"> \

**Rule Definitions:**
1. **Rule 1**: Utilized for constructing the primary branches.
2. **Rule 2**: Appended a rotated line at the termination of each branch to simulate the finer nuances of branch formations.

**Leaf Representation:**
- In our design, the symbol `K` stands for the leaf. This leaf structure is modeled using another L-system.

**Leaf Generation:**
- To visualize the leaf, we employ polyton triangles. By connecting these triangles, we achieve a detailed representation of the leaf structure.

## 1. Wheat grammar puzzle
Look at these iterations (n = 1, 2, 3) of a one-rule grammar. Using the built in symbols in Houdini, design a grammar that produces this output. Take a screenshot of your rules.\
<img width="200" alt="square1" src="https://user-images.githubusercontent.com/1758825/193949661-a3a0e1f7-7d68-4b9e-8384-d9991e1e9fd2.png">
<img width="200" alt="square2" src="https://user-images.githubusercontent.com/1758825/193949853-cf2306b3-3537-4c24-91b5-0a3083bc87c0.png">
<img width="200" alt="square3" src="https://user-images.githubusercontent.com/1758825/193949859-5e432b4b-f18d-48b5-a9e9-8d7dba255955.png">

## 2. Square grammar puzzle
How about this one? Take a screenshot of your rules.\
<img width="200" alt="square1" src="https://user-images.githubusercontent.com/1758825/193949895-87cdfb43-da7c-4867-ab1b-107e1ba9d2a7.png">
<img width="200" alt="square2" src="https://user-images.githubusercontent.com/1758825/193949904-a9cdfe0f-319e-4ca8-9935-dd338217a7cf.png">
<img width="200" alt="square3" src="https://user-images.githubusercontent.com/1758825/193949910-928e5993-ce26-4681-80f8-ffeb54be4dcf.png">

## 3. Custom plant
Choose a plant in the world. Working off a reference, design a grammar that mimics the structure of that plant. Unlike our simple puzzles, please use multiple rules for greater complexity. Think carefully about the structure of your grammar! EXPLAIN the structure of your plant in the README. What are the components? What do each of the rules do? Be sure to also include images of a few iterations of your output plant. 

## Submission
- Create a pull request against this repository
- In your readme, list your solutions and format your README nicely
- Profit
