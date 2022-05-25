About r-clustersim
==================

Home: http://keii.ue.wroc.pl/clusterSim

Package license: GPL (>= 2)

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-clustersim-feedstock/blob/main/LICENSE.txt)

Summary: Distance measures (GDM1, GDM2,	Sokal-Michener, Bray-Curtis, for symbolic interval-valued data), cluster quality indices (Calinski-Harabasz, Baker-Hubert, Hubert-Levine, Silhouette, Krzanowski-Lai, Hartigan, Gap,	Davies-Bouldin),	data normalization formulas (metric data, interval-valued symbolic data), data generation (typical and non-typical data), HINoV method,	replication analysis, linear ordering methods, spectral clustering, agreement indices between two partitions, plot functions (for categorical and symbolic interval-valued data).  (MILLIGAN, G.W., COOPER, M.C. (1985) <doi:10.1007/BF02294245>,  HUBERT, L., ARABIE, P. (1985) <doi:10.1007%2FBF01908075>,  RAND, W.M. (1971) <doi:10.1080/01621459.1971.10482356>,  JAJUGA, K., WALESIAK, M. (2000) <doi:10.1007/978-3-642-57280-7_11>,  MILLIGAN, G.W., COOPER, M.C. (1988) <doi:10.1007/BF01897163>,  JAJUGA, K., WALESIAK, M., BAK, A. (2003) <doi:10.1007/978-3-642-55721-7_12>,  DAVIES, D.L., BOULDIN, D.W. (1979) <doi:10.1109/TPAMI.1979.4766909>,  CALINSKI, T., HARABASZ, J. (1974) <doi:10.1080/03610927408827101>, HUBERT, L. (1974) <doi:10.1080/01621459.1974.10480191>,  TIBSHIRANI, R., WALTHER, G., HASTIE, T. (2001) <doi:10.1111/1467-9868.00293>,  BRECKENRIDGE, J.N. (2000) <doi:10.1207/S15327906MBR3502_5>,  WALESIAK, M., DUDEK, A. (2008) <doi:10.1007/978-3-540-78246-9_11>).

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6519&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-clustersim-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_r_base4.0</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6519&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-clustersim-feedstock?branchName=main&jobName=linux&configuration=linux_64_r_base4.0" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_r_base4.1</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6519&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-clustersim-feedstock?branchName=main&jobName=linux&configuration=linux_64_r_base4.1" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_r_base4.0</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6519&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-clustersim-feedstock?branchName=main&jobName=win&configuration=win_64_r_base4.0" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_r_base4.1</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6519&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-clustersim-feedstock?branchName=main&jobName=win&configuration=win_64_r_base4.1" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--clustersim-green.svg)](https://anaconda.org/conda-forge/r-clustersim) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-clustersim.svg)](https://anaconda.org/conda-forge/r-clustersim) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-clustersim.svg)](https://anaconda.org/conda-forge/r-clustersim) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-clustersim.svg)](https://anaconda.org/conda-forge/r-clustersim) |

Installing r-clustersim
=======================

Installing `r-clustersim` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `r-clustersim` can be installed with `conda`:

```
conda install r-clustersim
```

or with `mamba`:

```
mamba install r-clustersim
```

It is possible to list all of the versions of `r-clustersim` available on your platform with `conda`:

```
conda search r-clustersim --channel conda-forge
```

or with `mamba`:

```
mamba search r-clustersim --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search r-clustersim --channel conda-forge

# List packages depending on `r-clustersim`:
mamba repoquery whoneeds r-clustersim --channel conda-forge

# List dependencies of `r-clustersim`:
mamba repoquery depends r-clustersim --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [Anaconda-Cloud](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-clustersim-feedstock
===============================

If you would like to improve the r-clustersim recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-clustersim-feedstock are
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

* [@conda-forge/r](https://github.com/conda-forge/r/)
* [@npavlovikj](https://github.com/npavlovikj/)

