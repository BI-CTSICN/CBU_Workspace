Installing monocle


error while installing leidenbase

Update-- got around this by installing a fresh version of gfortran from here - https://github.com/fxcoudert/gfortran-for-macOS/releases. I just installed their dmg file because I have MAC.

Also in my case I had to upgrade to R 3.6 from R 3.5 because other packages like 'hexbin’, ‘deldir' were not available for R 3.5.

Again after installing leidenbase, I got another error about Matrix.utils package while trying to install Monocle3. Someone else had posted this error before and I followed that by
devtools::install_url('https://cran.r-project.org/src/contrib/Archive/Matrix.utils/Matrix.utils_0.9.7.tar.gz')

Hope this is helpful for other users who get stuck with this particular error.
