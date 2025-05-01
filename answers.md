# CMPS 2200 Recitation 08

## Answers

**Name:** Joshua Haddad
**Name:** Zev Gaslin


Place all written answers from `recitation-08.md` here for easier grading.



- **1b)**
  
In the worst case each edge processed once for a total of |E| processes. Worst case has an insertion/removal at each edge which takes
log|E| work. Therefore the total work is the number of edges * the cost per edge which is |E|log|E|.
Work = O(|E|log|E|)


Algorithm is fully sequential with no room for parrilizaation because 1 edge cannot be calculated without knowing the distance that got it there. As in the previous case removal from each edge takes |E|log|E| time and must at worst be done for every |E| edges. 

Therefor:Span = O(|E|log|E|)

