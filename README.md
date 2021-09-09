 # APPEAR Toolbox #
# An Automatic Pipeline for EEG Artifact Reduction #
## Author: Obada Al Zoubi; obada.y.alzoubi@gmail.com

Removing artifacts from simultaneous EEG-fMRI recordings is a challenging issue since it requires manual
attending with specialized expertise. Additionally, manual correction is prone to experimenter biases in
cleaning data. Thus, we developed a fully automated pipeline for EEG artifacts reduction (APPEAR).
APPEAR was validated and compared to manual EEG preprocessing for two common applications - resting
and task-based EEG-fMRI acquisitions. APPEAR offers A-to-Z preprocessing for EEG and generates
ready-to-analyze output while cleaning MR, ballistocardiogram (BCG), pulse, eye blinking, saccades,
muscles, and single-channel artifacts. This is achieved by following well-validated steps using signal
processing and Independent Component Analysis (ICA). Also, APPEAR can be used to process large scale
datasets while supporting parallel implementations. In this technical report, we provide a detailed
explanation of using the toolbox while highlighting the important technical details for the user. APPEAR
is implemented using MATLAB software with dependencies on EEGLAB (Delorme & Makeig, 2004) and
fMRIb (Niazy, Beckmann, Iannetti, Brady, & Smith, 2005) toolboxes. We elaborate on several parameters
that are used in the APPEAR toolbox using demo examples. Additionally, we provide information about
several functions and features offered with the APPEAR toolbox. For APPEAR validation and analyses,
please refer to this manuscript (Mayeli et al., 2019).
