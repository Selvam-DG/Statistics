## SAMPLE SPACE AND EVENTS
- The set of all possible outcomes of an experiment is known as the sample space of the experiment and is denoted by S.
- Any subset E of the sample space is known as an event
- For any two events E and F of a sample space S, we define the new event E ∪ F, called the union of the events E and F, to consist of all outcomes that are either in E or in F or in both E and F. That is, the event E ∪ F will occur if either E or F occurs.
- For any two events E and F, we may also define the new event EF, called the intersection of E and F, to consist of all outcomes that are in both E and F. That is, the event EF will occur only if both E and F occur
- If EF =∅, implying that E and F cannot both occur, then E and F are said to be **mutually exclusive**
- For any event E, we define the event Ec(E_complement), referred to as the complement of E, to consist of all outcomes in the sample space S that are not in E. That is, Ec will occur if and only if E does not occur
- If E ⊂ F and F ⊂ E, then we say that E and F are equal (or identical) and we write E = F.
## VENN DIAGRAMS AND THE ALGEBRA OF EVENTS
![Screenshot 2023-12-28 190612](https://github.com/Selvam-DG/Statistics_-and_R_programming/assets/98681717/ad7f7fb4-2456-4757-97b8-9ed5a180aabb)

- **Commutative law**:
 -  E ∪ F = F ∪ E ;   EE FE

- **Associative law**
  - (E ∪ F) ∪ G = E ∪ (F ∪ G) ;  (EF)G = E(FG)
- **Distributive law**
    - (E ∪ F)G = EG ∪ FG ;   EF ∪ G = (E ∪ G)(F ∪ G)
- **DeMorgan’s laws.**:
    - (E ∪ F)complement = EcFc ;    (EF)c = Ec ∪ Fc

## AXIOMS OF PROBABILITY:
1.  0 ≤ P(E ) ≤ 1
2.  P(S ) = 1
3.  Probability of union of all events = summation of the probability of individual events, if all events are mutually exclusive
 [Screenshot 2023-12-28 191758](https://github.com/Selvam-DG/Statistics_-and_R_programming/assets/98681717/5773ef3d-85b4-4cb2-b7fb-64f0eb13f788)
- We first note that E and Ec are always mutually exclusive, and since E ∪ Ec = S
    - 1 =P(S) =P(E ∪ Ec) = P(E) + P(Ec)
- PROPOSITION
  - P(Ec) = 1 - P(E)
  - P(E ∪ F) = P(E ) + P(F) − P(EF)

## SAMPLE SPACES HAVING EQUALLY LIKELY OUTCOMES
- Generalized Basic Principle of Counting
    - If r experiments that are to be performed are such that the first one may result in any of n1 possible outcomes, and if for each of these n1 possible outcomes there are n2 possible outcomes of the second experiment, and if for each of the possible outcomes of the first two experiments, there are n3 possible outcomes of the third experiment, and if, ..., then there are a total of n1 ·n2 ···nr possible outcomes of the r experiments
- P(E) = Number of possible outcomes of Event E / Total sample Space (E/S)

## CONDITIONAL PROBABILITY
-  Let E and F denote some events, the conditional probability of E given that F has occurred and is denoted by P(E|F )
  - P(E|F ) = P(EF)/P(F )
    [image](https://github.com/Selvam-DG/Statistics_-and_R_programming/assets/98681717/bbe86d98-5ab3-41fe-abd6-37cc936b43af)
  - Note the above equation is well defined only when P(F )>0andhenceP(E|F )is defined only when P(F )>0
