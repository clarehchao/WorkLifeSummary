![](linked_files/What_I_think_about.jpg)

# Work and Life Summary of Shih-ying (Clare) Chao
- Born in Taipei, Taiwan
- Growing up, I was always drawing friends and families to gift them greeting cards and often thought about things to draw or create
- Moved to the U.S. at age of 16-year-old (10th grade in high school) in San Diego, CA
- I really enjoyed Calculus and computer programming classes in high school
- Finished my bachelor degree in Electrical Engineering (University of California, San Diego) with emphasis of image processing
- Completed my PhD in Biomedical Engineering (University of California, Davis) with [Dr. John M. Boone](https://bme.ucdavis.edu/people/john-boone)
- Research Scientist with the nuclear medicine group at UCSF lead by [Dr. Youngho Seo](https://radiology.ucsf.edu/people/youngho-seo)

## During my PhD years
My lab was involved with several clinical trials, collecting breast CT images from hundreds of human volunteers
1. **With the large amount of breast CT images, I characterized the beast anatomy in many ways including**
  - Breast density
  - Cup-size related measurement
  - Skin thickness
  - Distribution of breast glandular tissues
  - See more details in [Skin Thickness using Breast CT Images](https://www.dropbox.com/scl/fi/mxlqm1fl692f389lag5xy/SkinTMammoDose_2008_Huang.pdf?rlkey=r2e40p22vpfls18p20161te87&st=32uqsauz&dl=0), [Breast Anatomical Metrics Using Breast CT Images]([./linked_files/Publications/BreastMetrics_2011_Huang.pdf](https://www.dropbox.com/scl/fi/mlpugzwewopv08n9ueg9k/BreastMetrics_2011_Huang.pdf?rlkey=u4gf6yeb4jcbwgghp9pwl0fut&st=lt5rg2we&dl=0)), and [Chapter 2 of my PhD dissertation](https://www.dropbox.com/scl/fi/0nfeebra9kj08jbzaqfwz/Disseration_UCstyleClass_SHuang.pdf?rlkey=fv5asruxf1hpnqwim5t36c3ez&st=sr7rlmah&dl=0)
  - **IMPACT**: The breast anatomy characterization helps the breast cancer research immensely by providing a gold standard of breast anatomy in many area of research including image simulation (when designing an imaging system or lack the amount of human imaging data for further research), dosimetry estimation and calculation, and image system optimization and designing
2. **I optimized a new imaging technique (dual-energy mammography) on the BreastCT system**
  - Simulated images by modeling the imaging detector and system setup (mathematically and experimentally characterized the detector of the BreastCT system)
  - Designed and constructed a static and dynamic breast phantom for optimization tasks
  - Conducted a comprehensive optimization considering various imaging system setup and the associated dosimetry
  - See details in [Chapter 3 and 4 of my PhD dissertation](https://www.dropbox.com/scl/fi/0nfeebra9kj08jbzaqfwz/Disseration_UCstyleClass_SHuang.pdf?rlkey=fv5asruxf1hpnqwim5t36c3ez&st=sr7rlmah&dl=0)
  - **IMPACT**: Determined the optimal imaging system setting of dual energy dynamic imaging using the BreastCT system with imaging dose consideration
3. A list of **Oral Presentations**:
   - “A Multi-Dimensional Description of Breast Anatomy Using Breast CT” The American Association of Physicists in Medicine (AAPM), Vancouver, Canada, July 2011 
   - “The Characterization of Iodinated-Contrast Kinetics Using a Dynamic Breast Phantom”, AAPM, Anaheim, California, July 2009 
   - “Simulation and Phantom Studies of Contrast-Enhanced Dual Energy Mammography (CEDEM)” International Worship of Digital Mammography (IWDM), Tucson, Arizona, July 2008 
   - “A Phantom Study of Contrast-Enhanced Dual Energy Mammography (CEDEM)” AAPM, Minneapolis, Minnesota, July 2007 
   - “Computational Evaluation of Breast Geometry from Breast CT” AAPM, Orland, Florida, July 2006
## During my time as a Research Scientist at UCSF
1. **Patient-Specific Monte Carlo Dosimetry Calculation using dynamic I<sup>124</sup> PET/CT Imaging**
   - Implemented a Monte-Carlo dosimetry calculator using GEANT4 Monte Carlo software and validated the dose metrics with other published dose metrics
   - For each patient who went through the clinical trial of I<sup>131</sup>-MIBG targeted radionuclide therapy, dose to and from each organ was computed using [the dosimetry calculator on Github](https://github.com/clarehchao/ImageBasedDosimetryTool?tab=readme-ov-file) and allow physicians to have a sense of dosimetry as they evaluate the treatment effectiveness
   - See [the poster](https://www.dropbox.com/scl/fi/5xtluwyhp6ubhasct82bo/I131MIBG_CologneANR2014_Huang.jpg?rlkey=5dbiakltw5zabmpac17r59cds&st=n6vvlduu&dl=0) presented at [Advances in Neuroblastoma Research Association, 2014, Cologne, Germany](https://www.anrmeeting.org/meetings-2014.php)
   - See details in [Patient-Specific Dosimetry Using Pretherapy [<sup>124</sup>I]m-iodobenzylguanidine([<sup>124</sup>I]mIBG) Dynamic PET/CT Imaging Before [<sup>131</sup>I]mIBG Targeted Radionuclide Therapy for Neuroblastoma](https://www.dropbox.com/scl/fi/df486p3vw5ycv1w585111/I124MIBG_MIBJournalPublicationPrint_MIB_SHuang.pdf?rlkey=avewd6hutwxalcagufqwgnvcv&st=ss7htr66&dl=0)
   - **IMPACT**: The estimated dosimetry specific to each patient was helpful to physicians to evaluate the effectiveness of the treatment (look for the doctor's paper..)
2. **Radiomics Using PET/CT and MR Images of Breast Cancer Patients**
   - Gathered and explored PET/CT and MR images of segmented breast tumors in 200+ patients with breast cancer
   - Implemented a Python-based tool to compute 2D and 3D image features of the segmented PET and MR images of the breast tumors
   - Determined helpful features to predict breast cancer outcome using machine learning models
   - Check out [the PETCTomics project on Github](https://github.com/clarehchao/PETCTomics) for code and jupyter notebooks
   - See [the PETCTomics poster](https://www.dropbox.com/scl/fi/38qhln0c3welwwxo59pmx/PETMRIRadiomics_IEEE_2017_Huang_42inch_46inch_v5_Poster.pdf?rlkey=qaiokcoeq7z341wxs43eha9gt&st=vqj6obz4&dl=0) presented at IEEE Nuclear Science Symposium and Medical Imaging Conference, October 2017
   - More details in [Exploration of PET and MRI radiomic features for decoding breast cancer phenotypes and prognosis](https://www.dropbox.com/scl/fi/f8omxjvddv5lzdjmkfy1z/PETCTomics_NPJ_SHuang.pdf?rlkey=r4nu7pay205cosxh0c7qb7hft&st=n9b21kdt&dl=0)
   - **IMPACT**: determine the power of 2D and 3D image features of the PET and MR images in predicting breast cancer outcome
3. A list of **Oral Presentations**:
   - “A GEANT4-Based Internal Dosimetry Tool of <sup>131</sup>I-metaiodobenzylguanidine (MIBG) Targeted Radionuclide Therapy for Neuroblastoma” Society of Nuclear Medicine and Molecular Imaging Annual Meeting, Vancouver, BC, Canada, June 2013 
   - “Geant4-based Patient-Specific Internal Dosimetry of <sup>131</sup>I-Metaiodobenzylguanidine (MIBG) Targeted Radionuclide Therapy (TRT) using <sup>124</sup>I-MIBG PET/CT for Neuroblastoma” 2nd Geant4 Australian School and Monte Carlo Workshop, Wollongong, New South Whales, Australia, April 2013 
   - “Radiation Dosimetry in Medical Imaging” Guest lecture for UCSF Masters of Science in Biomedical Imaging Program, San Francisco, California, Fall 2012 & 2013

# A few proof-of-concept projects that I worked on
- Proof of concept of a proton-counting SPECT/CT imaging system, collaborated with Dxray, Inc. and [the poster presentation at IEEE Nuclear Science Symposium and Medical Imaging Conference, November 2012](https://www.dropbox.com/scl/fi/31eeqy1u73wa5f45gc1a6/DxRayEnergySpectrum_IEEE_33x54inch_Huang_flatten_Poster.pdf?rlkey=dez683z21gb4nu3sdc1xlr4ju&st=q1pvitg2&dl=0)
- [The effect of magnetic field on positron range using Monte Carlo simulations on Github](https://github.com/clarehchao/MagneticFieldEffectOnPositronRange) and [the poster presentation at IEEE Nuclear Science Symposium and Medical Imaging Conference, November 2014](https://www.dropbox.com/scl/fi/els0rwhxzery4585nqg9q/MagFieldPositronRange_Huang_42x70_4_Poster.pdf?rlkey=zddwf8tu6gn2g47ryayqd70tw&st=gk8ea3u5&dl=0)
- [3D MLEM image reconstruction algorithm using Spark GraphX for faster computation time on Github](https://github.com/clarehchao/Spark3DImageReconstruction) and [the poster presentation at Fully3D conference, 2015](https://www.dropbox.com/scl/fi/9yviih3lq1wj9d061sje4/MLEM_SparkGraphX_Poster_SHuang.pdf?rlkey=mmyrg16c777bugrx0s4tw9hp4&st=93rzk842&dl=0)
- **IMPACT and SKILLS**:
	- Flexible with simple proof-of-concept implementation and experimentation
	- Quick to learn necessary computation tools and design experiments to answer research questions
    - Act as a consultant and liaison working with start-up companies and vendors to develop proof-of-concept ideas to products and provide recommendations for added features to existing products

## When I became a mom of 2 boys, I took some time to slow down and works on things when I can
- Involved in a local co-op teaching preschool kids about bible, the alphabet, counting, and fun games/crafts (lesson planning and teach at an age-appropriate manner)
- Started illustrating more during my free time using [Procreate on an IPAD](https://procreate.com/) making greeting cards and children's books ([My Etsy shop](https://thecraftyslug.etsy.com) and [My illustration portfolio](https://www.behance.net/shihyingclarechao)).
- Realize my love of creating and finding ways to communicate a concept or idea using visualization, whether it's illustration or explore data to create a visualization best fit for effective communication of findings
- If not thinking about drawing fuzzy and cute animals or being out in the nature, I worked on [a recent project on data visualization using Python Plotly](https://github.com/clarehchao/DataVisualization) as I learn how to visualize and present data more effectively and intentionally.
