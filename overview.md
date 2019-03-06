---
layout: page
title: Overview
permalink: /overview/
---
## What is the project about?

The *CP4CDS* project provides climate projections for the [Climate Data Store](https://cds.climate.copernicus.eu) (CDS).
The Climate Data Store is part of the European [Copernicus Climate Change Service](https://climate.copernicus.eu/) (C3S).

*CP4CDS* means *Climate Projections for Climate Data Store*.

We currently provide a subset of the [CMIP5 global climate model data](https://www.wcrp-climate.org/wgcm-cmip/wgcm-cmip5).
This data is made accessible via web-services using standard interfaces like [OpenDAP](https://www.opendap.org/)
and using the [ESGF](https://esgf.llnl.gov/) software stack.

In addition we provide compute services for predefined operations on the climate data pool, like subsetting and re-gridding.
These computations are available via a web-service using the
[Web Processing Service](http://opengeospatial.org/standards/wps) standard interface.
We also serve more advanced operations on climate data using the [C3S MAGIC toolbox](https://portal.c3s-magic.eu/).

![cp4cds](https://github.com/cehbrecht/copernicus-talk-july-2018/raw/master/media/cp4cds.png){:class="img-responsive"}

Our project highlights are:
* Access to a quality controlled subset of CMIP5 data.
* A resilient infrastructure for data and compute services.
* An extendable software solution for additional datasets and processing tools.
