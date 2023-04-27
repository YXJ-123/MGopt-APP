# MGopt-APP

Contact: Xiaojian Yang (1724925160@qq.com)

Multigrid algorithms accelerate the solution of large-scale sparse linear systems by generating a sequence of grids (from fine level to coarse level) by successive refinement.
The Symmetric Gaussian-Seidel (SYMGS) method at each level is often the performance bottleneck of MG.
MGopt uses a modified computational formulation to reduce computational operations and memory accesses in SYMGS.
In addition, it proposes a new asynchronous parallelization scheme to reduce the synchronization overhead in SYMGS parallelization.
These optimization techniques have been combined with the HPCG benchmark and have significantly improved its performance.


**This work is continuing to be optimized.
Here, this project shows only the *.exe* file (based on ARMv8 or x86) for your testing.
If you have any questions about this project or are interested in the source code, please contact me.**


# Paper information

**Xiaojian Yang, Shengguo Li, Fan Yuan, Dezun Dong, Chun Huang, Zheng Wang:** [Optimizing Multi-grid Computation and Parallelization on
Multi-cores](https://doi.org/10.1145/3577193.3593726). **ICS 2023**


# Software dependences

[GNU Compiler (GCC) 11.2.0](http://ftp.gnu.org/gnu/gcc/gcc-11.2.0/gcc-11.2.0.tar.gz)

[MPICH 3.4.3](https://www.mpich.org/static/downloads/3.4.3/)

It is advisable to complete the configuration of these two dependency libraries before *Getting Started*.

# Getting Started



# Note
