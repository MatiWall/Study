# Quick calculation 2.1
Verify that for $A_1, A_2\in \mathcal{F}$ the intersection $A_1 \cap A_2$ is also in $\mathcal{F}$
## Solution
A $\sigma$-algebra is defined as:
1. $\mathcal{F}$ is nonempty
2. if $A\in \mathcal{F}$ then $A^C\in \mathcal{F}$
3. if $A_1, A_2,\ldots \in \mathcal{F}$ then $\cup_{n=1}^{N}A_n \in \mathcal{F}$

From definition 2 we know that $A_1^C$ and $A_2^C$ are also in $\mathcal{F}$ and from 3. that $A_1^C \cup A_2^C \in \mathcal{F}$. From the De Morgan's rule we know
$$
    \cap_{n=1}^{N}A_n = \left(\cup_{n=1}^N A_n^C\right)^C
$$
we see that  $A_1 \cap A_2 \in \mathcal{F}$