# bioimage1s: A Benchmark Dataset for One-Shot Classification with Biomedical Imaging

## Contents

This dataset contains eight folders of biomedical images, each representing a specific task. Within each folder:

The "testing" folder contains subfolders of testing images, each labeled by different categories.

The "training" folder holds training images intended for use in conventional deep learning methods. This folder has two subfolders, "homogeneous" and "heterogeneous," indicating whether the training images are homogeneous or heterogeneous in relation to the testing images. Sub-subfolders within these contain images with various labels.

The "referencearray" folder provides reference arrays of training images intended for large language/multimodal models. The images here are the same as those in the "training" folder.

## Tasks

The dataset tasks are as follows:

GBM_histology: Histology images from individuals with or without glioblastoma (GBM).

brain_MRI: MRI images from individuals with or without brain tumors.

cell_states: DAPI-stained images from normal and senescent cells.

cell_types: Microscopy images of two cell lines: BV2 and SHSY5Y.

chest_CT: Chest CT images from individuals with or without lung cancer.

retina_OCT: Retina OCT images from individuals with or without diabetic macular edema (DME).

three_tissues: H&E-stained images of three tissue types: artery, tibial nerve, and adipose.

two_tissues: H&E-stained images of two tissue types: artery and tibial nerve.

