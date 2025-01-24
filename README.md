# stat-450-lab3

Our first attempt at determining whether a relationship exists between bill length and bill depth within each species will be a linear regression model with interaction terms:

$\text{Bill depth} = \beta_0 + \beta_1 \text{Bill length} + \beta_2 \text{Chinstrap} + \beta_3 \text{Gentoo} + \beta_4 (\text{Bill length} \times \text{Chinstrap}) + \beta_5 (\text{Bill length} \times \text{Gentoo}) + \epsilon$

where $\text{Chinstrap}$ and $\text{Gentoo}$ are dummy variables that take the value 1 when species is Chinstrap or Gentoo, respectively, and 0 otherwise.

We must verify the assumptions that the residuals $\epsilon$ are independent and roughly Normally distributed with constant variance.
