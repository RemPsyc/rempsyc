---
title: 'rempsyc: Convenience functions for psychology'
tags:
  - R
  - psychology
  - statistics
  - visualization
authors:
  - name: Rémi Thériault
    orcid: 0000-0003-4315-6788
    affiliation: 1
affiliations:
  - name: "Département de psychologie, Université du Québec à Montréal, Québec, Canada"
    index: 1
date: "2022-11-29"
bibliography: paper.bib
output:
  md_document:
    preserve_yaml: TRUE
---

# Summary

(R Core Team 2022)

The forces on stars, galaxies, and dark matter under external
gravitational fields lead to the dynamical evolution of structures in
the universe. The orbits of these bodies are therefore key to
understanding the formation, history, and future state of galaxies. The
field of “galactic dynamics,” which aims to model the gravitating
components of galaxies to study their structure and evolution, is now
well-established, commonly taught, and frequently used in astronomy.
Aside from toy problems and demonstrations, the majority of problems
require efficient numerical tools, many of which require the same base
code (e.g., for performing numerical orbit integration).

# Statement of need

`Gala` is an Astropy-affiliated Python package for galactic dynamics.
Python enables wrapping low-level languages (e.g., C) for speed without
losing flexibility or ease-of-use in the user-interface. The API for
`Gala` was designed to provide a class-based and user-friendly interface
to fast (C or Cython-optimized) implementations of common operations
such as gravitational potential and force evaluation, orbit integration,
dynamical transformations, and chaos indicators for nonlinear dynamics.
`Gala` also relies heavily on and interfaces well with the
implementations of physical units and astronomical coordinate systems in
the `Astropy` package (**astropy?**) (`astropy.units` and
`astropy.coordinates`).

`Gala` was designed to be used by both astronomical researchers and by
students in courses on gravitational dynamics or astronomy. It has
already been used in a number of scientific publications
(**Pearson:2017?**) and has also been used in graduate courses on
Galactic dynamics to, e.g., provide interactive visualizations of
textbook material (**Binney:2008?**). The combination of speed, design,
and support for Astropy functionality in `Gala` will enable exciting
scientific explorations of forthcoming data releases from the *Gaia*
mission (**gaia?**) by students and experts alike.

# Citations

Citations to entries in paper.bib should be in
[rMarkdown](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)
format.

If you want to cite a software repository URL (e.g. something on GitHub
without a preferred citation) then you can do it with the example BibTeX
entry below for (**fidgit?**).

For a quick reference, the following citation commands can be used: -
`@author:2001` -&gt; “Author et al. (2001)” - `[@author:2001]` -&gt;
“(Author et al., 2001)” - `[@author1:2001; @author2:2001]` -&gt;
“(Author1 et al., 2001; Author2 et al., 2002)”

# Figures

Figure sizes can be customized by adding an optional second parameter:
<img src="figure.png" style="width:20.0%"
alt="Caption for example figure." />

# Acknowledgements

I would like to thank Hugues Leduc, Jay Olson, Charles-Étienne Lavoie,
and Björn Büdenbender for statistical or technical advice that helped
inform some functions of this package, as well as useful feedback on
this manuscript. I would also like to acknowledge funding from the
Social Sciences and Humanities Research Council of Canada.

R Core Team. 2022. *R: A Language and Environment for Statistical
Computing*. Vienna, Austria: R Foundation for Statistical Computing.
<https://www.R-project.org/>.