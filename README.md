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

