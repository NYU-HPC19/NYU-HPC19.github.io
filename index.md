---
layout: default
---

Here’s a [flyer](./files/flyer.pdf) for the class.

**Instructors:**
- [Georg Stadler](https://cims.nyu.edu/~stadler), Warner Weaver Hall Office #1111
- [Dhairya Malhotra](https://cims.nyu.edu/~malhotra), Warner Weaver Hall Office #1008

**Lectures:** Mondays 5:10-7:00pm, **class starts on January 28**

**Location:** Warren Weaver Hall #1302

**Organization:** We use Slack for organization, communication and cooperation. Please email if you want to be added.

## Lecture Material

| Lec. no. |    Date | Topics |           Slides/ Material |                                          Code | Homework
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 1         | Jan 28  | *Theory:* HPC Tour, Top 500 lists, applications, examples; *Tools:* ssh, module   | [slides](./files/lec1.pdf) [computing@CIMS](./files/hpc19_cims.pdf) | [code](https://github.com/NYU-HPC19/lecture1) | hw #1 [[PDF](./files/hpc19_assignment1.pdf), [TEX](./files/hpc19_assignment1.tex)],  due Feb 11         |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 2         | Feb 4   | *Theory:* Memory hierarchies, computational intensity, programming models, scalability, Amdahl's law; *Tools:* valgrind, cachgrind   | [slides](./files/lec2.pdf) | [code](https://github.com/NYU-HPC19/lecture2), [video](https://www.youtube.com/watch?v=G32QMsgr-jM) |          |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 3         | Feb 11   | *Theory:* Bandwidth, latency and valgrind examples, single core performance (pipelining, vectorization)  | [slides](./files/lec3.pdf) | [code](https://github.com/NYU-HPC19/lecture3)  |hw #2 [[PDF](./files/hpc19_assignment2.pdf), [TEX](./files/hpc19_assignment2.tex)],  due March 11          |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| -         | Feb 18   | *No class due to NYU holiday*  |  |  |          |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 4         | Feb 25  | *Theory:* Amdahl's law, parallel scalability, Distributed memory model, OpenMP, shared memory performance and speedup; *Tools:* local git | [slides](./files/lec4.pdf) | [code](https://github.com/NYU-HPC19/lecture4) | |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| -         | Mar 4   | *No class due to NYU closure (fake snow storm day)*  |  |  |          |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 5         | Mar 8   | **Makeup class, Rm 101, 4:10-6:00PM; Video of the class is on NYU Classes (login required) HPC19-Panopto**: *Theory:* More OpenMP, atomic operations; *Tools:* remote git, git merge,  Make  | [slides](./files/lec5.pdf) | [code](https://github.com/NYU-HPC19/lecture5)  |     |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 6         | Mar 11   | *Theory:*  More OpenMP, NUMA, review of vectorization + lec3-demo, *Libraries:* BLAS, LAPACK, FFTW    | [slides](./files/lec6.pdf) | [code](https://github.com/NYU-HPC19/lecture6) |hw #3 [[PDF](./files/hpc19_assignment3.pdf), [TEX](./files/hpc19_assignment3.tex)],  due April 1          |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 7         | Mar 25   | *Theory:* computing on GPGPUs, GPU architecture, thread hierarchy, memory spaces, global memory management, launching kernels; *Tools:* nvcc compiler | [slides](./files/lec7.pdf) | [code](https://github.com/NYU-HPC19/lecture7) |          |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 8         | Apr 1   | *Theory:* computing on GPGPUs, shared memory, thread synchronization; *Tools:* job schedulers (SLURM), [final project examples](./files/hpc19_projectexamples.pdf)  | [slides](./files/lec8.pdf) | [code](https://github.com/NYU-HPC19/lecture8) | hw #4 [[PDF](./files/hpc19_assignment4.pdf), [TEX](./files/hpc19_assignment4.tex)],  due April 15         |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 9         | Apr 8   |  *Theory:* Final project, GPU performance, occupancy, streams; *Examples:* bitonic sort, scan, image blurring, cuBLAS   | [slides](./files/lec9.pdf) | [code](https://github.com/NYU-HPC19/lecture9) |          |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 10         | Apr 15   | *Theory:* Sources of parallelism, distributed memory computing, partitioning I, MPI blocking and non-blocking Send and Recv       | [slides](./files/lec10.pdf)  | [code](https://github.com/NYU-HPC19/lecture10) |  hw #5 [[PDF](./files/hpc19_assignment5.pdf), [TEX](./files/hpc19_assignment5.tex)],  due April 29        |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 11         | Apr 22   | *Theory:* collective MPI calls (reduce, gather, etc), more distributed memory examples;  *Tools:* more SLURM       | [slides](./files/lec11.pdf)   | [code](https://github.com/NYU-HPC19/lecture11)  |          |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 12         | Apr 29   | *Theory:* MPI algorithms: parallel Jacobi (blocking and non-blocking), hypercube algorithms; problem partitioning and distribution    | [slides](./files/lec12.pdf)   | [code](https://github.com/NYU-HPC19/lecture12)  | hw #6 [[PDF](./files/hpc19_assignment6.pdf), [TEX](./files/hpc19_assignment6.tex)],  due May 13 |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 13         | May 6   | *Theory:* Space filling curves and Morten IDs, multigrid; *Tools:* paraview   |  [slides](./files/lec13.pdf)   | [code](https://github.com/NYU-HPC19/lecture13)  |          |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|
| 14         | May 13   |        |  |  |          |
|:---------:|:-------:|:------:|:--------------------------:|:---------------------------------------------:|:--------:|

## Other
- [Examples of HPC applications](pages/hpcapplications.html)
