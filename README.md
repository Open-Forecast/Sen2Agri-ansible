# Sen2Agri-ansible
Ansible roles to simplify the installation process of the Sen2Agri service.
The scripts are tailored for using Centos7 as reqired for Sen2Agri.

In order run the script you need to dowload

* Sen2Agri-package-{{ sen2agri_version }}.zip
* srtm.zip
* Maja_3.2.2_TM.zip

The script can be used with an external data base.

## Roles

* nfs-mount: specific for our project to use NFS file system due to the large amount of data
* maja: requiered for the Sen2Agri service
* sen2agri: the service itself
* git: specific for our project to get additional code for postprocessing
* python3: specific for our project to postprocessing on the data

## HowTo

1) enter data base url and password
2) choose sen2agri version
3)
