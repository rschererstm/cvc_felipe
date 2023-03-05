# cvc_felipe
- Visual Field Pipeline -

This notebook aims to demonstrate my bridge knowledge between Ophthalmology and Computer Vision. The software sample process visual fields. The codes are mere prototypes without clinical validation.



<a href="https://colab.research.google.com/drive/1py6Q5LM_fJkgPG-kciVZ43P_cJTJtMZr?usp=sharing" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


## Dataset
https://github.com/uw-biomedical-ml/uwhvf

## Image Retrieval - Autoencoder
https://github.com/ankonzoid/artificio/tree/master/image_retrieval

## Anomaly Detection - GAN
https://github.com/openvinotoolkit/anomalib

## TRAINED GAN DOWNLOAD MODEL AND REPORTS
https://drive.google.com/drive/folders/1c1gcjQ6Mqg5dLQ8ZyuLXIya8Lwnom7Z2?usp=sharing


## AWS LAMBDA JSON FORMAT (FOR CONVERTER)
Example:
{
  "age":  "23",
  "hvf_r": [[100,   100,   100,    26.34,  23.73,  22.84,  24.19, 100,   100  ], [100,   100,    26.25,  27.22,  25.67,  26.18,  27.01,  26.24, 100 ], [100,    22.2,   28.17,  29.2,   28.44,  27.58,  28.51,  28.02,  25.68], [ 20.4,   27.41,  29.73,  30.02,  30.93,  30.36,  30.64,  21,    27.89], [ 20.45,  25.88,  28.9,   32.17,  31.89,  30.91,  28.8,    0,    27.43], [100,    27.16,  29.98,  32.74,  29.95,  32.07,  29.84,  26.99,  27.3 ], [100,   100,    26.88,  29.43,  29.82,  28.64,  29.81,  28.24, 100  ], [100,   100,   100,    28.88,  27.3,   26.82,  28.18, 100, 100]],
  "hvf_l": [[100,   100,   100,    26.34,  23.73,  22.84,  24.19, 100,   100  ], [100,   100,    26.25,  27.22,  25.67,  26.18,  27.01,  26.24, 100 ], [100,    22.2,   28.17,  29.2,   28.44,  27.58,  28.51,  28.02,  25.68], [ 20.4,   27.41,  29.73,  30.02,  30.93,  30.36,  30.64,  21,    27.89], [ 20.45,  25.88,  28.9,   32.17,  31.89,  30.91,  28.8,    0,    27.43], [100,    27.16,  29.98,  32.74,  29.95,  32.07,  29.84,  26.99,  27.3 ], [100,   100,    26.88,  29.43,  29.82,  28.64,  29.81,  28.24, 100  ], [100,   100,   100,    28.88,  27.3,   26.82,  28.18, 100, 100]],
  "td_r": [[100,   100,   100,    26.34,  23.73,  22.84,  24.19, 100,   100  ], [100,   100,    26.25,  27.22,  25.67,  26.18,  27.01,  26.24, 100 ], [100,    22.2,   28.17,  29.2,   28.44,  27.58,  28.51,  28.02,  25.68], [ 20.4,   27.41,  29.73,  30.02,  30.93,  30.36,  30.64,  21,    27.89], [ 20.45,  25.88,  28.9,   32.17,  31.89,  30.91,  28.8,    0,    27.43], [100,    27.16,  29.98,  32.74,  29.95,  32.07,  29.84,  26.99,  27.3 ], [100,   100,    26.88,  29.43,  29.82,  28.64,  29.81,  28.24, 100  ], [100,   100,   100,    28.88,  27.3,   26.82,  28.18, 100, 100]],
  "td_l": [[100,   100,   100,    26.34,  23.73,  22.84,  24.19, 100,   100  ], [100,   100,    26.25,  27.22,  25.67,  26.18,  27.01,  26.24, 100 ], [100,    22.2,   28.17,  29.2,   28.44,  27.58,  28.51,  28.02,  25.68], [ 20.4,   27.41,  29.73,  30.02,  30.93,  30.36,  30.64,  21,    27.89], [ 20.45,  25.88,  28.9,   32.17,  31.89,  30.91,  28.8,    0,    27.43], [100,    27.16,  29.98,  32.74,  29.95,  32.07,  29.84,  26.99,  27.3 ], [100,   100,    26.88,  29.43,  29.82,  28.64,  29.81,  28.24, 100  ], [100,   100,   100,    28.88,  27.3,   26.82,  28.18, 100, 100]]
}


# Reference

If you use this library and like it, use this to cite it

```tex
@misc{cvc_felipe,
      title={CVC: A Notebook for Analyze Visual Fields},
      author={Rafael Scherer},
      year={2023}
}
```
