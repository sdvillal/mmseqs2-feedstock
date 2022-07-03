About mmseqs2
=============

Home: https://github.com/soedinglab/mmseqs2

Package license: GPLv3

Feedstock license: [BSD-3-Clause](https://github.com/sdvillal/mmseqs2-feedstock/blob/master/LICENSE.txt)

Summary: MMseqs2: ultra fast and sensitive sequence search and clustering suite

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/mmseqs2-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/mmseqs2-feedstock?branchName=master&jobName=linux&configuration=linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/mmseqs2-feedstock?branchName=master&jobName=osx&configuration=osx_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-mmseqs2-green.svg)](https://anaconda.org/sdvillal/mmseqs2) | [![Conda Downloads](https://img.shields.io/conda/dn/sdvillal/mmseqs2.svg)](https://anaconda.org/sdvillal/mmseqs2) | [![Conda Version](https://img.shields.io/conda/vn/sdvillal/mmseqs2.svg)](https://anaconda.org/sdvillal/mmseqs2) | [![Conda Platforms](https://img.shields.io/conda/pn/sdvillal/mmseqs2.svg)](https://anaconda.org/sdvillal/mmseqs2) |

Installing mmseqs2
==================

Installing `mmseqs2` from the `sdvillal` channel can be achieved by adding `sdvillal` to your channels with:

```
conda config --add channels sdvillal
conda config --set channel_priority strict
```

Once the `sdvillal` channel has been enabled, `mmseqs2` can be installed with `conda`:

```
conda install mmseqs2
```

or with `mamba`:

```
mamba install mmseqs2
```

It is possible to list all of the versions of `mmseqs2` available on your platform with `conda`:

```
conda search mmseqs2 --channel sdvillal
```

or with `mamba`:

```
mamba search mmseqs2 --channel sdvillal
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search mmseqs2 --channel sdvillal

# List packages depending on `mmseqs2`:
mamba repoquery whoneeds mmseqs2 --channel sdvillal

# List dependencies of `mmseqs2`:
mamba repoquery depends mmseqs2 --channel sdvillal
```




Updating mmseqs2-feedstock
==========================

If you would like to improve the mmseqs2 recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`sdvillal` channel, whereupon the built conda packages will be available for
everybody to install and use from the `sdvillal` channel.
Note that all branches in the sdvillal/mmseqs2-feedstock are
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


