## The method of  installing ipopt

### Installation steps:

If you are in a no delaying Internet environment, you can use the script to install ipopt. However, if you are not in a satisfactory Internet environment, the suggestion as follow:

> 1.download the package Ipopt-3.12.4.

> 2.use command ./getXXX download third-party package. If can't download package, you can choose relevant package and extract in Ipopt-version/ThirdParty/XXX. However, the way of downloading relevant package has probability install failed.

> 3.Execute the script after 38 lines.

**Attention:**

> 1.install Cppad before install ipopt.

> 2.it is necessary to pass the test. Otherwise, the installation is failed large probability.

> 3.Apparently, the version of ipopt can change according with real occasion.

### Uninstall steps:

> cd /usr/local/lib
>
> sudo rm libipopt*
>
> cd pkgconfig
>
> sudo rm ipopt*
>
> cd ../../include
>
> sudo rm -r coin/
>
> sudo lpconfig

