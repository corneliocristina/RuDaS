# RuDaS: Synthetic dataset generation code and evaluation tools for ILP

RuDaS (**S**ynthetic **Da**tasets for **Ru**le Learning), is a tool for generating synthetic datasets containing both facts and rules, and for evaluating rule learning systems, that overcomes the shortcomings of existing datasets and proper evaluation methods. 
* *highly parameterizable:* number of constants, predicates, facts, consequences of rules (i.e., completeness) amount of noise (e.g., wrong or missing facts) and kinds of dependencies between rules can be selected. 
* *assesses the performance* of rule learning systems by computing classical and more recent metrics, including a new one that we introduce.


### Code & Data

Code and Data are available &rarr; [HERE](https://github.com/IBM/RuDaS)

### Example of Dataset
**Rules.**
```
p3(X0,X1) :- p7(X1,X0).
p7(X0,X2) :- p6(X0,X1), p6(X1,X2).
p7(X1,X0) :- p9(X3,X1), p9(X1,X0).
```
**Facts.**
```
p9(c127,c381).
p6(c324,c291).
p3(c363,c354).
p7(c61,c96).
...
```

### Paper & Slides:

* [ILP publication](http://lr2020.iit.demokritos.gr/online/Cornelio.pdf)
* [Slides](https://github.com/IBM/RuDaS/tree/master/other/RuDaS_slides_ILP.pdf) presented at ILP @ IJCLR 2021
* [arXiv preprint](https://arxiv.org/abs/1909.07095)

### How to cite:

```latex
@inproceedings{cornelio_thost_rudas,
  author={Cristina Cornelio and Veronika Thost},
  Booktitle = {Proceedings of the {30th} International Conference on Inductive Logic Programming, ILP2020-21 @ IJCLR},
  title={Synthetic Datasets and Evaluation Tools for Inductive Neural Reasoning},
  Year = {2021}}
```
---


