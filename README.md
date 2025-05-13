# Human short association fibers are thinner and less myelinated than long fibers
![Visualization of raw, predicted and final segmentation](https://i.imgur.com/hX9HMJN.jpeg)

This is a collection of all scripts, sample data, and other information used to generate the figures in Ruthig, Edler v.d. Planitz et al ([currently in preprint](https://www.biorxiv.org/content/10.1101/2024.10.21.619354v1)). 

`CC` and `SWM` each contain a copy of the complete segmentation pipeline, from raw data to final segmentation of the images. Also included is a validation step for CC and SWM data each, which generates all supplementary data related to validations (Fig. S1-S5). Due to data size limitations, we only include image data of a a sample image each to visualize the process. The text-based (.csv) data of all images are included in each `3_postprocessed` folder in the files `CC/3_postprocessed/CC_anonymized.csv`, `SWM_orthogonal_anonymized.csv` and `SWM_parallel_anonymized.csv`. Additional information regarding the pipeline can be found at https://github.com/PhilipRuthig/EMtools.

`fig2.ipynb` creates Figure 2 from images at different steps of the analysis pipeline.

`mcmc_CCvsSWM_GEV.ipynb` performs the MCMC modeling and plots all main figures, including parts for Fig S6 and S7, S8, and S9, S10, S11, S12. The modeling part requires an installation of PyMC3.

`pymc_env.yml` contains the conda environment required to run the MCMC sampling.

`options.json` contains all relevant information for the training of a DenseNet analogous to the one used in the study using Uni-EM (Urakubo et al., 2019)

Please find more comprehensive information in the related paper:

https://www.biorxiv.org/content/10.1101/2024.10.21.619354v1
