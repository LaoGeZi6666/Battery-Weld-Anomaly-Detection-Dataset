# Battery-Weld-Anomaly-Detection-Dataset 
![License](https://img.shields.io/badge/License-CC_BY--SA_4.0-green)  ![Updated](https://img.shields.io/badge/Last_Update-2025--03--25-blue) 
 
A comprehensive industrial anomaly detection dataset for battery welding processes, structured in [MVTec Anomaly Detection (MVTecAD)](https://www.mvtec.com/company/research/datasets/mvtec-ad)  format. Suitable for unsupervised/semi-supervised anomaly detection research.
 
## Dataset Structure 
Battery-Weld-Anomaly-Detection-Dataset/ 
├───<welding>/ # e.g., battery_weld │ ├── train/ │ │ └── good/ │ │ ├── 000.png
│ │ └── ... │ └── test/ │ ├── good/ │ ├── anomaly_type_1/ # e.g., crack │ │ ├── 000.png
│ │ └── ... │ └── anomaly_type_2/ # e.g., contamination ├───<category_2>/ └── ...
