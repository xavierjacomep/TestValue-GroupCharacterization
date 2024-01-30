# TestValue-GroupCharacterization

Test Vaue Criterion is mainly used for the characterization of a group of observations according a variable, continuous or categorical.
The groups should be defined by categories from a discrete variable (e.g. clustering label, a node of a decision tree, etc.).

**Principle**

Test value compares the values of a descriptive statistic indicator computed on the whole sample and computed on sub sample related to the group.
- *Continuous:* It compares the mean.
- *Categorical:* It compares the proportion.

**Formulation**

The formulation was taken from Lebart et al.'s book (2001).

***Comparison according a continuous variable:***

![t_c=\frac{{\mu_g - \mu}}{{\sqrt{\frac{{n - n_g}}{{n - 1}} \times \frac{{\sigma^2}}{{n_g}}}}](https://latex.codecogs.com/svg.latex?t_c=\frac{{\mu_g%20-%20\mu}}{{\sqrt{\frac{{n%20-%20n_g}}{{n%20-%201}}%20\times%20\frac{{\sigma^2}}{{n_g}}}})

Where:
- ![X](https://latex.codecogs.com/svg.latex?X) is a continuous variable.
- ![\mu](https://latex.codecogs.com/svg.latex?\\mu) is the mean computed on the whole sample.
- ![sigma^2](https://latex.codecogs.com/svg.latex?\sigma^2) is the empirical variance.
- ![\mu_g](https://latex.codecogs.com/svg.latex?\\mu_g) is the mean computed into the group.
- ![n](https://latex.codecogs.com/svg.latex?n) is the total number of elements on the whole sample.
- ![n_g](https://latex.codecogs.com/svg.latex?n_g) is the total number of elements into the group.

***Comparison according a categorical (discrete) variable:***

![t_d=\frac{{n_{jg} - \frac{{n_g \times n_j}}{n}}}{{\sqrt{\frac{{n - n_g}}{{n - 1}} \times \left(1 - \frac{{n_j}}{n}\right) \times \frac{{n_g \times n_j}}{n}}}}](https://latex.codecogs.com/svg.latex?t_d=\frac{{n_{jg}%20-%20\frac{{n_g%20\times%20n_j}}{n}}}{{\sqrt{\frac{{n%20-%20n_g}}{{n%20-%201}}%20\times%20\left(1%20-%20\frac{{n_j}}{n}\right)%20\times%20\frac{{n_g%20\times%20n_j}}{n}}}})


Where:
- ![n](https://latex.codecogs.com/svg.latex?n) is the total number of elements on the whole sample.
- ![n_g](https://latex.codecogs.com/svg.latex?n_g) is the total number of elements into the group.
- ![n_j](https://latex.codecogs.com/svg.latex?n_j) is the total number of elements into the category on the whole sample.
- ![n_j_g](https://latex.codecogs.com/svg.latex?n_j_g) is the total number of elements into the category into the group.

Use the Test Value criterion to characterize and differentiate groups, which allows for understanding the distinguishing features of each.
