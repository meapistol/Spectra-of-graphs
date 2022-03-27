# Spectra-of-graphs
The **GraphRoots.nb** program computes the spectrum of a graph with a Laplacian on the edges. The graph must have edges that are rationally dependent,
and in such cases **all** solutions are found explicitly.
The graph must be compact and Neumann boundary conditions are assumed at the vertices.
The instructions how to run the progam are within the notebook and includes a set of tests.

The main objective of this repository is that people should test **GraphRoots** as much as possible. Many tests have been done but it is still possible
that the program contains errors and such errors must be caught. Please report any errors or suspect behaviour under issues.

The program **Isospectral.nb** has a set of commands to generate graphs that are isospectral but not isomorphic. Included in **Isospectral.nb**
is a large and growing set of isospectral pairs that are not isomporphic. In order for **Isospectral.nb** to work **GraphRoots.nb** must be run first.

If you find these programs useful please cite this repository as:

```
@misc{pistol2021graphroots,
  author =       {Mats-Erik Pistol},
  title =        {Graph{R}oots, Isospectral},
  howpublished = {\url{https://github.com/meapistol/Spectra-of-graphs}},
  year =         {2021}
}
```

and/or the associated paper: *Generating isospectral but not isomorphic quantum graphs* by Mats-Erik Pistol: https://arxiv.org/abs/2104.12885.

```
@misc{pistol2021generating,
      title={Generating isospectral but not isomorphic quantum graphs},
      author={Mats-Erik Pistol},
      year={2021},
      eprint={2104.12885},
      archivePrefix={arXiv},
      primaryClass={math.SP}
}
```
# Issues
No issues at the moment.

# Updates
Version 5 of the paper is now uploaded and now includes about ten generating sets. Isospectral.nb has been updated to correspond to vs5 the paper. GraphRoots.nb is unchanged but supports vs5 of the paper as well.
# Data
The file Trees.pdf contains all isospectral pairs of trees having at most 13 vertices. There are 51 isospectral pairs. There is one isospectral pair with nine vertices, two isospectral pairs with 10 vertices, five isospectral pairs with 11 vertices and six isospectral pairs with 12 vertices and 37 isospectral trees with 13 vertices.

# Typos in paper
None known.
# Licensing

**GraphRoots.nb** and **Isospectral.nb** are released under MIT license.
