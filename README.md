About gmsh-packages-feedstock
=============================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/gmsh-feedstock/blob/main/LICENSE.txt)


About gmsh-packages
-------------------

Home: https://gmsh.info/

Package license: GPL-2.0-or-later

Summary: A three-dimensional finite element mesh generator with built-in pre- and post-processing facilities

Development: https://gitlab.onelab.info/gmsh/gmsh/

Documentation: https://gmsh.info/doc/texinfo/gmsh.html

Gmsh is a free 3D finite element grid generator with a build-in CAD
engine and post-processor. Its design goal is to provide a fast, light
and user-friendly meshing tool with parametric input and advanced
visualization capabilities. Gmsh is built around four modules:
geometry, mesh, solver and post-processing. The specification of any
input to these modules is done either interactively using the graphical
user interface or in ASCII text files using Gmsh's own scripting
language.


About gmsh
----------

Home: https://gmsh.info/

Package license: GPL-2.0-or-later

Summary: A three-dimensional finite element mesh generator with built-in pre- and post-processing facilities

Development: https://gitlab.onelab.info/gmsh/gmsh/

Documentation: https://gmsh.info/doc/texinfo/gmsh.html

Gmsh is a free 3D finite element grid generator with a build-in CAD
engine and post-processor. Its design goal is to provide a fast, light
and user-friendly meshing tool with parametric input and advanced
visualization capabilities. Gmsh is built around four modules:
geometry, mesh, solver and post-processing. The specification of any
input to these modules is done either interactively using the graphical
user interface or in ASCII text files using Gmsh's own scripting
language.


About python-gmsh
-----------------

Home: https://gmsh.info/

Package license: GPL-2.0-or-later

Summary: A three-dimensional finite element mesh generator with built-in pre- and post-processing facilities

Development: https://gitlab.onelab.info/gmsh/gmsh/

Documentation: https://gmsh.info/doc/texinfo/gmsh.html

Gmsh is a free 3D finite element grid generator with a build-in CAD
engine and post-processor. Its design goal is to provide a fast, light
and user-friendly meshing tool with parametric input and advanced
visualization capabilities. Gmsh is built around four modules:
geometry, mesh, solver and post-processing. The specification of any
input to these modules is done either interactively using the graphical
user interface or in ASCII text files using Gmsh's own scripting
language.


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-gmsh-green.svg)](https://anaconda.org/freecad/gmsh) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/gmsh.svg)](https://anaconda.org/freecad/gmsh) | [![Conda Version](https://img.shields.io/conda/vn/freecad/gmsh.svg)](https://anaconda.org/freecad/gmsh) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/gmsh.svg)](https://anaconda.org/freecad/gmsh) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-python--gmsh-green.svg)](https://anaconda.org/freecad/python-gmsh) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/python-gmsh.svg)](https://anaconda.org/freecad/python-gmsh) | [![Conda Version](https://img.shields.io/conda/vn/freecad/python-gmsh.svg)](https://anaconda.org/freecad/python-gmsh) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/python-gmsh.svg)](https://anaconda.org/freecad/python-gmsh) |

Installing gmsh-packages
========================

Installing `gmsh-packages` from the `freecad` channel can be achieved by adding `freecad` to your channels with:

```
conda config --add channels freecad
conda config --set channel_priority strict
```

Once the `freecad` channel has been enabled, `gmsh, python-gmsh` can be installed with `conda`:

```
conda install gmsh python-gmsh
```

or with `mamba`:

```
mamba install gmsh python-gmsh
```

It is possible to list all of the versions of `gmsh` available on your platform with `conda`:

```
conda search gmsh --channel freecad
```

or with `mamba`:

```
mamba search gmsh --channel freecad
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search gmsh --channel freecad

# List packages depending on `gmsh`:
mamba repoquery whoneeds gmsh --channel freecad

# List dependencies of `gmsh`:
mamba repoquery depends gmsh --channel freecad
```




Updating gmsh-packages-feedstock
================================

If you would like to improve the gmsh-packages recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`freecad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `freecad` channel.
Note that all branches in the conda-forge/gmsh-packages-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@adrianinsaval](https://github.com/adrianinsaval/)
* [@guyer](https://github.com/guyer/)
* [@isuruf](https://github.com/isuruf/)
* [@looooo](https://github.com/looooo/)
* [@matthiasdiener](https://github.com/matthiasdiener/)
* [@xywei](https://github.com/xywei/)

