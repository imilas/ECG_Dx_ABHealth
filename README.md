**Machine Learning Algorithms based on Electrocardiograms for Cardiovascular Diagnoses at the Population Level.**

---
Citation
```
TBD
```

Bibtext
```
TBD
```

Abstract summary
```
This study develops and validates  models for predicting 15 different common cardiovascular diagnoses. We conducted a retrospective study that included 1,605,268 ECGs of 244,077 adult patients and considered 15 CV diagnoses: Atrial Fibrillation (AF), Supraventricular Tachycardia (SVT), Ventricular Tachycardia (VT), Cardiac Arrest (CA), Atrioventricular Block (AVB), Unstable Angina (UA), Non-ST elevation Myocardial Infarction (NSTEMI), ST elevation Myocardial Infarction (STEMI), Pulmonary Embolism (PE), Hypertrophic Cardiomyopathy (HCM), Aortic Stenosis (AS), , Mitral Valve Prolapse (MVP), Mitral Valve Stenosis (MS), Pulmonary Hypertension (PHTN), and Heart Failure (HF). We explored two approaches to learn models, each using  a patient’s ECG, age and sex to diagnose these 15 diagnoses: deep learning (DL) (based on ECG tracings) and extreme gradient boosting (XGB) (based on ECG measurements). 

The DL models had an AUROC of < 80% for 3 CV conditions (PTE, SVT, UA), 80-90% for 8 CV conditions (cardiac arrest, NSTEMI, VT, MVP, PHTN, AS, AF, HF) and an AUROC > 90% for 4 diagnoses (AVB, HCM, MS, STEMI).  Moreover, they performed better than XGB for most CV conditions (on average 5.2% higher AUROC) .  

While both ECG-based DL and XGB prediction models demonstrated good-to-excellent prediction performance in diagnosing common cardiovascular conditions, DL models provided better prediction than XGB models and could be used as a future screening tool.
```


## Setup
    - Conda/mamba environment recommended for tensorflow
        - Tensorflow: mamba install tensorflow-gpu
    - pip3 for the following libraries:
        - pandas 1.4.2
        - numpy 1.21.6
        - matplotlib, scikit-learn, seaborn
## See demo_data directory for example data and labels
    - Each 12 ECG stored as a .npy file
    - labels stored in demo_labels.csv
    - age and sex features in demo_asfeats.csv
    - ecgId is used to match the ECGs to labels and age/sex features

