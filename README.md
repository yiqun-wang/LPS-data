# Incompatible Shape Structure Datasets

The incompatible shape structure datasets in the paper ["A Robust Local Spectral Descriptor for Matching Non-Rigid Shapes with Incompatible Shape Structures"](http://openaccess.thecvf.com/content_CVPR_2019/html/Wang_A_Robust_Local_Spectral_Descriptor_for_Matching_Non-Rigid_Shapes_With_CVPR_2019_paper.html) by Yiqun Wang,  Jianwei Guo, Dong-Ming Yan, Kai Wang, Xiaopeng Zhang.

Original Dataset can be found at: http://faust.is.tue.mpg.de/  (FAUST dataset) and we remeshed each shape independently using paper ["Isotropic Surface Remeshing without Large and Small Angles"](https://ieeexplore.ieee.org/document/8361045) to generate multi-resolution models. For 5K resolution, we use the model in https://github.com/llorz/SGA18_orientation_BCICP_dataset.

For each of the dataset, the first 6890 points have an exact correspondence for accurate evaluation.

- faust_all_8000: 8K resolution (100 models)

- faust_all_10000: 10K resolution (100 models)

- faust_all_12000: 12K resolution (100 models)

- faust_all_15000: 15K resolution (100 models)

- faust_all_rot_random: randomly rotated models (100 models)

- faust_all_scale_random: randomly scaled models (100 models with five scaling factors: 0.2, 0.5, 1.0, 2.0, and 4.0.)