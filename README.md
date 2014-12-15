DigOps Cluster
==============

This files present ansible-related stuff with AWS EC2 instance running servers.

# Prerequisites for getting to work

You need the following python modules on your machine (the machine you run ansible 
on) 
- python-yaml
- python-jinja2

On Debian/Ubuntu run:
``sudo apt-get install python-yaml python-jinja2 python-paramiko python-crypto``

We're also assuming you have a keypair in your ~/.ssh directory.
# Cloning the repo

    git clone https://github.com/digsearch/digops-cluster
    cd digops-cluster

## Contributors and maintainers

* Sardor Muminov (@muminoff)
