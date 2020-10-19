# Fairness Measurement


### Anti-classification
Decisions do not consider protected attributes.

$$
d(x)=d(x') \: for \, all \: x, x'  \: such \, that \: x_u =x'_u.
$$

> *[The Measure and Mismeasure of Fairness: A Critical Review of Fair Machine Learning](https://arxiv.org/pdf/1808.00023.pdf)*


### Classification Parity
Some given measure of classification error is equal across groups defined by the protected attributes.
- Parity in the proportion of positive decisions are known as demographic parity.
$$
Pr(d(X))
$$



> *[The Measure and Mismeasure of Fairness: A Critical Review of Fair Machine Learning](https://arxiv.org/pdf/1808.00023.pdf)*

### Calibration
