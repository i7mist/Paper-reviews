Equality of Opportunity in Supervised Learning
==============================================

Moritz Hardt, Eric Price, Nathan Srebro
---------------------------------------

Link: [paper](http://ttic.uchicago.edu/~nati/Publications/HardtPriceSrebro2016.pdf)

This paper proposes a new notion of fairness: *oblivious*, which differs from the previous notion of "fairness through unawareness" and "demographic parity",
by depending only on the joint statistics of the predictor, the target and the protected attributes. The less mathematical explanation of their key idea is to make the true/false positive rate the same across data points that have different values of the protected attributes.
