About astocad-feedstock
=========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/astocad-feedstock/blob/main/LICENSE.txt)

Home: https://astocad.com/

Package license: LGPL-2.1-or-later

Summary: AstoCAD is a parametric 3D modeler made primarily to design real-life objects of any size. 

Development: https://github.com/AstoCAD/FreeCAD

Documentation: https://wiki.freecad.org/Main_Page

AstoCAD is a general purpose feature-based, parametric 3D modeler for
CAD, MCAD, CAx, CAE and PLM, aimed directly at mechanical engineering
and product design but also fits a wider range of uses in engineering,
such as architecture or other engineering specialties. It is 100% Open
Source (LGPL2+ license) and extremely modular, allowing for very
advanced extension and customization.
AstoCAD is based on FreeCAD, a free and open source project.


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-astocad-green.svg)](https://anaconda.org/AstoCAD/astocad) | [![Conda Downloads](https://img.shields.io/conda/dn/AstoCAD/astocad.svg)](https://anaconda.org/AstoCAD/astocad) | [![Conda Version](https://img.shields.io/conda/vn/AstoCAD/astocad.svg)](https://anaconda.org/AstoCAD/astocad) | [![Conda Platforms](https://img.shields.io/conda/pn/AstoCAD/astocad.svg)](https://anaconda.org/AstoCAD/astocad) |

Installing astocad
====================

Installing `astocad` from the `AstoCAD/label/dev` channel can be achieved by adding `AstoCAD/label/dev` to your channels with:

```
conda config --add channels AstoCAD/label/dev
conda config --set channel_priority strict
```

Once the `AstoCAD/label/dev` channel has been enabled, `astocad` can be installed with `conda`:

```
conda install astocad
```

or with `mamba`:

```
mamba install astocad
```

It is possible to list all of the versions of `astocad` available on your platform with `conda`:

```
conda search astocad --channel AstoCAD/label/dev
```

or with `mamba`:

```
mamba search astocad --channel AstoCAD/label/dev
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search astocad --channel AstoCAD/label/dev

# List packages depending on `astocad`:
mamba repoquery whoneeds astocad --channel AstoCAD/label/dev

# List dependencies of `astocad`:
mamba repoquery depends astocad --channel AstoCAD/label/dev
```




Updating astocad-feedstock
============================

If you would like to improve the astocad recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`AstoCAD` channel, whereupon the built conda packages will be available for
everybody to install and use from the `AstoCAD` channel.
Note that all branches in the conda-forge/astocad-feedstock are
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

* [@PaddleStroke](https://github.com/PaddleStroke/)

