# Investigating the effect of alpha band on TRFs

# Background

The alpha band (α-wave) is a type of brainwave with a frequency range of approximately 8 to 12 Hz, often associated with relaxation and closed-eye states. Temporal Response Functions (TRFs) are models used to analyze the brain's response to time-series stimuli, particularly in the context of speech processing. 

Given our interest in understanding whether α-waves influence TRFs during language processing, our project aims to explore the impact of including or excluding α-waves on TRFs. Using an open dataset, we seek to determine how the presence or absence of α-waves affects the modeling and interpretation of neural responses in speech processing.

# Data

## Tools
The dataset processing by using mne-python
## Quickstart



## Workflow
![procedure](https://github.com/Aiame/2024_brain_hack_school_project/assets/127302047/02da82a1-8a8f-471f-b1e0-2bd33666e010)

## Results
subject 13
![output1](https://github.com/Aiame/2024_brain_hack_school_project/assets/127302047/59d47fd7-c0da-46c0-95d3-c3bede280c8b)
subject 18
![output2](https://github.com/Aiame/2024_brain_hack_school_project/assets/127302047/f506544d-c1b5-43d7-ba86-0e52ab8b5b2d)
subject 38
![output](https://github.com/Aiame/2024_brain_hack_school_project/assets/127302047/1746d269-7fec-4b13-ab4d-1a6ebcfe9f49)

## Conclusion and acknowledgement

In our study of three participants, removing the alpha band affected TRFs, with some features being suppressed and others enhanced. This simplification highlighted local signals, making brain activity clearer. However, it's unclear if these enhanced signals represent true brain activity or noise, requiring further analysis for validation.

## Reference
Alice dataset: https://github.com/Eelbrain/Alice/tree/main

Bhattasali, S., Brennan, J., Luh, W. M., Franzluebbers, B., & Hale, J. (2020). The Alice Datasets: fMRI & EEG observations of natural language comprehension. In Proceedings of the Twelfth Language Resources and Evaluation Conference (pp. 120-125).

# team member
Kuan-Yu Chen, Ruo-Chi Yao, Liang-Mei Lin, Ming-Feng Hsin
