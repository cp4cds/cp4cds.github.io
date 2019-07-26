---
layout: page
title: Technology
permalink: /tech/
---
We provide here information about the technology (software) we use and access points to our services.

## Access Points to our Services

Here is collection of the CP4CDS web services (data and compute):

* [Data Availability App](https://cp-availability.ceda.ac.uk/)
  * The Data Availability Application is provided to allow questions to be asked about the availability of different variables and models in CMIP5.
* [Geographically load-balanced ESGF search end-point for C3S Climate Model Simulations](https://index.mips.copernicus-climate.eu/esg-search/search)
  * This search interface is an **XML document**. It is a *computational interface* that can be interacted with by various client tools. More details on interacting with the *ESGF Search* interface can be found at:
  * [ESGF Search RESTful API documentation](https://github.com/ESGF/esgf.github.io/wiki/ESGF_Search_REST_API)
* [Geographically load-balanced Compute Service using the Web Processing Service (WPS) standard interface](http://compute.mips.copernicus-climate.eu/wps?service=WPS&version=1.0.0&request=GetCapabilities)
  * This interface is an **XML document**. It is a *computational interface* that can be interacted with by various WPS client tools. An example client tool is the Phoenix interface, hosted by DKRZ. This provides a graphical user interface for interacting with a WPS service:
  * [Try Phoenix online demo](https://bovec.dkrz.de/processes/list?wps=ccds)


## Software

Please check the list of our software tools we use in our data and compute infrastructure.

Data Service Software:

* [ESGF Installer](https://github.com/ESGF/esgf-installer/wiki)
  * This is the Installation Guide for building, maintaining and running an ESGF Data Nodes.
  * This was used in the project for deploying the CP4CDS Data Service.
* [esgf-pyclient](https://esgf-pyclient.readthedocs.io/en/latest/)
  * Python library for searching ESGF holdings.
  * esgf-pyclient was used in the project for querying data availability. It is used by a wider community as a tool for locating, and downloading, data sets held on ESGF, or CP4CDS, systems.
* [synda](http://prodiguer.github.io/synda/) - Python command-line tool for searching, selecting, downloading and replicating ESGF data.
  * Synda has been used for identifying data within other parts of the federation, and replicating data between sites.
  * It can also be used by end-users to manage bulk transfers of ESGF, or CP4CDS, data sets from remote sites.

Compute Service Software:

* [Birdhouse](http://bird-house.github.io/) - The Birdhouse Web Processing Service framework, a server and client environment for hosted processing.
  * Birdhouse has provided the basic structure and templates for creating new Web Processing Services (WPS) within the project.
* [SDDS](https://sdds.readthedocs.io/en/latest/) - The CP4CDS Software Dependency Deployment Solution, a framework for defining and sharing software environments.
  * The SDDS has provided a re-usable system for defining and developing software environments to support specific WPS deployments.
  * The SDDS uses the Conda package management tool to capture, and reproduce, python software environments.
* [PyWPS](https://pywps.org/) - PyWPS is an implementation of the Web Processing Service standard.
  * PyWPS is used as the core package within Birdhouse for providing basic WPS functionality.

## WPS application documentation

Documentation links are provided here for building/deploying WPS applications developed within the project:

* [CliMAF WPS](https://climaf-wps-demo.readthedocs.io/en/latest/) - A Web Processing Service for CliMAF.
* [C4CDS WPS](https://c4cds-wps.readthedocs.io/en/latest/) - A WPS Compute Service for CMIP5 and CORDEX climate model data.
