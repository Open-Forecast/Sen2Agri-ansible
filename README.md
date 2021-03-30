
# Disclaimer

The given ansible roles are written to fit the specific infrastructure environment.
Install files and data output will be written to nfs mounted storage. Additionally some
user IDs and group IDs are choosen to fit the environement. In order
to reuse the ansible roles you have to adapt these working environment changes.

# Sen2Agri-ansible
Ansible roles to simplify the installation process of the Sen2Agri service.
The scripts are tailored for using Centos7 as reqired for Sen2Agri.

In order run the script you need to download

* Sen2Agri-package-{{ sen2agri_version }}.zip
* srtm.zip
* Maja_3.2.2_TM.zip

## Roles

* nfs-mount: specific for our project to use NFS file system due to the large amount of data
* maja: requiered for the Sen2Agri service
* sen2agri: the service itself
* git: specific for our project to get additional code for postprocessing
* python3: specific for our project to postprocessing on the data

## Open Issues

1) Change from local DB to external DB for better maintenance
2) Connect to HPC batch system instead of building own cluster
