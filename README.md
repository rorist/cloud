CLOUD
=====

cloud - an easy to use tool for spawning disposable VM on an Openstack cloud

Installation
------------

* Install dependencies

    sudo pip install ipaddr
    sudo apt-get install python-novaclient python-neutronclient

* Download openrc file to your computer
** Go to Access & Security > API Access
** Click Download OpenStack RC File
** Put the openrc file in ~/openrc

Usage
-----

* Source openrc file, from your .bashrc for instance

 echo '. ~/openrc' >> ~/.bashrc

* Run the script without argument to launch a VM !
* ./cloud -h # for help

