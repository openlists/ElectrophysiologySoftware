# Open Software for Human Electrophysiology

This is a list of openly available software and code for working with electrophysiological data, including EEG, MEG, ECoG/iEEG, and LFP.

## Table of Contents

- [Overview](#overview)
- [General Purpose Tools](#general-purpose-tools)
- [Standalone Tools](#standalone-tools)
- [Plugins](#plugins)
- [Neuro Tools](#neuro-tools)

## Overview

This list is focused on re-usable tools for working with electrophysiological data. Generally, this does not include code that is available for specific analysis on particular datasets (though these may be included where they are potentially useful and licensed for re-use).

By 'open', here we mean that source code is provided and is released with a permissive license. Commercial products are not listed. Be sure to double check the license before using / modifying linked code. Note that some tools may require non-open dependencies (for example, Matlab tools are listed, but are not fully open).

Other available lists of relevant tools include:
- The [Physionet](https://physionet.org/) project maintains a [list of software](https://physionet.org/about/software/) available in the PhysioToolkit
    -  This includes some software that can be used with electrophysiology data.

## General Purpose Tools

The following are general purpose platforms, with functionality including: loading data, preprocessing, visualization, standard analysis, and making figures.

### MNE

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`MNE` is a general purpose tool for processing, analyzing, and visualizing M/EEG data.

[HomePage](https://martinos.org/mne/stable/index.html) -
[Github](https://github.com/mne-tools/mne-python) -
[Paper](https://doi.org/10.1016/j.neuroimage.2013.10.027)

### Neural Ensemble Tools

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

[Neural Ensemble](https://neuralensemble.org/) is an initiative for open-source software in neuroscience and includes a set of tools for managing and analyzing electrophysiology data.

`neo` is a tool for representing electrophysiology data, and reading neurophysiological file formats.

[HomePage](https://neo.readthedocs.io/en/latest/) -
[Github](https://github.com/NeuralEnsemble/python-neo)

`elephant` is a tool for analyzing electrophysiological data.

[HomePage](https://neuralensemble.org/elephant/) -
[Github](https://github.com/NeuralEnsemble/elephant)

### Wonambi

![Language](https://img.shields.io/badge/Language-Python-blue.svg)
![Language](https://img.shields.io/badge/GUI-yes-lightgrey.svg)

`Wonambi` is a general purpose tool for processing, analyzing, and visualizing EEG data, including specific tools focused on sleep scoring and analysis.

[HomePage](https://wonambi-python.github.io) -
[Github](https://github.com/wonambi-python/wonambi)

### NeuroKit2

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`NeuroKit2` is a tool for neurophysiological signal processing.

[HomePage](https://neurokit2.readthedocs.io/en/latest/) -
[Github](https://github.com/neuropsychology/NeuroKit)

### FieldTrip

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![Language](https://img.shields.io/badge/GUI-yes-lightgrey.svg)

`FieldTrip` is a general purpose tool for processing, analyzing, and visualizing M/EEG and iEEG/ECoG data.

[HomePage](http://www.fieldtriptoolbox.org) -
[Github](https://github.com/fieldtrip/fieldtrip) -
[Paper](https://doi.org/10.1155/2011/156869)

### BrainStorm

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![Language](https://img.shields.io/badge/GUI-yes-lightgrey.svg)

`BrainStorm` is a general purpose tool for processing, analyzing and visualizing focused primarily on MEG data, with additional support for EEG & ECoG data.

[HomePage](https://neuroimage.usc.edu/brainstorm/) -
[Github](https://github.com/brainstorm-tools/brainstorm3) -
[Paper](https://doi.org/10.1155/2011/879716)

### EEGLab

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![Language](https://img.shields.io/badge/GUI-yes-lightgrey.svg)

`EEGLab` is a general purpose tool for processing, analyzing, and visualizing EEG data.

[HomePage](https://sccn.ucsd.edu/eeglab/index.php) -
[Paper](https://doi.org/10.1016/j.jneumeth.2003.10.009)

### SPM

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![Language](https://img.shields.io/badge/GUI-yes-lightgrey.svg)

`SPM` is a general purpose toolbox for neuroimaging, including support for processing M/EEG data.

[HomePage](https://www.fil.ion.ucl.ac.uk/spm/)

### NutMEG

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`NutMEG` is a general purpose tool for processing, analyzing, and visualizing MEG data.

[HomePage](https://nitrc.org/plugins/mwiki/index.php/nutmeg:MainPage) -
[Github](https://github.com/UCSFBiomagneticImagingLab/nutmeg) -
[Paper](https://doi.org/10.1155/2011/758973)

### Signaleeg

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`Signaleeg` is a general purpose tool for processing and analyzing EEG data, with a focus on signal-data mining.

[Code](https://caleta.udg.edu/git/eXiT_Research_Group/Signaleeg/src/branch/v1) -
[Paper](https://doi.org/10.1007/s12021-020-09507-2)

### BBCI - Berlin brain-computer interface

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

The `BBCI` tool is collection of tools for online and offline analyses for brain-computer interface experiments.

[Github](https://github.com/bbci/bbci_public) -
[Paper](https://doi.org/10.3389/fnins.2016.00530)

### EEGUtils

![Language](https://img.shields.io/badge/Language-R-lightgrey.svg)

`EEGUtils` is a general purpose tool for processing, analyzing, and visualizing EEG data.

[HomePage](https://bnicenboim.github.io/eeguana/) -
[Github](https://github.com/craddm/eegUtils)

### EEGuana

`EEGuana` is a package for working with EEG data.

![Language](https://img.shields.io/badge/Language-R-lightgrey.svg)

[HomePage](https://craddm.github.io/eegUtils/) -
[Github](https://github.com/bnicenboim/eeguana/tree/master/R)

### EEG.jl

![Language](https://img.shields.io/badge/Language-Julia-green.svg)

`EEG.jl` is library for processing EEG data.

[HomePage](https://eegjl.readthedocs.io/en/latest/) -
[Github](https://github.com/rob-luke/EEG.jl)

### CarTool

![Language](https://img.shields.io/badge/Language-C++-yellowgreen.svg)

`CarTool` is an EEG analysis toolbox.

[HomePage](https://sites.google.com/site/cartoolcommunity/) -
[Paper](https://doi.org/10.1155/2011/813870)

## Standalone Tools

The following are standalone tools, independent of general software platforms, for specific purposes.

### NeuroDSP

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`NeuroDSP` is a package for calculating a broad range of measures on neural time series, including a range of time-domain measures such as waveform shape analyses.

[Homepage](https://neurodsp-tools.github.io/) -
[Github](https://github.com/neurodsp-tools/neurodsp) -
[Paper](https://doi.org/10.21105/joss.01272)

### SpecParam (formerly 'fooof')

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`SpecParam` (formerly called `fooof`) is a package for parameterizing neural power spectra.

[Homepage](https://fooof-tools.github.io/) -
[Github](https://github.com/fooof-tools/fooof) -
[Paper](https://doi.org/10.1038/s41593-020-00744-x)

### ByCycle

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`ByCycle` is a tool for cycle-by-cycle analyses of neural oscillations.

[Homepage](https://bycycle-tools.github.io/) -
[Github](https://github.com/bycycle-tools/bycycle) -
[Paper](https://doi.org/10.1152/jn.00273.2019)

### IRASA

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

A Python implementation of the 'irregular resampling auto-spectral analysis'.
Note that this is a re-implementation of the algorithm described in the paper.

[Github](https://github.com/jrudoler/irasa) -
[Paper](https://doi.org/10.1007/s10548-015-0448-0)

### Frites - Framework for Information Theoretic analysis of Electrophysiological data and Statistics

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`FRITES` is package for computing information-theoretic measures on human and electrophysiological data.

[Homepage](https://brainets.github.io/frites/) -
[Github](https://github.com/brainets/frites)

### Antropy

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`Antropy` is a package for computing entropy and complexity measures on EEG data.

[Homepage](https://raphaelvallat.com/antropy/build/html/index.html) -
[Github](https://github.com/raphaelvallat/antropy)

### PTSA - Python Time Series Analysis

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`PTSA` is package for time series analysis in Python, focused on analyzing electrophysiological data.

[Homepage](https://pennmem.github.io/ptsa_new/html/index.html) -
[Github](https://github.com/pennmem/ptsa_new)

### GhostiPy - General Hub Of Spectral Techniques In Python

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`Ghostipy` is a toolbox for signal processing and spectral analyses.

[Github](https://github.com/kemerelab/ghostipy) -
[Paper](https://doi.org/10.1523/ENEURO.0202-21.2021)

### Spectral Connectivity

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`Spectral Connectivity` is a package for functional connectivity and coherence related measures.

[HomePage](https://spectral-connectivity.readthedocs.io/en/latest/index.html) -
[Github](https://github.com/Eden-Kramer-Lab/spectral_connectivity)

### Brain Connectivity Toolbox for Python

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

The `Brain Connectivity Toolbox` is a package for brain connectivity measures.

[Github](https://github.com/aestrivex/bctpy)

### Tensor PAC

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`TensorPAC` is a tool for calculating phase-amplitude coupling measures, using tensors and parallel computing.

[HomePage](https://etiennecmb.github.io/tensorpac/) -
[Github](https://github.com/EtienneCmb/tensorpac) -
[Paper](https://doi.org/10.1371/journal.pcbi.1008302)

### PACTools

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`PACTools` is a package for calculating phase-amplitude coupling measures in neural time series.

[HomePage](https://pactools.github.io) -
[Github](https://github.com/pactools/pactools)

### PyEEG

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`PyEEG` includes some implementations of information theoretic and complexity related measures for neural time series.

[Github](https://github.com/forrestbao/pyeeg) -
[Paper](https://doi.org/10.1155/2011/406391)

### ECoGTools

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`ECoGTools` is a collection of tools for analyzing ECoG data.

[Github](https://github.com/choldgraf/ecogtools)

### EELBrain

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`EELBrain` is a tool for statistical analysis of M/EEG data.

[HomePage](https://eelbrain.readthedocs.io/en/stable/index.html) -
[Github](https://github.com/christianbrodbeck/Eelbrain) -
[Paper](https://www.biorxiv.org/content/10.1101/2021.08.01.454687v1)

### YASA - Yet another spindle algorithm

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`YASA` is a package for analyzing polysomnograghy recordings.

[HomePage](https://raphaelvallat.com/yasa/build/html/index.html) -
[Github](https://github.com/raphaelvallat/yasa)

### kCSD - kernel Current Source Density

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

The `kCSD` tool implements kernel Current Source Density.

[HomePage](https://kcsd-python.readthedocs.io/en/latest/) -
[Github](https://github.com/Neuroinflab/kCSD-python) -
[Paper](https://www.biorxiv.org/content/10.1101/708511v1.abstract)

### EMD - Empirical Mode Decomposition

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

The `EMD` toolbox implements empirical mode decomposition and Hilbert-Huang spectral analyses.

[HomePage](https://emd.readthedocs.io/) -
[Code](https://gitlab.com/emd-dev/emd) -
[Paper](http://doi.org/10.21105/joss.02977)

### eBOSC - extended Better OSCillation detector

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`eBOSC` is a tool for oscillation detection and measurement.

[Github](https://github.com/jkosciessa/eBOSC) -
[Paper](http://doi.org/10.1016/j.neuroimage.2019.116331)

### BEST - Brain Electrophysiological recording & STimulation

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`BEST` is a tool for designing and running non-invasive brain stimulation experiments.

[Homepage](https://www.best-toolbox.org/) -
[Github](https://github.com/umair-hassan/best-toolbox) -
[Paper](https://doi.org/10.1016/j.brs.2021.11.017)

### restingIAF

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`RestingIAF` is a tool for estimating the peak individual alpha frequency.

[Github](https://github.com/corcorana/restingIAF) -
[Paper](https://doi.org/10.1111/psyp.13064)

### Phase Opposition Code

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

Phase Opposition is a collection of functions for calculating phase opposition measures.

[HomePage](http://www.cerco.ups-tlse.fr/~rufin/PhaseOppositionCode/) -
[Paper](https://doi.org/10.3389/fnins.2016.00426)

### ADAM - Amsterdam Decoding and Modeling Toolbox

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`ADAM` is a tool for encoding and decoding model analysis on M/EEG data.

[Github](https://github.com/fahrenfort/ADAM) -
[Paper](https://doi.org/10.1007/s12021-013-9186-1)

### HERMES

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`HERMES` is tool for estimating connectivity measures between M/EEG signals.

[HomePage](http://hermes.ctb.upm.es) -
[Github](https://github.com/guiomar/HERMES) -
[Paper](https://doi.org/10.3389/fnins.2018.00368)

### SEREEGA - Simulating Event-Related EEG Activity

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`SEREEGA` is a package for simulating synthetic data that mimic event-related EEG activity.

[Github](https://github.com/lrkrol/SEREEGA) -
[Paper](https://doi.org/10.1101/326066)

### UNFOLD

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`Unfold` is a tool for deconvolving overlapping EEG signals and for non-linear modeling.

[HomePage](https://www.unfoldtoolbox.org) -
[Github](https://github.com/unfoldtoolbox/unfold) -
[Paper](https://doi.org/10.7717/peerj.7838)

### ept-TFCE

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`ept-TFCE` is a tool for statistical analysis of already preprocessed M/EEG data, focused mainly around the 'threshold-free cluster enhancement' method.

[Github](https://github.com/Mensen/ept_TFCE-matlab) -
[Paper](https://doi.org/10.1016/j.neuroimage.2012.10.027)

### ERA - ERP Reliability Analysis

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`ERA` is a tool for calculating reliability estimates for ERP data.

[HomePage](http://peterclayson.com/era-toolbox/) -
[Github](https://github.com/peclayson/ERA_Toolbox) -
[Paper](https://doi.org/10.1016/j.ijpsycho.2016.10.012)

### SynchSqueezing

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`SynchroSqueezing` is a tool for time-frequency and time-scale analyses.

[Github](https://github.com/ebrevdo/synchrosqueezing)

### AutoMagic

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

`AutoMagic` is a standardized toolbox for preprocessing EEG datasets.

[Github](https://github.com/methlabUZH/automagic) -
[Paper](https://doi.org/10.1101/460469)

### MVGC - Multivariate Granger Causality Toolbox

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

The `MVGC` toolbox is designed to run Granger-causal analysis on multivariate time-series data.

[HomePage](https://users.sussex.ac.uk/~lionelb/MVGC/html/mvgchelp.html#3) -
[Code](https://www.sussex.ac.uk/sackler/mvgc/) -
[Paper](https://doi.org/10.1016/j.jneumeth.2013.10.018)

### OpenMEEG

![Language](https://img.shields.io/badge/Language-C++-yellowgreen.svg)

`OpemMEEG` is a package for solving forward problems for EEG & MEG data.

[HomePage](https://openmeeg.github.io) -
[Github](https://github.com/openmeeg/openmeeg) -
[Paper](https://doi.org/10.1186/1475-925X-9-45)

## Plugins

The following are plugins, designed primary for use with one of the aforementioned general purpose tools.

### AutoReject

![Language](https://img.shields.io/badge/Language-Python-blue.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-MNE-blue.svg)

`AutoReject` is a tool for preprocessing M/EEG data, but algorithmically determining and applying rejection thresholds, with MNE.

[HomePage](https://autoreject.github.io) -
[Github](https://github.com/autoreject/autoreject) -
[Paper](https://doi.org/10.1016/j.neuroimage.2017.06.030)

### MNE-BIDS

![Language](https://img.shields.io/badge/Language-Python-blue.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-MNE-blue.svg)

`MNE-BIDS` is a tool for creating [BIDS](https://bids.neuroimaging.io/) compatible datasets with MNE.

[HomePage](https://mne.tools/mne-bids/) -
[Github](https://github.com/mne-tools/mne-bids) -
[Paper](https://doi.org/10.21105/joss.01896)

### PyPREP

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`PrPREP` is an implementation of the 'Preprocessing Pipeline' (PREP) for EEG data, in Python and using MNE.

[Homepage](https://pyprep.readthedocs.io/en/latest/) -
[Github](https://github.com/sappelhoff/pyprep)

### PREP Pipeline

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-EEGLab-orange.svg)

The `PREP` pipeline is a standardized pre-processing tool for EEG data, using EEGLab.

[HomePage](https://vislab.github.io/EEG-Clean-Tools/) -
[Github](https://github.com/VisLab/EEG-Clean-Tools) -
[Paper](https://doi.org/10.3389/fninf.2015.00016)

### RELAX

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-EEGLab-orange.svg)

`RELAX` (Reduction of Electroencephalographic Artifacts) provides a fully automated method to clean EEG data.

[Github](https://github.com/NeilwBailey/RELAX) - 
[Paper1](https://doi.org/10.1101/2022.03.08.483548) - 
[Paper2](https://doi.org/10.1101/2022.03.08.483554)

### ADJUST

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-EEGLab-orange.svg)

`ADJUST` is an automatic artifact identification and removal tool, using EEGLab.

[HomePage](https://www.nitrc.org/projects/adjust/) -
[Paper](https://doi.org/10.1111/j.1469-8986.2010.01061.x)

### ERPlab

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-EEGLab-orange.svg)

`ERPLab` is a tool for event-related potential (ERP) analysis of EEG data, with EEGLab.

[HomePage](https://erpinfo.org/erplab) -
[Github](https://github.com/lucklab/erplab) -
[Paper](https://doi.org/10.3389/fnhum.2014.00213)

### LIMO - Linear Modeling

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-EEGLab-orange.svg)

`LIMO` is a tool for Linear Modeling of EEG data, with EEGLab.

[HomePage](https://github.com/LIMO-EEG-Toolbox/limo_eeg/wiki) -
[Github](https://github.com/LIMO-EEG-Toolbox/limo_eeg) -
[Paper](https://doi.org/10.1155/2011/831409)

### SIFT - Source Information Flow Toolbox

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-EEGLab-orange.svg)

`SIFT` is a tool for causality and information flow measures, with EEGLab.

[HomePage](https://sccn.ucsd.edu/wiki/SIFT)

### MPT - Measure Projection Toolbox

![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)
![PlugIn](https://img.shields.io/badge/PlugIn-EEGLab-orange.svg)

`MPT` is a tool for probabilistic multi-subject EEG independent component analysis, with EEGLab.

[HomePage](https://sccn.ucsd.edu/wiki/MPT)

## Neuro Tools

The following are broader purpose neuro-tools that could be used with electrophysiology data.

### nibabel

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`nibabel` is a tool for read/write access to common neuroimaging file formats.

[HomePage](https://nipy.org/nibabel/) -
[Github](https://github.com/nipy/nibabel)

### nilearn

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`nilearn` is a tool for applying machine learning to neuroimaging data.

[HomePage](https://nilearn.github.io/) -
[Github](https://github.com/nilearn/nilearn)

### Visbrain

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`Visbrain` is a tool for brain data visualization.

[Homepage](http://visbrain.org/) -
[Github](https://github.com/EtienneCmb/visbrain)

### PyCortex

![Language](https://img.shields.io/badge/Language-javascript-yellow.svg)

`PyCortex` is a tool for visualizing cortical surfaces.

[Homepage](https://gallantlab.github.io/pycortex/) -
[Github](https://github.com/gallantlab/pycortex)

### BrainSpace

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`BrainSpace` is a tool for analyzing gradients in neuroimaging datasets.

[HomePage](https://brainspace.readthedocs.io/en/latest/) -
[Github](https://github.com/MICA-MNI/BrainSpace) -
[Paper](https://doi.org/10.1038/s42003-020-0794-7)

### neuromaps

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

`neuromaps` is a tool for comparing between brain maps.

[HomePage](https://netneurolab.github.io/neuromaps/) -
[Github](https://github.com/netneurolab/neuromaps) -
[Paper](https://www.biorxiv.org/content/10.1101/2022.01.06.475081v1)
