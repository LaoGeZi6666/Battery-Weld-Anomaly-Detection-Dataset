# Battery-Weld-Anomaly-Detection-Dataset 
![License](https://img.shields.io/badge/License-CC_BY--SA_4.0-green)  ![Updated](https://img.shields.io/badge/Last_Update-2025--03--25-blue) 
 
A comprehensive industrial anomaly detection dataset for battery welding processes, structured in [MVTec Anomaly Detection (MVTecAD)](https://www.mvtec.com/company/research/datasets/mvtec-ad)  format. Suitable for unsupervised/semi-supervised anomaly detection research.
 
## Dataset Structure 
Battery-Weld-Anomaly-Detection-Dataset/ 
    ├── train           
    │       ├── good
    │           ├── .png
    
    ├── test    
    │       ├── good
    │           ├── .png
    │       ├── defective
    │           ├── .png
    
    ├── ground_truth             
    │       ├── defective
    │           ├── .png
    
    ├── train_welding.json
    ├── test_welding.json

## Citation 
Please cite both **MVTecAD** and this dataset:
```bibtex 
@article{bergmann2019mvtecad,
  title={MVTec AD -- A Comprehensive Real-World Dataset for Unsupervised Anomaly Detection},
  author={Bergmann, Paul and Fauser, Michael and Sattlegger, David and Steger, Carsten},
  journal={CVPR},
  year={2019}
}
 
@misc{batteryweld2025,
  title={Battery-Weld-Anomaly-Detection-Dataset},
  author={LaoGeZi6666},
  howpublished={\url{https://github.com/LaoGeZi6666/Battery-Weld-Anomaly-Detection-Dataset}}, 
  year={2025}
}
