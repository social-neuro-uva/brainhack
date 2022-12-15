# UVA BrainHack

## Description

- This is a repository for the weekly collaborative BrainHack sessions at the University of Virginia. Included are shared resources for solving various problems in human neuroscience research, notably fMRI and EEG techniques.

## fmri

- *first_level_from_bids.ipynb* fits first-level GLMs condition-wise for traditional GLM analysis, and trial-wise for task-based functional connectivity and brain decoding.

- *decoding.ipynb* takes in single-trial GLM coefficients computed in *first_level_from_bids.ipynb* and trains a classifier for stimulus/ events in the scanner from the first-level design matrices. This procedure is known in the cognitive neuroscience field as multi[variate/voxel]-pattern analysis (MVPA).

## eeg

- Add examples one-by-one (TBD, focusing on imaging at the moment).

## Contact

For questions, feel free to contact Andrew J. Graves (ajg3eh@virginia.edu).
