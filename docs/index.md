# Open GOvernment Tech Ops Aide-de-Memoire

This is a guide for the OG Portal Team on hwo to conduct basic technical operations tasks. Whether you are new to the team, or something is broken and no one else is around, this guide is meant to walk you step by step through various techincal tasks that might need to get done.

## Table of Contents

* Build PD Templates
* Export Results from Drupal Web Form
* Restart services
* Deploy Code from Github to Servers
* Make CKAN User SYSADMIN - PROD
* Make CKAN USer SYSADMIN - STAGING
* Using the Make file to Manually Update Proactive Disclosures / Recombinant Types on the Portal
* Using the Make file to Export a Proactive Disclosures / Recombinant Type to a Static File
* Requesting a Whitelist for Registry
* Using the CKAN API to Modify an Existing Record on the Portal
* Using the CKAN API to get a List of Registry Users' Email Addresses

## Example Screen Shot
![screenshot](img/ckanapi.png)

you can use the command `ckanapi -h` to ge the instructions on how to use CKAN api CLI tool


## How to use the CKAN API to Modify an Existing Record on the Portal

1. Make sure you have Python installed on your workstation.
![pythonscreenshot](img/python.jpg)
    * If you don't have Python installed, you can download it from [python.org](https://python.org/downloads) 
2. Make sure you have pip installed
![pipscreenshot](img/pip.jpg)
 If you don't have pip:
    * download [get-pip.py](https://bootstrap.pypa.io/get-pip.py) to your computer. 
    * open a terminal and `cd` to the folder containing get-pip.py
    * run the command `python get-pip.py`