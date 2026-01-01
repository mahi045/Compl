# cmodels
The repository is taken from the codebase of SAT-based ASP solver [Cmodels](https://www.cs.utexas.edu/users/tag/cmodels/).

# How to Run
```
gringo -o smodels ex1.lp | ./cmodels -dimacs -output ex1
```

-output `ex1` means that the name of QCNF file will be `qcnf_ex1.qcnf`