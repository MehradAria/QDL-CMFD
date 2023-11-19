# QDL-CMFD
## A Quality-independent and Deep Learning-based Copy-Move Image Forgery Detection method.

One of the prevalent methods of image forgery is copy-move, where one or more regions of an image are duplicated and moved elsewhere in the image. It is usually challenging to detect this type of forgery due to the similarity of the copied and forged areas. Also, forgers perform pre-processing and/or post-processing operations on the manipulated areas to make it even more difficult to detect. This study presents an image quality-independent method based on a deep learning approach, termed QDL-CMFD, for detecting this type of forgery. QDL-CMFD utilizes generative adversarial networks for image quality enhancement, and convolutional neural networks (CNN) for forgery detection. A tailored dual-branch CNN architecture is introduced consisting of two subnetworks, namely a manipulation detection subnetwork and a similarity detection subnetwork. Accordingly, unlike most existing methods, QDL-CMFD is able to simultaneously detect several forged areas, as well as determine the source and target of the forgery. Also, QDL-CMFD is robust against various pre-processing/post-processing attacks. It shows excellent performance for detecting low-quality forged images and small areas. Experiments on the `CASIA` and `CoMoFoD` benchmark datasets confirm that QDL-CMFD performs significantly better than the competitors.

## QDL-CMFD architecture
![QDL-CMFD Approach](https://raw.githubusercontent.com/MehradAria/SR-DCMFD/main/Method.jpg)

## Train/Inference
You may use [QDL-CMFD.ipynb](https://github.com/MehradAria/QDL-CMFD/blob/main/QDL-CMFD.ipynb), inference is as simple as:

```shell
# Example
pred = QDLCMFD_decoder(model, image)
```

---
### Data / Pre-trained model availability:
- Model/Data is not publicly available at this moment.

---
### Condition and terms to use any sources of this project (Codes, Datasets, etc.):

1) Please cite the following paper:
```
Aria M, Hashemzadeh M, Farajzadeh N.
“QDL-CMFD: a Quality-independent and Deep Learning-based Copy-Move image Forgery Detection method”.
Neurocomputing. 2022; 511:213-36.
DOI: [10.1016/j.neucom.2022.09.017](https://doi.org/10.1016/j.neucom.2022.09.017)
```

2) Please do not distribute the database or source codes to others without author authorization.
Authors’ Email: `mehrad.aria[at]shirazu.ac.ir` (M. Aria).
