# Beyond Pattern Completeness: Deciding Quasi-Reducibility in Left-Linear TRSs
Master's thesis
Vrije Universiteit Amsterdam
2025

### Abstract


Pattern completeness, as a property of functional programs, guarantees that
a function is exhaustively defined for all possible inputs of its type. When
modelling functional programs via term rewrite systems, pattern completeness
ensures that any basic term – a ground term that has a defined symbol at the
root position – can be rewritten at the top.
We adapt the decision procedure of Thiemann and Yamada [1] for pattern com-
pleteness to address quasi-reducibility, a related notion to pattern completeness
that ensures computation does not get stuck by permitting matches to happen
anywhere in the term.
The adaptation has three variations: first one considers strong quasi-reducibility
as per [2] as a stepping stone to arrive at the second variation addressing gen-
eral quasi-reducibility. Finally, the last version adapts the algorithm for sorted
applicative term rewriting. The correctness of the algorithms are demonstrated
by a termination argument and a soundness argument.


[Full thesis](https://github.com/koeves/msc-quasi/blob/main/Thesis__Beyond_Pattern_Completeness__Deciding_Quasi_Reducibility_in_Left_Linear_TRSs.pdf)
