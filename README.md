# GI tract polyp segmentation using 2d Inverseform loss
The goal of the project is to develop a computer-aided detection and diagnosis system for automatic polyp segmentation and detection.
## Dataset 
We have used publicly available Kavsir seg dataset for this task (https://datasets.simula.no/kvasir-seg/). It consists of total 1000 images of endoscopy and colonoscopy along with the 2d segmented mask.
## Inverseform loss
This is a boundary aware loss. We have utilized this idea from the CVPR paper (https://openaccess.thecvf.com/content/CVPR2021/papers/Borse_InverseForm_A_Loss_Function_for_Structured_Boundary-Aware_Segmentation_CVPR_2021_paper.pdf) and used for the medical images.
