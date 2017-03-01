
# What is EPEL

EPEL (Extra Packages for Enterprise Linux) is open source and free community based repository project from Fedora team which provides 100% high quality add-on software packages for Linux distribution including RHEL (Red Hat Enterprise Linux), CentOS, and Scientific Linux. Epel project is not a part of RHEL/Cent OS but it is designed for major Linux distributions by providing lots of open source packages like networking, sys admin, programming, monitoring and so on. Most of the epel packages are maintained by Fedora repo.


# How To Enable EPEL Repository in RHEL/CentOS

## RHEL/centOS 7 64 bit

```shell

wget http://dl.fedoraproject.org/pub/epel/7/x86_64/e/epel-release-7-9.noarch.rpm
rpm -ivh epel-release-7-9.noarch.rpm

```

## RHEL/CentOS 6 32-64 Bit

```shell

## RHEL/CentOS 6 32-Bit ##
wget http://download.fedoraproject.org/pub/epel/6/i386/epel-release-6-8.noarch.rpm
rpm -ivh epel-release-6-8.noarch.rpm

## RHEL/CentOS 6 64-Bit ##
wget http://download.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm
rpm -ivh epel-release-6-8.noarch.rpm

```

---

# Resources

[How to Enable EPEL Repository for RHEL/CentOS ](http://www.tecmint.com/how-to-enable-epel-repository-for-rhel-centos-6-5/)
