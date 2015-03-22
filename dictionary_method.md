# Dictionary Method

> Each word has dictionary definitions

> Given a sentence, the goal is to find **defintion of word** that **most overlap** the meaning of the sentence.

### Collation Decision List (Yarowsky)

> A word has **two sences**

#### Ordered rules: $$collation \rightarrow sense$$
$$\log{\frac{p(sense_{A} | collocation_{i})}{p(sense_{B} | collocation_{i})}}$$

Ex.

- fish within window $$\rightarrow$$ $$bass_{1}$$
- striped bass $$\rightarrow$$ $$bass_{1}$$
- bass player $$\rightarrow$$ $$bass_{2}$$