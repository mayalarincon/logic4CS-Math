# logic4CS-Math

## Supplementary materials for "Applied Logic for Computer Scientists and Mathematicians"  
By Mauricio Ayala-Rincón, Flávio Leonardo Cavalcanti de Moura, and Thaynara Arielly de Lima

This repository includes supplementary materials for the book "Applied Logic for Computer Scientists and Mathematicians".

The book introduces the basics of Applied Logic for Computer Scientists and Mathematicians, focusing on the application of logical deductive systems in the verification and certification of code and the mechanization of mathematical theorems. The book discusses two classical Gentzen deductive systems: natural deduction and sequent calculus, and how they are implemented in interactive proof assistants. 

---

## Solutions of selected exercises 
* [Download Solutions PDF](SOLalcs.pdf)

## Examples of Formalizations

### 1. Tutorial on *Formal Reasoning with PVS* given at Nat@Logic 2015
* [Tutorial foils](NataLog2015PVS.pdf)
* [PVS exercises](tutNataLog.tgz)

### 2. Tutorial on *Formalization of Rewriting in PVS* given at ISR 2014
* [Tutorial foils](ISR2014RewritingInPVS.pdf)
* [PVS exercises](tutPVSRewriting.tgz)

The [NASA LaRC PVS library](https://github.com/nasa/pvslib/blob/master/README.md) contains:
* [TRS](https://github.com/nasa/pvslib/blob/master/TRS/README.md): A complete library of term rewriting properties.
* [sorting](https://github.com/nasa/pvslib/blob/master/sorting/README.md): A complete library on sorting algorithms.
* [inf_primes](https://github.com/nasa/pvslib/blob/master/ints/inf_primes/README.md): A complete library on the infinitude of primes, which includes proofs from the famous "Proofs from THE BOOK".
* [nominal](https://github.com/nasa/pvslib/blob/master/nominal/README.md): A library on equality-check, matching and unification algorithms for the nominal syntax modulo associativity, commutativity and associativity-commutativity.
* [PVS0](https://github.com/nasa/pvslib/blob/master/PVS0/README.md): A library on the automation of termination for first-order functional programs. It implements termination methods such as size-change termination, calling context graphs and matrix-weighted termination, dependency pairs, and Turing termination and mechanizes their equivalence. 

### 3. Checking Sorting Algorithms over naturals 
* [Compressed library](sorting.tgz)

This library contains the classic sorting algorithms (mergesort, quicksort, insertion sort, etc.) over lists and sequences of naturals. 

The official [sorting](https://github.com/nasa/pvslib/blob/master/sorting/README.md) library contains a version of sorting over non-interpreted sorted types.

---

## Recommended PVS complete tutorials

* [Formal Proofs in PVS](https://cicm-conference.org/2025/cicm.php?event=fm-pvs&menu=general): Tutorial affiliated with the 19th International Conference on Intelligent Computational Mathematics (CICM 2025).
* [Mechanizing Mathematics](https://thaynaradelima.github.io/Tutorials/UNAL_Manizales_2023/): Tutorial for mathematicians at the Universidad Nacional de Colombia, 2023.
* [PVS for Computer Scientists 2017](https://mayalarincon.github.io/pvsclass17/index.html): Tutorial affiliated to Tableaux/ITP/FroCoS, Universidade de Brasília, 2017.
* [NASA/NIA PVS Class 2012](https://shemesh.larc.nasa.gov/PVSClass2012): Tutorial at the National Institute for Aerospace NIA/NASA LaRC, Hampton VA, 2012.

---

**Email:** [ayala at ufg dot br](mailto:ayala@ufg.br)   [flaviomoura at unb dot br](mailto:flaviomoura@unb.br), [thaynaradelima at
  ufg dot br](mailto:thaynaradelima@ufg.br) 

---
Last updated: August 4, 2026
