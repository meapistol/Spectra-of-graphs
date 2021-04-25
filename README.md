# Spectra-of-graphs
The **GraphRoots.nb** program computes the spectrum of a graph with a Laplacian on the edges. The graph must have edges that are rationally dependent,
and in such cases **all** solutions are found explicitly.
The graph must compact and Neumann boundary conditions are assumed at the vertices.
The instructions how to run the progam are within the notebook and includes a set of tests.

The main objective of this repository is that people should test **GraphRoots** as much as possible. Many tests have been done but it is still possible
that the program contains errors and such errors must be caught. Please report any errors or suspect behaviour under issues.

The program **Isospectral.nb** has a set of commands to generate graphs that are isospectral but not isomorphic. Included in isospectral_spectra.nb
are a large and growing set of isospectral pairs that are not isomporphic. In order for **Isospectral.nb** to work **GraphRoots.nb** must be run first. 

If you find these programs useful please cite this repository as:

```
@misc{pistol2021graphroots,
  author =       {Mats-Erik Pistol},
  title =        {Graph{R}oots, Isospectral},
  howpublished = {\url{https://github.com/meapistol/Spectra-of-graphs}},
  year =         {2021}
}
```

and/or the associated paper: *Generating isospectral but not isomorphic quantum graphs* by Mats-Erik Pistol, arXiv.

# Licensing

**GraphRoots.nb** and **Isospectral.nb** are released under MIT license.
