# Open Software for Human Electrophysiology

This is a list of openly available software and code for working with electrophysiological data, focused mainly on local field potential (LFP) type measurements from humans, specifically EEG, MEG, and ECoG/iEEG. This list is primarily maintained by [Tom Donoghue](https://github.com/TomDonoghue).

## Overview

The goal here is to list re-usable tools for working with the specified data, and is not generally focused on code that is avaialable for specific analysis on particular datasets (though these may be included where they are licensed for re-use, and are the best available starting point for a particular use case). 

This list is curated by the VoytekLab, but most of the code / tools indexed here are from external sources (our tools will be explicitly noted). We have not necessarily tried all of these tools, and offer no general endorsement of which to use.

When known, tools will be specified as having a graphic user interface (GUI) and/or if they are a plug-in for a general purpose library. 

By 'open', here we mean that source code is provided and is released with a permissive license. Commercial products are not listed here. Be sure to double check the license before using / modifying linked code. Note that some tools may require non-open dependencies (for example, Matlab tools are listed, but are not fully open). 

## General Purpose Tools

The following are general purpose platforms, with functionality including: loading data, pre-processing, visualization, standard analysis, and making figures. 

### MNE

![Language](https://img.shields.io/badge/Language-Python-blue.svg)
![Language](https://img.shields.io/badge/GUI-yes-lightgrey.svg)

[HomePage](http://martinos.org/mne/stable/index.html) - 
[Github](https://github.com/mne-tools/mne-python) - 
[Paper](https://doi.org/10.1016/j.neuroimage.2013.10.027)

MNE is a general purpose tool for processing, analyzing and visualizing M/EEG data. 

### FieldTrip

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![Language](https://img.shields.io/badge/GUI-yes-lightgrey.svg)

[HomePage](http://www.fieldtriptoolbox.org) - 
[Github](https://github.com/fieldtrip/fieldtrip) - 
[Paper](https://doi.org/10.1155/2011/156869)

FieldTrip is a general purpose tool for processing, analyzing and visualizing M/EEG data. 

### BrainStorm

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![Language](https://img.shields.io/badge/GUI-yes-lightgrey.svg)

[HomePage](https://neuroimage.usc.edu/brainstorm/) - 
[Github](https://github.com/brainstorm-tools/brainstorm3) - 
[Paper](https://doi.org/10.1155/2011/879716)

BrainStorm is a general purpose tool for processing, analyzing and visualizing focused primarily on MEG data, but includes support for EEG & ECoG data. 

### EEGLab

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![Language](https://img.shields.io/badge/GUI-yes-lightgrey.svg)

[HomePage](https://sccn.ucsd.edu/eeglab/index.php) - 
[Paper](https://doi.org/10.1016/j.jneumeth.2003.10.009)

EEGLab is a general purpose tool for processing, analyzing and visualizing EEG data.

### Wonambi

![Language](https://img.shields.io/badge/Language-Python-blue.svg)
![Language](https://img.shields.io/badge/GUI-yes-lightgrey.svg)

[HomePage](https://wonambi-python.github.io) - 
[Github](https://github.com/wonambi-python/wonambi)

EEGLab is a general purpose tool for processing, analyzing and visualizing EEG data.

### NutMEG

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

[HomePage](https://www.nitrc.org/plugins/mwiki/index.php/nutmeg:MainPage) - 
[Github](https://github.com/UCSFBiomagneticImagingLab/nutmeg) - 
[Paper](https://doi.org/10.1155/2011/758973)

NutMEG is a general purpose tool for processing, analyzing and visualizing MEG data.

### EEGUtils

![Language](https://img.shields.io/badge/Language-R-lightgrey.svg)

[HomePage](https://craddm.github.io/eegUtils/) - 
[Github](https://github.com/craddm/eegUtils)

EEGUtils is a general purpose tool for processing, analyzing and visualizing EEG data.

## Standalone Tools - Specific Purposes

### NeuroDSP

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

NeuroDSP is a package for calculating a broad range of measures on neural time series, including a range of time-domain measures such as waveform shape analyses. 

Note: NeuroDSP is a tool developed by the VoytekLab. 

[Github](https://github.com/voytekresearch/neurodsp)

### FOOOF

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

FOOOF is a package for parameterizing neural power spectra. 

Note: FOOOF is a tool developed by the VoytekLab. 

[Github](https://github.com/voytekresearch/fooof) - 
[Paper](https://doi.org/10.1101/299859)

### Spectral Connectivity

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

Spectral connectivity is a package including a group of functional connectivity and coherence related measures.

[HomePage](http://spectral-connectivity.readthedocs.io/en/latest/index.html) - 
[Github](https://github.com/Eden-Kramer-Lab/spectral_connectivity) - 

### OpenMEEG

![Language](https://img.shields.io/badge/Language-C++-green.svg)

OpemMEEG is a package for solving forward problems for EEG & MEG data.

[HomePage](http://openmeeg.github.io) - 
[Github](https://github.com/openmeeg/openmeeg) - 
[Paper](https://doi.org/10.1186/1475-925X-9-45)

### PACTools

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

[HomePage](https://pactools.github.io) - 
[Github](https://github.com/pactools/pactools)

PACTools is a package for calculating phase-amplitude coupling measures in neural time series. 

### restingIAF

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

RestingIAF is a tool for estimating the peak individual alpha frequency.

[Github](https://github.com/corcorana/restingIAF) - 
[Paper](https://doi.org/10.1111/psyp.13064)

### Phase Opposition Code

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

Phase Opposition is a collection of functions for calculating phase opposition measures. 

[HomePage](http://www.cerco.ups-tlse.fr/~rufin/PhaseOppositionCode/) - 
[Paper](https://doi.org/10.3389/fnins.2016.00426)

### PyEEG

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

[Github](https://github.com/forrestbao/pyeeg)

PyEEG includes some implementations of information theoretic and complexity related measures for neural time series. 

## PlugIns

The following are some plug-ins, designed primary for use with one of the aforementioned general purpose tools. 

### PREP Pipeline (Standardized EEG pre-processing)

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-EEGLab-orange.svg)

The PREP pipeline is a standardized processing tool for EEG data, using EEGLab. 

[HomePage](http://vislab.github.io/EEG-Clean-Tools/) - 
[Github](https://github.com/VisLab/EEG-Clean-Tools) - 
[Paper](https://doi.org/10.3389/fninf.2015.00016)

### AutoReject

![Language](https://img.shields.io/badge/Language-Python-blue.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-MNE-blue.svg)

AutoReject is a tool for pre-processing M/EEG data, but algorithmically determining and applying rejection thresholds, with MNE.

[HomePage](http://autoreject.github.io) - 
[Github](https://github.com/autoreject/autoreject) - 
[Paper](https://doi.org/10.1016/j.neuroimage.2017.06.030)

### LIMO

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-EEGLab-orange.svg)

LIMO is a tool for Linear Modelling of EEG data, with EEGLab. 

[HomePage](https://github.com/LIMO-EEG-Toolbox/limo_eeg/wiki) - 
[Github](https://github.com/LIMO-EEG-Toolbox/limo_eeg) - 
[Paper](https://doi.org/10.1155/2011/831409)

### ERPlab

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-EEGLab-orange.svg)

ERPLab is a tool for event-related potential (ERP) analysis of EEG data, with EEGLab. 

[HomePage](https://erpinfo.org/erplab) - 
[Github](https://github.com/lucklab/erplab) - 
[Paper](https://doi.org/10.3389/fnhum.2014.00213)

## Tutorials and/or Lab or Project Specific Code

The following are known tutorials that may be useful to start with particular analyses, and/or other known code from labs or projects that may be useful and re-usable. 

### Inverted Encoding Models

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

This repository includes tutorials for using inverted encoding models (IEM), including with EEG. 

[Github](https://github.com/tommysprague/IEM-tutorial)

### Encoding / Decoding Code & Tutorials for Electrophysiology

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

This repository includes tutorials for using encoding and decoding models on electrophysiological data. 

[Github](https://github.com/choldgraf/paper-encoding_decoding_electrophysiology) - 
[Paper](https://doi.org/10.3389/fnsys.2017.00061)
