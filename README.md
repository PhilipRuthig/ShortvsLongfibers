# Human short association fibers are thinner and less myelinated than long fibers
![Visualization of raw, predicted and final segmentation](https://i.imgur.com/hX9HMJN.jpeg)

This is a collection of all the scripts used to generate Figures in Ruthig, Edler v.d. Planitz et al (in prep). 

`CC` and `SWM` each contain a copy of the complete segmentation pipeline, from raw data to final segmentation of the images. Also included is a validation step for CC and SWM data each, which generates all supplementary data related to validations (Fig. S2-S6). Due to data size limitations, we only include image data of a a sample image each to visualize the process. The text-based (.csv) data of all images are included in the `3_postprocessed` folder in the files `all_results_CC_anonymized.csv` and `all_results_SWM_anonymized.csv`.

`fig1.ipynb` creates Figure 1 from images at different steps of the pipeline.

`mcmc_CCvsSWM_GEV.ipynb` performs the MCMC modeling and plots all main figures, including supplementary figures S7, S8, and S9. The modeling part requires an installation of PyMC3.

`pymc_env.yml` contains the conda environment required to run the MCMC sampling.

Please find more comprehensive information in the related paper (in prep.)
