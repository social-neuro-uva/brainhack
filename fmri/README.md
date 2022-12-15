# fMRI

## glm

- *first_level_from_bids.ipynb* fits first-level GLMs condition-wise for traditional GLM analysis, and trial-wise for task-based functional connectivity and brain decoding.

- *decoding.ipynb* takes in single-trial GLM coefficients computed in *first_level_from_bids.ipynb* and trains a classifier for stimulus/ events from the first-level design matrices. This procedure is known as multi[variate/voxel]-pattern analysis (MVPA).

## conn

- TBD
