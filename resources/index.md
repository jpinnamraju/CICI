---
title: Software
---

# <i class="fas fa-tools"></i>Software

dynaswap: This repository contains the openMRS dynaswap module and other shell scripts which are being utilized in the project.

dynaswap-omrs: This folder contains the openMRS dynaswap module. The module alows to modify the existing openMRS database and facilitate other customizations as required.

  API - Application programming interface, a directory containing information about file access management

  Omode - File directory containing information specific to the web application

  dynaswap/dynaswap-omrs/omod/src/main/webapp/ - contains information for the web app including the Django Code

  dynaswap/dynaswap-omrs/omod/src/main/webapp/requirements.txt-lists the dependencies needed for the VM 
  along with their correct versions.

  Manage.py - connects Django web app to the openMRS data

Shell-scripts: This folder includes all the shell scripts that will be used in the project. Currently includes add users script which add users and their public keys on startup to a VM.

Integration-tests: This folder contains the Gherkin BDD .feature file and related pytest files. You can execute the test scripts and get the CVSS score using pytest -s You need to install the following:

Firefox web driver using: sudo apt-get install firefox-geckodriver.

pytest and pytest-bdd using: pip install pytest pytest-bdd

selenium using: pip install selenium


Architecture

System Overview:

Dynaswap’s proposed security architecture for accessing and handling sensitive data is shown above. Many security, data processing, and data transfer features were employed to ensure data protection and support collaborative and dynamic scientific research and training. All aspects of this cybersecurity architecture will be included in a VM image, deployable on JetStream. The image contains all the information needed to build up the Dynaswap architecture. Once the project is deployed on JetStream, servers can run virtual machines that include all the Dynaswap project features.


<!-- section break -->
<!-- section break -->
<!-- section break -->