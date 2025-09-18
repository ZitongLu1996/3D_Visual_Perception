# 3D Visual Perception – Code and Data

This repository provides the code and dataset accompanying the paper:   
Lu, Z., & Golomb, J. D. (2025). Unfolding spatiotemporal representations of 3D visual perception in the human brain. bioRxiv, 2025.

---

## 1. Dependencies

Python 3.10+   
Key Python packages include:  
  - `numpy >= 1.23`   
  - `scipy >= 1.11`    
  - `mne >= 1.6`   
  - `nibabel >= 5.2`   
  - `nilearn >= 0.11` 
  - `pandas >= 2.2`   
  - `pycortex`   
  - `neurora >= 1.1.6` 

---

## 2. Dataset Downloading

Please fill out the dataset request form via the link below, then you will get the link of our dataset.   
[https://forms.gle/5mL5ZwRT7RWym2UJA](https://forms.gle/5mL5ZwRT7RWym2UJA)

---

## 3. Scripts Description

code/Generate_hyp_feature_RDMs.ipynb
> To generate all hypthesis-based feature RDMs.

code/Behavioral_analysis_and_visualization.ipynb
> Behavioral analyses on pre-task 3 (Cube Adjustment Task) and visualization of individual results.

code/EEG_analysis_and_visualization.ipynb
> RSA analyses based on EEG signals and visualizations of key results.

code/fMRI_analysis_and_visualization.ipynb
> RSA analyses based on fMRI signals and visualizations of key results. (*We didn't include all the codes for geometric distance representations, ROI-based analyses, and permutation analyses - which are highly similar to the code you will find in this file.)

---

## 4. Notes on data processing

Functional MRI data were transformed from **Talairach (TAL)** space to **MNI152** space using **ANTs (Advanced Normalization Tools)**.

The MNI-aligned fMRI data were projected to the **fsaverage** cortical surface using **FreeSurfer**.

For the surface-based results, we used **pycortex** and **nilearn** to perform the visualizations.

---

## 5. License

This code is released under the MIT License.

---

## 6. Citation

If you use this code or dataset, please cite the following article:
> Lu, Z. & Golomb, J. D. (2025). Spatiotemporal representations of 3D spatial location in the human brain. Nature Communications.
