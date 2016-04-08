# dismathportfolio-aldoous
John Aldous A. Galay

11431768

#Week 1
- met DISMATH for the first time.
- learned about symbols for conditions and propositions.
  - learned that propositions could be either True(1) or False(0).
  - symbols are very confusing.
- learned about logical connectives.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| ∨ | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

#Week 2
- learned about truth tables.
- learned laws for logical equivalences: Identity, Domination, Negation, Double Negation, Idempotent, Commutative, Associative, Distributive, De Morgan's, and Absorption.

| Laws | Logical Equivalences |
| :-----: |:-------:|
| Identity Laws | p v F = p; p ∧ T = p |
| Domination Laws | p v T = T; p ∧ F = F |
| Negation Laws | p v ¬p = T; p ∧ ¬p = F |
| Double Negation Law | ¬(¬p) = p |
| Idempotent Laws | p v p = p; p ∧ p = p |
| Commutative Laws | p v q = q v p; p ∧ q = q ∧ p |
| Associative Laws | (p v q) v r = p v (q v r) |
| Distributive Laws | p v (q ∧ r) = (p v q) ∧ (p v r) |
| De Morgan's Laws | ¬(p ∧ q) = ¬p v ¬q |
| Absorption Laws | p v (p ∧ q) = p; p ∧ (p v q) = p |

#Week 3
 - learned about the rules of Inference.
 - an arguments validity does not tell its truth value.
 - Existential quantifiers denoted by (∃x) expresses that a proposition requires at least one member of the domain, "There Exists".
   - They are false if no element exists  
 - Universal quantifiers denoted by (∀x) expresses that a proposition requires every member of the domain, "All Exists".
   - They are false if a single element is false.

#Week 4
 - learned basic concepts about proof and how to build arguments.
 - learned some more methods of proving such as direct proof and proof by contrapositive.
  - direct proof is assuming that p is true and showing that q is true using the first assumption.
  - indirect proof is assuming the negation of p is true and showing that the negation of q is true using the first assumption. Basically, the opposite of a direct proof.
  - learned about more types of proofs:
    - Vacuous Proof is showing that p is false, because p → q must be true when p is false.
    - Trivial Proof is showing  that q is true because p → q must also be true.

#week 5
 - continued with more problems from last week... and learned about the proof by contradiction.
  - it is to show that the negation of a premise is true and lead to a contradiction.
 - learned about mathematical induction and recursive functions. <- they're confusing.
  - For Induction: Basis Step, then do an Inductive Step using the Direct proof.
  - For Recursive: Basis step, then the recursive step.
 - To prove having program correctness you would need: initial assertion, final assertion, and a segment.

#Week 6
 - introduction to sets which is easier than the previous lessons, though only by a little.
 - union, intersection, set difference and symmetrical difference.
  - union: A ∪ B
  - intersection: A ∩ B 
  - set difference: A - B or A \ B 
  - symmetrical difference: A ∆ B 
 - set identities are like those identities I've learned previously so I expect it to be as difficult.
 - cardinality isthe number of elements in a set, denoted by |S|.
  - Alephnull is a cardinality of infinite sets.

#Week 7
 - started discussing functions and its types and properties.
 - they have three types: one-to-one function, onto function, one-to-one correspondence.
 - one-to-one function, also known as injective, is a fuction that always assigns a value to each domain only once.
 - onto funtion, also known as surjective, is a function in which all its codomains have a designated value.
 - one-to-one function, also known as bijective, is a combination of an injective and surjective function.
 
#Week 9
 - the best part of DISMATH has startedm algorithms.
 - max() funtion was introduced.
 - Pseudocodes. 
 - Building an algorithm requires a precondition, procedure and postcondition.
 
#Week 9
 - Linear and binary search was introduced to me.
 - Bubble sort and Insertion sort are two different kinds of sorting algorithms.
 - Some examples were shown for algorithms.
 - the greedy algorithm and some coin algorithm was shown.
 - Growth of functions and the Big-O notation was introduced.
 - There are witnesses in growth of functions which are constants called C and k.

#Week 10
 - Growth of functions have expanded to Big-theta and Big-omega.
 - Big-omega is the lower bound to a function.
 - Big-theta is somewhat confusing because it is the combination of big-O and big-omega.
 - Time complexity is the number of operations a algorithm takes. It is very confusing.

#Week 11 
 - Graph Theory starts here. 
 - it is a somewhat easier topic than those in the past.
 - a graph is consists of an edge with vertices.
 - a degree is the number of edges are connected to a vertex.
 - Eulers read as -> oilers.
 - Path is finishing a certain path once.
 - Circuit is like a path but going back to the initial.
 - A Euler Circuit is a simple circuit that contains every edge of a graph.
  - nodes have all even degrees.
 - A Euler Path is a simple path than contains every edge of a graph.
  - exactly two nodes must be odd.
 - A Hamilton Circuit is a simple circuit that contains every node or vertex of a graph.
 - A Hamilton Path is a simple path that contains every node or vertex of a graph.
 - if two graphs have similar number of nodes then they are isomorphic.
 - Planar graphs do not have any edge that crosses with each other.
 - Nonplanar graphs can be known through Kuratowski's theorem which states that it must have a subgraph homeomorphic to a K33 or a K5 graph.

#Week 12
 - This is the last week of regular classes. 
 - We continued to study about graphs.
 - To color graphs, two adjacent edges must be colored with a different color.
 - Chromatic number is the least number of colors that can be assigned to a graph. 
 - Planar graphs follow the Four Color Theorem which states that it has a chromatic number of no greater than four.
 - Nonplanar graphs may have higher chromatic numbers.
 - A tree is a graph with no circuits. Parts/Terminology for a tree:
  - Roots
  - Parent
  - Child
 - If there are two or more trees then it is called a forest.
 - Leaves are those who do not have a child.
 - M-ary trees are trees that have m number of children at each node.
  - if it is a 2-ary tree, it is called a binary tree.
