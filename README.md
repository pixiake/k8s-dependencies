## Describe

This repository provides the basic software packages(`.deb` `.rpm`) that kubernetes depends on.


## Usage
After decompression, you can use the following command to install.

⚠ If you need to update dependencies for the running nodes in the cluster, please drain the nodes before executing.

### ubuntu
```shell
dpkg -iR --force-all  ./
```

### centos 
```shell
rpm -Uvh --force --nodeps ./*rpm
```