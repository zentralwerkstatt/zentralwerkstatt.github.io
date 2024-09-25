# A Syllogism in Turing's 1950 Paper

Scott Aaronsen famously maintains that "one can divide everything that's been said about artificial intelligence into two categories: the 70% that's somewhere in Turing's paper from 1950, and the 30% that's emerged from a half-century of research since then"[^1], and I very much agree with this sentiment. Among the many fascinating and clairvoyant arguments of the paper is a refutation of what Turing calls the "argument from informality of behavior". Turing writes:

> It is not possible to produce a set of rules purporting to describe what a man should do in every conceivable set of circumstances. One might for instance have a rule that one is to stop when one sees a red traffic light, and to go if one sees a green one, but what if by some fault both appear together? One may perhaps decide that it is safest to stop. But some further difficulty may well arise from this decision later. To attempt to provide rules of conduct to cover every eventuality, even those arising from traffic lights, appears to be impossible. With all this I agree. From this it is argued that we cannot be machines. I shall try to reproduce the argument, but I fear I shall hardly do it justice. It seems to run something like this. 'If each man had a definite set of rules of conduct by which he regulated his life he would be no better than a machine. But there are no such rules, so men cannot be machines.' The undistributed middle is glaring."[^2]

Contemporary machine learning, of course, has to deal with the similar problem of building models that generalize well not only in a probabilistic but also in a symbolic sense.[^3]

Because of this relevance it seems important to me to clarify the reasoning behind Turing's refutation, which requires an analysis of the [syllogism](https://en.wikipedia.org/wiki/Syllogism) employed here. Turing has already hinted at the fact that what we are dealing with here is a fallacy of the "undistributed middle". What does this imply? The following example can be found on [Wikipedia](https://en.wikipedia.org/wiki/Fallacy_of_the_undistributed_middle):

-   Major premise: All students carry backpacks.
-   Minor premise: My grandfather carries a backpack.
-   Conclusion: Therefore, my grandfather is a student.

This would only be true if we [distributed](https://en.wikipedia.org/wiki/Categorical_proposition#Distributivity) "carrying backpacks" in the major premise and added: everyone who carries a backpack is a student.

In Turing's case, we are dealing with the same structure:

-   Major premise: Each man (= all men) (A) have rules (X): all A is X.
-   *Implicit* minor premise: Machines (B) have rules (X): B is X.
-   Conclusion: All men are machines: all A are B.

X is the middle term because it appears in both the major and the minor premise. However, X (having rules) is not distributed in the major premise, as it is not also posited that all X are A, i.e. that "everyone who has rules, is a man". It may or may not be the case that all men have rules but this is irrelevant to the conclusion. What is relevant to the conclusion is whether it is true that all X are A, i.e. that "everyone who has rules, is a man" (as this would make "machines" also "men" and vice versa), which is ignored in the argument. The final conclusion ("there are no such rules, so men cannot be machines") does not hold exactly because the fact that all men have rules is irrelevant to the conclusion entirely.

---

[^1]: Scott Aaronsen, *Quantum Computing Since Democritus* (Cambridge University Press, 2013).

[^2]: Alan Mathison Turing, "Computing Machinery and Intelligence," *Mind* 59, no. 236 (1950), 452.

[^3]: Brendan Lake et al., "Building Machines That Learn and Think Like People," *Behavioral and Brain Sciences* 40 (2017); Gary Marcus, "Deep Learning: A Critical Appraisal," arXiv preprint 1801.00631, 2018.
