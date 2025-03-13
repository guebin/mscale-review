# Exploring Multiscale Methods: Reviews and Insights

## Overview

This repository contains the code and implementations used in the research paper Exploring Multiscale Methods: Reviews and Insights. The study focuses on reviewing and analyzing various multiscale methods applied in different domains, providing insights into their theoretical foundations and practical applications.

## Files
- `Sec2-FT1.ipynb` - Fourier Transform
- `Sec2-STFT1.ipynb` & `Sec2-STFT2.ipynb` - Short-Time Fourier Transform
- `Sec2-WT1.ipynb` & `Sec2-WT2.ipynb` - Wavelet Transform
- `Sec3-EMD1.ipynb`, `Sec3-EMD2.ipynb`, `Sec3-EMD3.ipynb` - Empirical Mode Decomposition
- `Sec3-EBT1.ipynb`, `Sec3-EBT2.ipynb` - Elastic-band Transform
- `Sec3-Sizer1.ipynb` - SiZer
- `Sec3-TPT1.ipynb`, `Sec3-TPT2.ipynb`, `Sec3-TPT3.ipynb` - Thick-pen Transform

## Environment
All dependencies required for running the notebooks are listed in `environment.yml`. To recreate the environment, use the following command:

```bash
conda env create -f environment.yml
```

After installation, activate the environment:

```bash
conda activate <environment_name>
```

## Citation
If you use this code in your research, please cite:

```
@article{your_reference,
  title={Exploring Multiscale Methods: Reviews and Insights},
  author={Your Name},
  journal={TBD},
  year={2025}
}
```

## Contact
For any questions regarding the code or implementation, please contact [guebin@jbnu.ac.kr].
