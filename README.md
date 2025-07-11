# Cracks semantic segmentation datasets
Cracks are the defects formed by cyclic loading, fatigue, shrinkage, creep, and so on. In addition, they represent the deterioration of the structures over some time. Therefore, it is essential to detect and classify them according to the condition grade at the early stages to prevent the collapse of structures. Deep learning and machine learning-based supervised semantic segmentation methods requires carefully annotated images of cracks. This is a repository of human annotated semantic segmentation datasets of concrete, pavement, walls/mixed and masonry/bricks cracks surface. I collected these datasets during my Ph.D. days and used many for my dissertation.

## Datasets examples
| No. | Dataset name | Cracks images                                    | Ground-truth images                              | Remarks |
|:--|:---|:------------------------------------------------|:------------------------------------------------|:--------|
| 1   | [Cracks-200](https://1drv.ms/f/c/49b23bc11eecd6a8/EhR2i1qbyhlKn6JmjTVdWQ4BVUcKofT80zNf12E0tDVgCw?e=DYmZzs) | ![](assets/Dataset_1_Cracks-200_crack.png)      | ![](assets/Dataset_1_Cracks-200_gt.png)        | Concrete surfaces, I won't say easy but still naive looking images of cracks and a low-resolution dataset. Low in the textural details. I call it Cracks-101 dataset.                                |
| 2   | [Cracks-1K (644 x 483)](https://1drv.ms/f/c/49b23bc11eecd6a8/ErmWulPITuVDmxcHQZK5bAkBr-FGHSYFI1QWHnjY_YikQA?e=rJUW4W) | ![](assets/Dataset_2_Cracks-1K_(644x483)_crack.png) | ![](assets/Dataset_2_Cracks-1K_(644x483)_gt.png) | Concrete and pavement surfaces, quite challenging dataset. It has cracks of thin, medium and thick varieties. This dataset is texturous and some pavement cracks are filled with debris and may not be darker in constrast compared to the background. Some pavement cracks have lighter shades.                                                 |
| 3   | [Cracks-676](https://1drv.ms/f/c/49b23bc11eecd6a8/EkGakDQpmLxApktxFMy8paoBYLkyBfs9guAgCvJGCa_Kig?e=Abayh0) | ![](assets/Dataset_3_Cracks-676_crack.png) | ![](assets/Dataset_3_Cracks-676_gt.png) | Concrete, wall and pavement surfaces, quite challenging dataset. It has cracks of thin, medium and thick varieties. Highly textureous and cracks width varies largely. I call this dataset as ***The Wild Wild West*** because of its diversity and different images size.                                                 |
| 4   | [Cracks-4K (512 x 512)](https://1drv.ms/f/c/49b23bc11eecd6a8/Evcsn2XWDblLv76EDFOwf0cB_V4WbqpRkOoH8YAIh5JfGg?e=fajgSS) | ![](assets/Dataset_4_Cracks-4K_(512x512)_crack.png) | ![](assets/Dataset_4_Cracks-4K_(512x512)_gt.png) | Concrete surfaces dataset. It has medium and large-sized cracks. Overall, clean and high-resolution dataset.       |
| 5   | [Cracks-1K (1280 x 720)](https://1drv.ms/f/c/49b23bc11eecd6a8/Eias7mEICpdOju5slI7_mpwBT-T73E8mAmu6N_vVYXQG8Q?e=dXBKIm) | ![](assets/Dataset_5_Cracks-1K_(1280x720)_crack.png) | ![](assets/Dataset_5_Cracks-1K_(1280x720)_gt.png) | Concrete surfaces dataset. It has some thin, medium, and large-sized cracks. Overall, clean and high-resolution dataset. |
| 6   | [Cracks-1K (448 x 252)](https://1drv.ms/f/c/49b23bc11eecd6a8/EgXYLiqrSNdKtzWPbJp3mQQBZN-xlivQHVCfzq8jxA-jkQ?e=8xqBD2) | ![](assets/Dataset_6_Cracks-1K_(448x252)_crack.png) | ![](assets/Dataset_6_Cracks-1K_(448x252)_gt.png) | Concrete surfaces dataset. It has thin, medium, and large-sized cracks. Same as Cracks-1K (1280 x 720), but with a different resolution manageable for Deep Learning and Machine Learning methods. Overall, clean and high-resolution dataset. |
| 7   | [Cracks-3K (512 x 512)](https://1drv.ms/f/c/49b23bc11eecd6a8/Ep-RtzHUbtxGpHH1HtczmZsBbWHFnFdKwp2X5CmHMO2Ipw?e=KjV3UH) | ![](assets/Dataset_7_Cracks-3K_(512x512)_crack.png) | ![](assets/Dataset_7_Cracks-3K_(512x512)_gt.png) | Concrete and pavement surfaces. It has thin, medium, and large-sized cracks. It has shadows in the middle. Overall, the most texture-diverse and challenging dataset. |
| 8   | [Masonry-Brick Cracks 81 (5152x3864)](https://1drv.ms/f/c/49b23bc11eecd6a8/Ek_azWXTJltNrWi4vqGy-XMBuNUFhzqxON5c1U3qXBTwNA?e=CYdtxs) | ![](assets/Dataset_8_Masonry-Brick_Cracks_81_(5152x3864)_crack.png) | ![](assets/Dataset_8_Masonry-Brick_Cracks_81_(5152x3864)_gt.png) | Masonry, bricks, and concrete joints dataset. Includes thin, medium, and large-sized cracks. Clean and very high resolution. Use [Cracks cropper algorithm](https://github.com/preethamam/CracksSplitterCropper-Dataset) to split large resolution images for Deep Learning and Machine Learning methods. |

# Citation
All cracks semantic segmentation datasets are available to the public. If you use any of these datasets in your research, please use the following BibTeX entry to cite:
```bibtex
@PhdThesis{preetham2021vision,
author = {{Aghalaya Manjunatha}, Preetham},
title = {Vision-Based and Data-Driven Analytical and Experimental Studies into Condition Assessment and Change Detection of Evolving Civil, Mechanical and Aerospace Infrastructures},
school =  {University of Southern California},
year = 2021,
type = {Dissertations & Theses},
address = {3550 Trousdale Parkway Los Angeles, CA 90089},
month = {December},
note = {Condition assessment, Crack localization, Crack change detection, Synthetic crack generation, Sewer pipe condition assessment, Mechanical systems defect detection and quantification}
}
```

# Acknowledgements
I thank Shravan Ravi, Vinay Hegde, and Milind Bhat (chronological order) for their efforts in the collection and preparation of the crack and non-crack image database around the University of Southern California (USC) campus at Los Angeles, USA. I thank Professor Mohammad Reza Jahanshahi for providing the Cracks-200 raw crack and non-crack images dataset. I thank Dr. Azarang Golmohammadi who web harvested cracks images of concrete, pavement, and walls in [Cracks-676](https://1drv.ms/f/c/49b23bc11eecd6a8/EkGakDQpmLxApktxFMy8paoBYLkyBfs9guAgCvJGCa_Kig?e=Abayh0) dataset. In addition, I thank Ryan, Youngseok, Wisepl Private Limited, Zhenghao Li, and Arjun Sridhar (chronological order) for their conscientious efforts in creating for crack semantic segmentation annotations.

# Feedback
Please rate and provide feedback for the further improvements.

