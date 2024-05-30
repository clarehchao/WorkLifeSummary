# Work and Life Summary of Shih-ying (Clare) Chao
- Grew up in Taipei, Taiwan
- Moved to the U.S. in Sophomore year of high school in San Diego, CA
- I really enjoyed Calculus and computer programming classes in high school
- Finished my bachelor degree in Electrical Engineering (University of California, San Diego) with emphasis of image processing
- Completed my PhD in Biomedical Engineering (University of California, Davis) with Dr. John M. Boone (pioneer of the BreastCT imaging system)
- Research Scientist with the nuclear medicine group at UCSF (P.I: Youngho Seo, PhD)

## During my PhD years, I learned a lot ...
My lab was involved with several clinical trials, collecting breast CT images from hundreds of human volunteers
1. With the large amount of breast CT images, I characterized the beast anatomny in many ways including
  - Breast density
  - Cup-size related measurement
  - Skin thickness
  - Distribution of breast glandular tissues
  - More details in [skin thickness paper], [50/50 breast metrics], and [link to chapter 2 of dissertation]
  - **IMPACT**: The breast anatomy characterization helps the breast cancer research immensely by providing a gold standard of breast anatomy in many area of research including image simulation (when designing an imaging system or lack the amount of human imaging data for furthre research), dosimetry estimation and calculation, and image system optimization and designing
2. I optimized a new imaging technique (dual-energy mammography) on the BreastCT system
  - Simulated images by modeling the imaging detector and system setup (mathematically and experimentally characterized the detector of the BreastCT system)
  - Designed and constructed a static and dynamic breast phantom for optimization tasks
  - Conducted a comprehensive optimization considering various imaging system setup and the associated dosimetry
  - [link to chap 3 and 4 of disseration?]
  - **IMPACT**: determined the optimial imaging system setting of dual energy dynamic imaging using the BreastCT systme with imaging dose consideration

## During my time at UCSF as a research scientist, I worked on ...
1. Patient-Specific Monte Carlo Dosimetry Calculation using dynamic I<sup>124<sup> PET/CT Imaging
- Implemented a Monte-Carlo dosimetry calculator using GEANT4 Monte Carlo software and validated the dose metrics with other published dose metrics
- For each patient who went through the clinical trial of I<sup>131<sup>-MIBG targeted radionuclide therapy, dose to and from each organ was computed using the dosimetry calculator and allow physicians to have a sense of dosimetry as they evaluate the treatment effectiveness
- [point to Monte Carlo dose project repo] and [monte carlo tool code]
- [show ANR poster]
- [point to MIBI paper, my published paper]
- **IMPACT**: the estimated dosimetry specific to each patient was helpful to physicians to evaluate the effectiveness of the treatment (look for the doctor's paper..)
2. PET/CT Radiomics
- Gathered and explored PET/CT and MR images of segmented breast tumors in 200+ patients with breast cancer
- Implemented a Python-based tool [point to the repo] to compute 2D and 3D image features of the segmented PET and MR images of the breast tumors
- Determined helpful features to predict breast cancer outcome using simple ML modeling including ....
- [point to PETCTomics repo] and [POSTER??]
- **IMPACT**: determine the power of 2D and 3D image features of the PET and MR images in predicting breast cancer outcome

# A few extra small proof-of-concept projects that I worked on ...
- Proof of concept of a proton-counting SPECT/CT imaging system [IEEE 2015 poster]
- The effect of magnetic field on positron range using Monte Carlo simulations [IEEE 2014 poster]
- Implemented 3D MLEM image reconstruction algorithm using Spark GraphX for faster computationg time
- **IMPACT and SKILLS**:
	- flexible with simple proof-of-concept implementation and experimentation
	- ready to answer a research question using computation and experimenation
	- quick to pick up tools or programing language to implement and conduct a research projects
    

