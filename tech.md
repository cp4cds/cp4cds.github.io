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
  * https://github.com/ESGF/esgf.github.io/wiki/ESGF_Search_REST_API
* [Geographically load-balanced Compute Service using the Web Processing Service (WPS) standard interface](http://compute.mips.copernicus-climate.eu/wps?service=WPS&version=1.0.0&request=GetCapabilities)
  * This interface is an **XML document**. It is a *computational interface* that can be interacted with by various WPS client tools. An example client tool is the Phoenix interface, hosted by DKRZ. This provides a graphical user interface for interacting with a WPS service:
  * https://bovec.dkrz.de/processes/list?wps=ccds


## Software

Please check the list of our software tools we use in our data and compute infrastructure.

Data Service Software:

* [ESGF Installer](https://github.com/ESGF/esgf-installer/wiki) - Installation Guide for ESGF data nodes.
* [esgf-pyclient](https://esgf-pyclient.readthedocs.io/en/latest/) - Python library for searching ESGF holdings.
* [synda](http://prodiguer.github.io/synda/) - Python command-line tool for searching, selecting, downloading and replicating ESGF data.

Compute Service Software:

* [Birdhouse](http://bird-house.github.io/) - The Birdhouse Web Processing Service framework, a server and client environment for hosted processing.
* [SDDS](https://sdds.readthedocs.io/en/latest/) - The CP4CDS Software Dependency Deployment Solution, a framework for defining and sharing software environments.
* [PyWPS](https://pywps.org/) - PyWPS is an implementation of the Web Processing Service standard.
* [GeoHealthCheck](https://geohealthcheck.org/) - GeoHealthCheck is a Python application to support monitoring OGC Web Services uptime and availability.

## Demo Applications

Compute Service Applications for Demonstration:

* [Copernicus WPS](https://copernicus-wps-demo.readthedocs.io/en/latest/) - The CP4CDS Compute Node, built on the Birdhouse WPS environment.
* [CliMAF WPS](https://climaf-wps-demo.readthedocs.io/en/latest/) - A Web Processing Service for CliMAF.
* [C4CDS WPS](https://c4cds-wps.readthedocs.io/en/latest/) - A WPS Compute Service for CMIP5 and CORDEX climate model data.
