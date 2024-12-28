# Cracks semantic segmentation datasets
Cracks are the defects formed by cyclic loading, fatigue, shrinkage, creep, and so on. In addition, they represent the deterioration of the structures over some time. Therefore, it is essential to detect and classify them according to the condition grade at the early stages to prevent the collapse of structures. Deep learning and machine learning-based supervised semantic segmentation methods requires carefully annotated images of cracks. This is a repository of human annotated semantic segmentation datasets of concrete, pavement, walls/mixed and masonry/bricks cracks surface. I collected these datasets during my Ph.D. days and used many for my dissertation.

## Datasets examples
<table style="width: 100%; border-collapse: collapse; table-layout: fixed; text-align: left;">
    <thead>
        <tr>
            <th style="width: 2%; word-break: break-word;">No.</th>
            <th style="width: 2%; word-break: break-word;">Dataset Name</th>
            <th style="width: 47%; word-break: break-word;">Cracks Images</th>
            <th style="width: 47%; word-break: break-word;">Ground-Truth Images</th>
            <th style="width: 2%; word-break: break-word;">Remarks</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td><a href="https://1drv.ms/f/c/49b23bc11eecd6a8/EhR2i1qbyhlKn6JmjTVdWQ4BVUcKofT80zNf12E0tDVgCw?e=DYmZzs">Cracks-200</a></td>
            <td><img src="assets/Dataset_1_Cracks-200_crack.png" alt="Crack Image" style="max-width: 100%;"></td>
            <td><img src="assets/Dataset_1_Cracks-200_gt.png" alt="Ground Truth Image" style="max-width: 100%;"></td>
            <td>Concrete surfaces, easy and a low-resolution dataset. I call it Cracks-101 dataset.</td>
        </tr>
        <tr>
            <td>2</td>
            <td><a href="https://1drv.ms/f/c/49b23bc11eecd6a8/ErmWulPITuVDmxcHQZK5bAkBr-FGHSYFI1QWHnjY_YikQA?e=rJUW4W">Cracks-1K (644 x 483)</a></td>
            <td><img src="assets/Dataset_2_Cracks-1K_(644x483)_crack.png" alt="Crack Image" style="max-width: 100%;"></td>
            <td><img src="assets/Dataset_2_Cracks-1K_(644x483)_gt.png" alt="Ground Truth Image" style="max-width: 100%;"></td>
            <td>Concrete and pavement surfaces, quite challenging dataset.</td>
        </tr>
        <tr>
            <td>3</td>
            <td>To be uploaded soon</td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>4</td>
            <td><a href="https://1drv.ms/f/c/49b23bc11eecd6a8/Evcsn2XWDblLv76EDFOwf0cB_V4WbqpRkOoH8YAIh5JfGg?e=fajgSS">Cracks-4K (512 x 512)</a></td>
            <td><img src="assets/Dataset_4_Cracks-4K_(512x512)_crack.png" alt="Crack Image" style="max-width: 100%;"></td>
            <td><img src="assets/Dataset_4_Cracks-4K_(512x512)_gt.png" alt="Ground Truth Image" style="max-width: 100%;"></td>
            <td>Concrete surfaces dataset. It has medium and large-sized cracks. Overall, clean and high-resolution dataset.</td>
        </tr>
        <tr>
            <td>5</td>
            <td><a href="https://1drv.ms/f/c/49b23bc11eecd6a8/Eias7mEICpdOju5slI7_mpwBT-T73E8mAmu6N_vVYXQG8Q?e=dXBKIm">Cracks-1K (1280 x 720)</a></td>
            <td><img src="assets/Dataset_5_Cracks-1K_(1280x720)_crack.png" alt="Crack Image" style="max-width: 100%;"></td>
            <td><img src="assets/Dataset_5_Cracks-1K_(1280x720)_gt.png" alt="Ground Truth Image" style="max-width: 100%;"></td>
            <td>Concrete surfaces dataset. It has some thin, medium, and large-sized cracks. Overall, clean and high-resolution dataset.</td>
        </tr>        
    </tbody>
</table>

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
I thank Shravan Ravi, Vinay Hegde, and Milind Bhat (chronological order) for their efforts in the collection and preparation of the crack and non-crack image database around the University of Southern California (USC) campus at Los Angeles, USA. I thank Dr. Azarang Golmohammadi who web harvested cracks images of concrete, pavment, and walls datasets. In addition, I thank Ryan, Youngseok and Wisepl Private Limited Data (chronological order) for their conscientious efforts in creating for crack semantic segmentation annotations.

# Feedback
Please rate and provide feedback for the further improvements.

