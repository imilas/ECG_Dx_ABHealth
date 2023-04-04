# ECG_Dx_ABHealth
## Setup
    - Conda/mamba environment recommended for tensorflow
        - Tensorflow: mamba install tensorflow-gpu
    - pip3 for the following libraries:
        - pandas 1.4.2
        - numpy 1.21.6
        - matplotlib, scikit-learn
## See demo_data directory for example data and labels
    - Each 12 ECG stored as a .npy file
    - labels stored in demo_labels.csv
    - age and sex features in demo_asfeats.csv
    - ecgId is used to match the ECGs to labels and age/sex features

