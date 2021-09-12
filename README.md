# QDL-CMFD
## QDL-CMFD: a Quality-independent and Deep Learning-based Copy-Move image Forgery Detection method.

One of the most common methods of image forgery is copy-move, in which one or more regions of an image are duplicated and moved elsewhere in the same image. It is usually difficult to detect this type of forgery due to the similarity of the copied and forged areas. Also, forgers usually perform pre-processing and/or post-processing operations on the manipulated areas to make it even more difficult to detect. In this study, an efficient and image quality-independent approach based on deep learning technology, termed QDL-CMFD, is presented for detecting copy-move image forgery. QDL-CMFD utilizes generative adversarial networks (GANs) for image super-resolution enhancement, and convolutional neural networks (CNNs) for feature extraction in the process of forgery detection, which is rarely considered in this field. The architecture of neural networks used in QDL-CMFD is designed taking into account the specific characteristics and constraints of the target application. Due to the low number of learning parameters in the proposed model, the common computational complexity problem in this field is efficiently solved, so that the forgery detection on images of conventional size is performed in real time. Also, unlike most existing methods, QDL-CMFD is robust against different types of known pre-processing and post-processing attacks. In addition, it is able to detect the source and target of the forgery, as well as simultaneous detection of several forged areas, and also shows excellent performance for detecting low-quality forged images and small areas. Experiments conducted on the CASIA and CoMoFoD benchmark datasets confirm that QDL-CMFD performs significantly better than competitors.

![QDL-CMFD Approach](https://raw.githubusercontent.com/MehradAria/SR-DCMFD/main/Method.jpg)

### Citation
    Aria M, Hashemzadeh M. 
    "QDL-CMFD: a Quality-independent and Deep Learning-based Copy-Move image Forgery Detection method" 
    XXX
    URL: X
    DOI: X
