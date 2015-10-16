CLOUD
=====

cloud - an easy to use tool for spawning disposable VM on an Openstack cloud

Installation
------------

* Install dependencies

```
sudo pip install -r requirements.txt
```

novaclient in pip doesn't work atm, better use the repo one,

```
sudo pip uninstall python-novaclient
sudo apt-get install python-novaclient
```

* Download openrc file to your computer
    * Go to Access & Security > API Access
    * Click Download OpenStack RC File
    * Put the openrc file in ```~/openrc```

Usage
-----

* Source openrc file, from your ```~/.bashrc``` for instance

```
echo '. ~/openrc' >> ~/.bashrc
```

* Run the script without argument to launch a VM !
* ```./cloud -h``` # for help

