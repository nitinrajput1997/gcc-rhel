# gcc-rhel

To install GCC (GNU Compiler Collection) on RHEL 8.7, you can follow these steps:

Open a terminal on your RHEL 8.7 system.

Update your system's package repository and software packages by running the following command:
```
sudo dnf update
```
Install GCC and related packages using the following command:
```
sudo dnf install gcc
```

This command installs the base GCC package along with its dependencies.

Verify the installation by checking the GCC version:
```
gcc --version
```
This should display the installed GCC version if the installation was successful.
