# SCUT LFMB-MVFV Dataset
This repository is the Large-scale Finger Multi-Biometric database and benchmark for Multi-View Finger Vein (LFMB-MVFV) from paper:   
__Multi-view Finger Vein Recognition using Attention-based MVCNN.   CCBR2022 Oral  
By Weili Yang, Junduan Huang, Zhuoming Chen, Junhong Zhao, and Wenxiong Kang  


## Abstract
Finger vein images are susceptible to finger posture variation and inappropriate lighting due to the contact-less imaging method and the special imaging principle, which can cause the imaging area to shift and the vein texture to vanish. However, the algorithms cannot directly handle these issues because there are no reference images in single-view imaging. To this end, this paper uses three multi-view finger vein imaging methods to capture finger vein image sets for identity recognition, and three multi-view finger vein datasets are constructed for the first time. To efficiently exploit the complementary information in each multi-view image set, we propose VW-MVCNN, an attention-based multi-view neural network that embeds a View-Wise attention module with MVCNN to mine the identity information in each view and dynamically fuse them to improve accuracy. Extensive experiments are performed on the three datasets to validate the superiority of the proposed VW-MVCNN, and the advantages and disadvantages of the three multi-view finger vein imaging methods are discussed. The datasets is released at https://github.com/SCUT-BIP-Lab/LFMB-MVFV.


## SCUT LFMB-MVFV Dataset
**the Large-scale Finger Multi-Biometric database and benchmark for Multi-View Finger Vein (LFMB-MVFV)**
The SCUT LFMB-MVFV Dataset consists of three subset, namely the multi-angle views subset, the multi-finger-rotation views subset, the multi-illumination views subset. Each of the three subsets acquired a kind of multi-view finger vein image set of the same 668 fingers. The multi-angle views subset adopted the multi-angle views imaging method, which capture multiple finger vein images with multiple cameras surrounding the finger. The multi-finger-rotation views subset adopted the multi-finger-rotation views imaging method, which capture image sequences of the finger under longitudinal rotation with a single camera. The multi-illumination views subset adopted the multi-illumination views imaging method, which capture multiple images of the finger under different light intensities with a single camera. And we provide the common finger index in the three subsets, as well as the inter- and intra-class pairs files for the validation and testing sets.

？？？？？？？？？？？？？？？？？？？？？？？？？？？？？？？？？？？？？？？？？
--__common_finger_index__: the finger data in training set.   
--__datasamples__: data samples provided to understand this dataset in detail.  
--__datasamples/LFMB-3DFB_Pictures_Seged_Rectified__: each capture get 6 raw images by the 6 different views of the imaging system, and we rectified and segmented the finger.     
--__datasamples/Deformed_Meshes_cylinder382_textured__: reconstructed 3D holographic finger models with textures with 382 vertices.    
--__datasamples/Deformed_Meshes_cylinder662_textured__: reconstructed 3D holographic finger models with textures with 662 vertices.   
--__datasamples/Deformed_Meshes_cylinder1022_textured__: reconstructed 3D holographic finger models with textures with 1022 vertices.   
--__datasamples/Deformed_Meshes_cylinder2602_textured__: reconstructed 3D holographic finger models with textures with 2602 vertices.   
--__datasamples/Deformed_Meshes_cylinder5543_textured__: reconstructed 3D holographic finger models with textures with 5543 vertices.   
--__datasamples/Deformed_Meshes_cylinder10064_textured__: reconstructed 3D holographic finger models with textures with 10064 vertices.   

## Request
The __SCUT LFMB-MVFV Dataset__ is publicly available(free of charge) to the research community. Unfortunately, due to privacy reasons, we cannot provide the database for commercial use.

We have made part of the dataset available for download in the repo in order to get a detailed view of this data. Those interested in obtaining the whole __SCUT LFMB-MVFV Dataset__ should download [release agreement](https://github.com/SCUT-BIP-Lab/LFMB-3DFB/blob/main/SCUT%20LFMB-3DFB%20Database%20Release%20Agreement.docx??????????????????????？？？？？？？？？？？？？？？？？？?), and send by e-mail one signed and scanned copy to scutbip@outlook.com.


While reporting results using the __SCUT LFMB-MVFV Dataset__, please cite the following article:    

@inproceedings{yang2022MVFV,
  title={Multi-view Finger Vein Recognition using Attention-based MVCNN},
  author={Yang, Weili and Huang, Junduan and Chen, Zhuoming and Zhao, Junhong and Kang, Wenxiong},
  booktitle={2022 Chinese Conference on Biometrics Recognition (CCBR)},
  year={2022}
}




## Contact
Weili Yang   
Biometrics and Intelligence Perception Lab.   
College of Automation Science and Engineering   
South China University of Technology    
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641   
yang.wei.li@aliyun.com 



Prof. Kang Wenxiong   
Biometrics and Intelligence Perception Lab.   
College of Automation Science and Engineering   
South China University of Technology   
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641      
auwxkang@scut.edu.cn   
