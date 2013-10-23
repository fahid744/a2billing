a2billing
=========

a2billing


README

This script allows you to install A2Billing on a clean install of CentOS 5 (Either i386 or x86_64) just 'Base' is required to install it.

Among other things the script does:

- Install & Configure of LAMP (Requesting MySQL root & a2billing password)
- Install A2Billing
- Configure it for production state
- Compile from sources the Sangoma Wanpipe drivers if desired
- Disable SELinux & Firewall
- Disable unused default services in CentOS 5
- Install Asterisk from Digium repositories
- Configure cronjobs, logs, etc

HOW TO INSTALL

Be sure to have the 'screen' package installed, in order to do it you can run:

yum -y install screen

Then you have to execute the script on a screen session, to do this run:

screen

And then execute the script:

chmod +x a2billing_setup.sh
./a2billing_setup.sh

    Status
    API
    Training
    Shop
    Blog
    About

    © 2013 GitHub, Inc.
    Terms
    Privacy
    Security
    Contact

