RHEL/CentOS 6 CIS Benchmark implementation
====

This ansible playbook implements the Center for Internet Security (CIS) Security Configuration Benchmark for Red Hat Enterprise Linux 6.x Version 1.2.0 25-06-2013 avilable at <http://benchmarks.cisecurity.org>.

Testing has been carried out on RHEL 6.x and CentOS 6.x , it should be expected to work on OEL 6.x and SL 6.x however no testing has been carried out.

What does this playbook do?
-------
The playbook will configure your system to meet the requirements of the scored CIS security benchmarks.

***Please review the modifications before applling them on a running system. Failure to do so may result in a system that you are unable to access. <font color='red'>You have been WARNED</font>***

Usage
--
git clone git://github.com/AlanC-au/CIS
cd  CIS

Perform a dry run:

    ansible-playbook -i inventory -C site.yml

To apply the changes run:

    ansible-playbook -i inventory site.yml
