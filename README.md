﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿#   Dynamic Neural Orthogonal Mapping for Fault Detection***- File "Comparison\_DPCA\_DKPCA\_DNOM.m" can be run directly to get the results of DPCA, DKPCA and DNOM in Figure 1- Please note that the data used by code "Comparison\_DPCA\_DKPCA\_DNOM.m" are randomly generated every time, so the results may be slightly different from Figure 1. But only slightly.- The Matlab version we used is R2017b. We did not tested code on Matlab of other version.- File "Comparison\_DPCA\_DKPCA\_DNOM.m" needs KPCA code which can be found in [the Github link of Deng Cai](https://github.com/dengcai78/MatlabFunc/tree/master/SubspaceLearning)- For the GPU acceleration and fast computation, the python codes is developed with the package PyTorch. Please install  the required python libraries before running the python codes-  File "dnom.py" is designed for performing DNOM on TE data*** ####  Please install the following python libraries before running the code "dnom.py"- python==3.52- numpy==1.13.3- PyTorch==0.20- scikit-learn==0.19.0For the GPU acceleration with PyTorch, please refer to [PyTorch](http://pytorch.org/)#### RunOn linux:- python3 dnom.py