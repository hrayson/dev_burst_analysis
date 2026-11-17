# Developmental EEG beta-burst analysis

Analysis code for analyzing frequency-specific transient burst events in developmental EEG data.

## Paper

Rayson, H., Debnath, R., Alavizadeh, S., Fox, N., Ferrari, P. F., & Bonaiuto, J. J. (2022). [Detection and analysis of cortical beta bursts in developmental EEG data](https://doi.org/10.1016/j.dcn.2022.101069). *Developmental Cognitive Neuroscience*.

## Code

The five MATLAB tutorials, [`tutorial_1.m`](tutorial_1.m) through [`tutorial_5.m`](tutorial_5.m), demonstrate steps in the analysis. [`run_all.m`](run_all.m) is the batch analysis script. Set the paths to the prepared EEG data in the study configuration before running the scripts.

## Requirements

* MATLAB R2015b
* EEGLAB v14.1.1: https://sccn.ucsd.edu/eeglab/index.php
* FieldTrip v20190329: https://www.fieldtriptoolbox.org/
* shadedErrorBar: https://fr.mathworks.com/matlabcentral/fileexchange/26311-raacampbell-shadederrorbar?
* shadedErrorBaryy: https://uk.mathworks.com/matlabcentral/fileexchange/42578-shaded-error-bar-yy
* R v3.6.1
* R_rainclouds: https://github.com/RainCloudPlots/RainCloudPlots
