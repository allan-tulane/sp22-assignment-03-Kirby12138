# CMPS 2200 Assignment 3
## Answers

**Name:**____________Dachen Ni_____________


Place all written answers from `assignment-03.md` here for easier grading.


- **b.**
The `parens_match_iterative` function iterate the whole list one by one. Thus, its work is O(n). Since the whole process is sequential, leaving no space for parallelism, then its span is S(n) = O(n).

- **d.**
The `parens_match_scan` first map each element in mylist to 1 and -1 using `parens_map` function. Then, by implementing the efficient scan using contraction, the total work is W(n) = W(n/2)+ O(n) = O(n). Its span is S(n) = S(n/2)+O(1) in O(lg n).


- **f.**
Since the merging step is O(1), the total work is W(n)=2W(n/2)+O(1) = O(N) and its span is S(n) = S(n/2)+O(1) = O(log n).
