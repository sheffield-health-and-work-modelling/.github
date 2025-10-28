# Codebase for Health and Work economic modelling

This GitHub organisation stores the R packages and associated repositories of simulation modelling, statistical analysis, and data processing for the modelling of the relationship between health and work. This work has been funded by several projects:

- [Support Employment beyond SMI](https://www.ipsbeyondsmi.org/)
- [Workplace Intervention for Sustainable Health and Employment Support (WISHES)]

## Overview
The analyses were developed by researchers at the [Sheffield Centre for Health and Related Research](https://www.sheffield.ac.uk/scharr) at the University of Sheffield, UK.

The modelling was developed in R and R studio, with particular attention to utilising new developments in the software environment to organise, document, and version control code.   

A set of internal STAPM R packages have been developed that contain code used for particular purposes, e.g. to process survey data such as the Understanding Society longitudinal dataset in a consistent and reproducible way. Packaging up code into modular functions and packages makes the processes applied in modelling easier to document, adapt and reuse across projects. Some code is spublicly available on this GitHub repository, but the majority is currently available only to the project team.  

# Structure 

This platform of modelling consists of several types of repository:

- Data: Repositories which process and clean large survey data sets used in health and work analyses, to be reused for multiple purposes.
- Analysis: Statistical analysis of datasets to inform parameters used in modelling.
- R packages: For storing reusable functions and parameters for routine use.
- Model: A repository which combines the use of R packages, data, and parameters into simulation models for modelling interventions and performing Cost-Benefit Analyses.
- Documentation: Reproducible technical reports detailing modelling methodologies.

## R packages 

- [ukhlsclean](https://github.com/sheffield-health-and-work-modelling/ukhlsclean): For cleaning Understanding Society: The UK Household Longitudinal Study.
- [frsclean](https://github.com/sheffield-health-and-work-modelling/frsclean): For cleaning the Family Resources Survey.
- [lfsclean](https://github.com/sheffield-health-and-work-modelling/lfsclean): For cleaning the quarterly cross-sectional and five-quarter longitudinal versions of the Labour Force Survey.

## Analysis (private)

- [labour-market-transition-probs](https://github.com/sheffield-health-and-work-modelling/labour-market-transition-probs): For the estimation of probabilities of transitioning between labour market states.
- [health-impacts-of-employment](https://github.com/sheffield-health-and-work-modelling/health-impacts-of-employment): For estimating the impact of changing labour market status on health.

## Model (private)

- [https://github.com/sheffield-health-and-work-modelling/work-and-health-interventions-model](https://github.com/sheffield-health-and-work-modelling/work-and-health-interventions-model): For undertaking simulation modelling of work and health interventions. 

