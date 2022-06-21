# ml-services-in-healthcare
Development of a companion application to help medical staff in more efficient segmentation of brain tumors and its sub-regions from mri images, including patient survival prediction.
MRI Brain Tumor Segmentation U-Net approach
Problem definiton
Segmentation of tumors in pre-operative MRI scans.

Each pixel on image must be labeled:
- Pixel is part of a tumor area (1 or 2 or 3) can be one of multiple classes or subregions
- Anything else > pixel is not on a tumor region (0)

The subregions of tumor considered for evaluation are:
- The "enhancing tumor" (ET).
- The "tumor core" (TC).
- The "whole tumor" (WT). The provided segmentation labels have values of 1 for CORE, 2 for EDEMA, 4 for ENHANCING TUMOR, and 0 for everything else.
