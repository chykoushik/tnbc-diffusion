## Current Progress

### Completed

- Initial project structure setup
- Data organization into:
  - `raw/` (ignored)
  - `processed/`
  - `patients/` (excluded for privacy)
- Exploratory data analysis
- Patient cohort selection logic
- Initial notebooks:
  - `01_data_exploration.ipynb`
  - `02_patient_selection.ipynb`
- Git repository setup with proper `.gitignore`

---

## Raw Data Source

TCGA-BRCA (Clinical Data)  
https://portal.gdc.cancer.gov/projects/TCGA-BRCA  

File:
- clinical.project-tcga-brca.2026-04-12.tar.gz

---

I-SPY2 Dataset  
https://www.cancerimagingarchive.net/collection/ispy2/

Files:
- ISPY2-Imaging-Cohort-1-Clinical-Data.xlsx
- Multi-feature-MRI-NACT-Data.xlsx
- Analysis-mask-files-description.v20211020.docx

---

I-SPY2 Imaging Data (DICOM)  
https://nbia.cancerimagingarchive.net/nbia-search/?MinNumberOfStudiesCriteria=1&CollectionCriteria=ISPY2

Selected Patients:
ISPY2-910706, ISPY2-489504, ISPY2-578975, ISPY2-625854, ISPY2-208303, ISPY2-774840, ISPY2-727804, ISPY2-564234, ISPY2-252748, ISPY2-697098, ISPY2-829491, ISPY2-622315, ISPY2-233191, ISPY2-502486, ISPY2-535779, ISPY2-164468, ISPY2-571995, ISPY2-934906, ISPY2-196024, ISPY2-955035
