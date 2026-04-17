# TNBC Diffusion — Tumor Modeling & Analysis Pipeline

This project implements a computational pipeline for analyzing **Triple Negative Breast Cancer (TNBC)** using clinical data, MRI imaging, and physics-based tumor modeling.

The workflow integrates:
- Clinical + imaging datasets
- DICOM preprocessing
- Tumor segmentation and mesh generation
- PDE-based tumor simulation
- Sensitivity and response analysis

---

## Repository Structure

```
data/
  processed/              # Cleaned datasets (clinical + imaging)

notebooks/
  01_data_exploration.ipynb
  02_patient_selection.ipynb
  03_dicom_exploration.ipynb
  04_batch_dicom_processing.ipynb
  05_pde_mesh_solver.ipynb

outputs/
  figures/                # Generated plots
  meshes/                 # 3D tumor meshes (.stl)

README.md
.gitignore
```

---

## Current Progress

### Completed

- Project structure setup
- Processed dataset creation
- Exploratory Data Analysis (EDA)
- Patient cohort selection
- DICOM exploration and validation
- Batch DICOM preprocessing
- Tumor mask generation
- 3D tumor mesh reconstruction
- PDE-based tumor simulation
- Sensitivity analysis
- Visualization outputs

---

## Raw Data Source

### I-SPY2 Dataset
https://www.cancerimagingarchive.net/collection/ispy2/

Files:
- ISPY2-Imaging-Cohort-1-Clinical-Data.xlsx
- Multi-feature-MRI-NACT-Data.xlsx
- Analysis-mask-files-description.v20211020.docx

---

### I-SPY2 Imaging Data (DICOM)
https://nbia.cancerimagingarchive.net/nbia-search/?MinNumberOfStudiesCriteria=1&CollectionCriteria=ISPY2

Selected Patients:
ISPY2-910706, ISPY2-489504, ISPY2-578975, ISPY2-625854, ISPY2-208303, ISPY2-774840, ISPY2-727804, ISPY2-564234, ISPY2-252748, ISPY2-697098, ISPY2-829491, ISPY2-622315, ISPY2-233191, ISPY2-502486, ISPY2-535779, ISPY2-164468, ISPY2-571995, ISPY2-934906, ISPY2-196024, ISPY2-955035

---

## Notes

- Raw DICOM and clinical data are not included due to size and privacy constraints
- Only processed and derived outputs are stored in the repository
- Mesh files (.stl) represent tumor geometry used for PDE simulations

---

## Next Steps

- Integrate ML models for prediction
- Cross-modal analysis (image + clinical)
- Extend PDE modeling
- Add evaluation benchmarks
