# Battery-Weld-Anomaly-Detection-Dataset 
![License](https://img.shields.io/badge/License-CC_BY--SA_4.0-green)  ![Updated](https://img.shields.io/badge/Last_Update-2025--03--25-blue) 
 
A comprehensive industrial anomaly detection dataset for battery welding processes, structured in [MVTec Anomaly Detection (MVTecAD)](https://www.mvtec.com/company/research/datasets/mvtec-ad)  format. Suitable for unsupervised/semi-supervised anomaly detection research.
 
## Dataset Structure 
Battery-Weld-Anomaly-Detection-Dataset/ 
    └── train           // 帮助文档
    │       └── good
    │           └── .png
    
    ├── test    // 
    │       ├── good
    │           ├── .png
    │       ├── defective
    │           ├── .png
    
    ├── ground_truth             // DDS核心文件库，包含各版本的include、src、lib文件夹，方便合并
    │       ├── defective
    │           ├── .png
    
    │   ├── include_src     // 包含各版本的include、src文件夹
    
    │       ├── V1.0
    
    │           ├── include
    
    │           └── src
    
    │       └── V......
    
    │   └── lib             // 包含各版本的lib文件夹
    
    │       ├── arm64       // 支持arm64系统版本的lib文件夹
    
    │           ├── V1.0
    
    │           └── V......
    
    │       └── x86         // 支持x86系统版本的lib文件夹
    
    │           ├── V1.0
    
    │           └── V......
    
    ├── target              // 合成结果存放的文件夹
    
    └── temp                // 存放待合并的服务的服务文件夹
 
