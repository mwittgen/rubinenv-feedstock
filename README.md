About rubin-env-feedstock
=========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/rubinenv-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/conda-forge/rubinenv-feedstock

Package license: BSD-3-Clause

Summary: Metapackage to install the Rubin Observatory's common software environment.

This metapackage exists to define the Rubin Observatory common software
environment, including version specifications where needed, while allowing
users flexibility when installing additional packages into the same environment.

Current build status
====================


<table><tr>
    <td>GitHub Actions</td>
    <td>
      <a href="https://github.com/conda-forge/rubinenv-feedstock/actions/workflows/conda-build.yml">
        <img src="https://github.com/conda-forge/rubinenv-feedstock/actions/workflows/conda-build.yml/badge.svg?event=push&branch=main">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=10671&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/rubinenv-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=10671&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/rubinenv-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-rubin--env-green.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-rubin-env_dev/rubin-env.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env) | [![Conda Version](https://img.shields.io/conda/vn/conda-rubin-env_dev/rubin-env.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-rubin-env_dev/rubin-env.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-rubin--env--developer-green.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-developer) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-rubin-env_dev/rubin-env-developer.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-developer) | [![Conda Version](https://img.shields.io/conda/vn/conda-rubin-env_dev/rubin-env-developer.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-developer) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-rubin-env_dev/rubin-env-developer.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-developer) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-rubin--env--extras-green.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-extras) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-rubin-env_dev/rubin-env-extras.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-extras) | [![Conda Version](https://img.shields.io/conda/vn/conda-rubin-env_dev/rubin-env-extras.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-extras) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-rubin-env_dev/rubin-env-extras.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-extras) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-rubin--env--nosysroot-green.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-nosysroot) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-rubin-env_dev/rubin-env-nosysroot.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-nosysroot) | [![Conda Version](https://img.shields.io/conda/vn/conda-rubin-env_dev/rubin-env-nosysroot.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-nosysroot) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-rubin-env_dev/rubin-env-nosysroot.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-nosysroot) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-rubin--env--rsp-green.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-rsp) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-rubin-env_dev/rubin-env-rsp.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-rsp) | [![Conda Version](https://img.shields.io/conda/vn/conda-rubin-env_dev/rubin-env-rsp.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-rsp) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-rubin-env_dev/rubin-env-rsp.svg)](https://anaconda.org/conda-rubin-env_dev/rubin-env-rsp) |

Installing rubin-env
====================

Installing `rubin-env` from the `conda-rubin-env_dev/label/` channel can be achieved by adding `conda-rubin-env_dev/label/` to your channels with:

```
conda config --add channels conda-rubin-env_dev/label/
conda config --set channel_priority strict
```

Once the `conda-rubin-env_dev/label/` channel has been enabled, `rubin-env, rubin-env-developer, rubin-env-extras, rubin-env-nosysroot, rubin-env-rsp` can be installed with `conda`:

```
conda install rubin-env rubin-env-developer rubin-env-extras rubin-env-nosysroot rubin-env-rsp
```

or with `mamba`:

```
mamba install rubin-env rubin-env-developer rubin-env-extras rubin-env-nosysroot rubin-env-rsp
```

It is possible to list all of the versions of `rubin-env` available on your platform with `conda`:

```
conda search rubin-env --channel conda-rubin-env_dev/label/
```

or with `mamba`:

```
mamba search rubin-env --channel conda-rubin-env_dev/label/
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search rubin-env --channel conda-rubin-env_dev/label/

# List packages depending on `rubin-env`:
mamba repoquery whoneeds rubin-env --channel conda-rubin-env_dev/label/

# List dependencies of `rubin-env`:
mamba repoquery depends rubin-env --channel conda-rubin-env_dev/label/
```




Updating rubin-env-feedstock
============================

If you would like to improve the rubin-env recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-rubin-env_dev` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-rubin-env_dev` channel.
Note that all branches in the conda-forge/rubin-env-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@athornton](https://github.com/athornton/)
* [@beckermr](https://github.com/beckermr/)
* [@erykoff](https://github.com/erykoff/)
* [@ktlim](https://github.com/ktlim/)
* [@mwittgen](https://github.com/mwittgen/)
* [@roceb](https://github.com/roceb/)
* [@timj](https://github.com/timj/)

