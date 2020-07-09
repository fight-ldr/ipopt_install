# ipopt_install
The method of installing ipopt

Installation steps:
If you are in a no delaying Internet environment, you can use the script to install ipopt.
Apparently, the version of ipopt can change according with real occasion.
If you are not in a satisfactory Internet environment, the suggestion as follow.
First, download the package Ipopt-3.12.4.
Second, use command ./getXXX download third-party package. If can't download package, you can choose relevant package and extract in Ipopt-version/ThirdParty/XXX. However, the way of downloading relevant package has probability install failed.
Third, Execute the script after 38 lines.

Attention:
First, install Cppad before install ipopt.
Second, it is necessary to pass the test. Otherwise, the installation is failed large probability.

uninstall steps:
cd /usr/local/lib
sudo rm libipopt*
cd pkgconfig
sudo rm ipopt*
cd ../../include
sudo rm -r coin/
sudo lpconfig


