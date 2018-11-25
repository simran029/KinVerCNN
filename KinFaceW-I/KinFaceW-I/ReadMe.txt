KinFaceW-I Dataset

Overview:


The KinFaceW-I Dataset contains the parents-children images used in the paper "Neighborhood Repulsed Metric Learning for Kinship Verification" (CVPR 2012) by Jiwen Lu, Junlin Hu, Xiuzhuang Zhou, Yuanyuan Shang, Yap-Peng Tan and Gang Wang.

There are four kinship relations in the KinFaceW-I dataset: Father-Son (FS), Father-Daughter (FD), Mother-Son (MS), and Mother-Daughter (MD). In the KinFaceW-I dataset, there are 156, 134, 116, and 127 pairs of kinship images for these four relations.

And there are four folders: father-dau, father-son, mother-dau and mother-son, representing four different kinship relations: Father-Daughter (FD), Father-Son (FS), Mother-Daughter (MD), and Mother-Son (MS). The file name in the father-dau folder is fd_xxx_a, here xxx indicates the xxxth person, a=1 indicates the parent, and a=2 indicates the child.  

For ease of use, we manually label the coordinates of the eyes position of each face image, and cropped and aligned facial region into 64x64.




Meta data:

For each relation, we split images as 5-fold, four folds are used for traing model and other one for testing, and the mean of these five folds is recorded as the final result. 

In meta_data folder, the structure of the *.mat file is as follows:
fold   kin/non-kin   image1   image2

For KinFaceW-I dataset, file 'fs_pairs.mat' contains 156 positive pairs and 156 negative pairs of images, and there are about 27 positive and 27 negative pairs for each fold (indeed, the fifth fold contains 26 positive and 26 negative pairs). Similar case to other relations.


