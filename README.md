[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# Average case sub-quadratic exact and heuristic procedures for the traveling salesman 2-OPT neighborhood

This archive is distributed in association with the [INFORMS Journal on
Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

The software and data in this repository are a snapshot of the software and data
that were used in the research reported on in the paper
[Average case sub-quadratic exact and heuristic procedures for the traveling salesman 2-OPT neighborhood](https://doi.org/10.1287/ijoc.2023.0169)
by G. Lancia and P. Vidoni.

## Cite

To cite the contents of this repository, please cite both the paper and this
repo, using their respective DOIs.

https://doi.org/10.1287/ijoc.2023.0169

https://doi.org/10.1287/ijoc.2023.0169.cd

Below is the BibTex for citing this snapshot of the repository.

```
@misc{Lancia2024,
  author =        {G. Lancia and P. Vidoni},
  publisher =     {INFORMS Journal on Computing},
  title =         {{Average case sub-quadratic exact and heuristic procedures for the traveling salesman 2-OPT neighborhood}},
  year =          {2024},
  doi =           {10.1287/ijoc.2023.0169.cd},
  url =           {https://github.com/INFORMSJoC/2023.0169},
  note =          {Available for download at https://github.com/INFORMSJoC/2023.0169},
}
```

## Description

The repository contains all files necessary to replicate computational
experiments as those reported in the paper "Average case sub-quadratic  exact
and heuristic procedures for the traveling salesman 2-OPT neighborhood", by
Giuseppe Lancia and Paolo Vidoni, INFORMS Journal on Computing, 2024.

## Building

The programs are in c. They can be compiled by running
```
make KoptLS
```
This creates the suite KoptLS, i.e., a program for TSP local search via k-OPT
moves for (k=2,3,4). Only k=2 is relevant to the paper.

Please, find further instructions on how to use the suite KoptLS on the file [docs/KoptLSmanual.pdf](docs/KoptLSmanual.pdf).

## Results

Please, find all instructions on how to replicate the paper's computational
experiments on the file [docs/KoptLS_JOC.pdf](docs/KoptLS_JOC.pdf).

This is a detailed step-by-step guide on how to use KoptLS in order to simulate
the experiment relative to all tables and figures reported in the paper.

Tables and figures can be found on [docs/tablesAndFigures.pdf](docs/tablesAndFigures.pdf).
