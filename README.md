#AptOutputParser

This script accepts a file (packages.txt) that contains the parsed output of dpkg -l (with only the package names in it). It then runs "apt-cache rdepends" on the package names and outputs only those packages (and their reverse dependencies) that do not contain the package "dxxx-xxxx-os-2"
