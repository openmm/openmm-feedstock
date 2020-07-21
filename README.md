About openmm
============

Home: http://openmm.org

Package license: LGPL-3.0-or-later

Feedstock license: BSD-3-Clause

Summary: A high performance toolkit for molecular simulation.

OpenMM is a toolkit for molecular simulation. It can be used either as a
stand-alone application for running simulations, or as a library you call
from your own code. It provides a combination of extreme flexibility
(through custom forces and integrators), openness, and high performance
(especially on recent GPUs) that make it truly unique among simulation
codes. OpenMM is MIT licensed with some LGPL portions (CUDA and OpenCL
platforms).


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/openmm/feedstock-builds/_build/latest?definitionId=3&branchName=master">
            <img src="https://dev.azure.com/openmm/feedstock-builds/_apis/build/status/openmm-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux</td>
              <td>
                <a href="https://dev.azure.com/openmm/feedstock-builds/_build/latest?definitionId=3&branchName=master">
                  <img src="https://dev.azure.com/openmm/feedstock-builds/_apis/build/status/openmm-feedstock?branchName=master&jobName=linux&configuration=linux_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_opencl_implicdloader</td>
              <td>
                <a href="https://dev.azure.com/openmm/feedstock-builds/_build/latest?definitionId=3&branchName=master">
                  <img src="https://dev.azure.com/openmm/feedstock-builds/_apis/build/status/openmm-feedstock?branchName=master&jobName=osx&configuration=osx_opencl_implicdloader" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_opencl_implicdsystem</td>
              <td>
                <a href="https://dev.azure.com/openmm/feedstock-builds/_build/latest?definitionId=3&branchName=master">
                  <img src="https://dev.azure.com/openmm/feedstock-builds/_apis/build/status/openmm-feedstock?branchName=master&jobName=osx&configuration=osx_opencl_implicdsystem" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>
      <img src="https://img.shields.io/badge/Windows-disabled-lightgrey.svg" alt="Windows disabled">
    </td>
  </tr>
  <tr>
    <td>Linux_ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-openmm-green.svg)](https://anaconda.org/openmm/openmm) | [![Conda Downloads](https://img.shields.io/conda/dn/openmm/openmm.svg)](https://anaconda.org/openmm/openmm) | [![Conda Version](https://img.shields.io/conda/vn/openmm/openmm.svg)](https://anaconda.org/openmm/openmm) | [![Conda Platforms](https://img.shields.io/conda/pn/openmm/openmm.svg)](https://anaconda.org/openmm/openmm) |

Installing openmm
=================

Installing `openmm` from the `openmm` channel can be achieved by adding `openmm` to your channels with:

```
conda config --add channels openmm
```

Once the `openmm` channel has been enabled, `openmm` can be installed with:

```
conda install openmm
```

It is possible to list all of the versions of `openmm` available on your platform with:

```
conda search openmm --channel openmm
```




Updating openmm-feedstock
=========================

If you would like to improve the openmm recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`openmm` channel, whereupon the built conda packages will be available for
everybody to install and use from the `openmm` channel.
Note that all branches in the openmm/openmm-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@jaimergp](https://github.com/jaimergp/)
* [@jchodera](https://github.com/jchodera/)
* [@peastman](https://github.com/peastman/)

