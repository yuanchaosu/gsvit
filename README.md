# GSViT: A Generative Self-Aware Vision Transformer for Hyperspectral Image Unmixing

**Note:** GSViT codes are intended for academic communication only and may not be used commercially.

## Architectures and Systems
* GSViT can run under X86 and ARM architectures.\
* Two demos were made for synthetic data and real data, respectively.\
#
├── Readme. md\
├── Environment: Python 3.9 and PyTorch 2.0 + cuDNN 11.8\
├── Demo\
│   ├── demo_synthetic_data.py\
│   └── demo_real_data.py\
│── Main Codes                      
│   ├── GSViT.py # Framework of SEViT\
│   ├── gsvit_emb.py                  
│   └── gsvit_tnt.py\
├── Auxiliary Codes                      
│   ├── utils.py\
│   ├── dataPro.py  
│   ├── plots.py\
│   └── vca.py\
├── Test data: real and synthetic data sets.\
│   ├── data_real/real.mat (Real data)\
│   └── synthetic_data.py\
│         ├── USGS_Library (Endmembers are given by randomly selecting library spectra.)\
│         └── data_synthetic/synthetic.mat (Synthetic data)\
└── Results files

## Specification
* 'synthetic_data' is a data generator that can generate different data sets by setting endmembers, 
window size, and SNR.
* For our synthetic_data, its size, purity, and SNR are adjustable for users' needs.
* 'demo_synthetic_data.py' uses synthetic hyperspectral data.
* 'demo_real_data.py' uses challenging real hyperspectral data.

## Authors
- Yuanchao Su (suych3@xust.edu.cn)
- Lianru Gao (gaolr@aircas.ac.cn)
- Mengying Jiang
- Antonio Plaza  
- Xu Sun 
- Bing Zhang 

## Date
Jan. 2024
