# fastTopics

[![Travis Build Status](https://travis-ci.org/stephenslab/fastTopics.svg?branch=master)](https://travis-ci.org/stephenslab/fastTopics)
[![Appveyor Build status](https://ci.appveyor.com/api/projects/status/224272mhk5fadgmt?svg=true)](https://ci.appveyor.com/project/pcarbo/fastTopics)
[![codecov](https://codecov.io/gh/stephenslab/fastTopics/branch/master/graph/badge.svg)](https://codecov.io/gh/stephenslab/fastTopics)

R package implementing fast optimization algorithms for fitting topic
models and non-negative matrix factorizations to count data.

If you find a bug, or you have a question or feedback on this software,
please post an [issue][issues].

## License

Copyright (c) 2019-2020, Peter Carbonetto and Matthew Stephens.

All source code and software in this repository are made available
under the terms of the [MIT license][mit-license].

## Quick Start

The fastTopics package is currently undergoing major re-development in
the master branch, so it is recommended to install the version from
the v0.1 branch. To do this, clone the repository from GitHub, switch
to the v0.1 branch by running in the shell

```bash
git checkout v0.1
```

then use [devtools][devtools]:

```R
install.packages("devtools")
devtools::install_local("fastTopics")
```

This command should automatically install all required packages if
they are not installed already.

Alternatively, to install the latest (in-development) version of the
fastTopics package, download or clone the repository from GitHub, then
run:

```R
devtools::install_local("fastTopics")
```

Compiling this package from source will require a C++ compiler setup
that is appropriate for the version of R installed on your
computer. For details, refer to the [CRAN documentation][cran].

## Credits

The fastTopics R package was developed by [Peter Carbonetto][peter] at
the [University of Chicago][uchicago], with guidance from
[Matthew Stephens][matthew].

[mit-license]: https://opensource.org/licenses/mit-license.html
[issues]: https://github.com/stephenslab/fastTopics/issues
[peter]: https://pcarbo.github.io
[matthew]: http://stephenslab.uchicago.edu
[uchicago]: https://www.uchicago.edu
[devtools]: https://github.com/r-lib/devtools
[cran]: https://cran.r-project.org

