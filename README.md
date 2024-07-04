# ShortvsLongfibers
![Visualization of raw, predicted and final segmentation](https://i.imgur.com/hX9HMJN.jpeg)

This is a collection of all the scripts used to generate Figures in Ruthig, Edler v.d. Planitz et al (in prep). 

'CC' and 'SWM' each contain a copy of the complete segmentation pipeline, from raw data to final segmentation of the images. Also included is a validation step for CC and SWM data each, which generates all supplementary data related to validations (Fig. S2-S6).

'fig1.ipynb' creates Figure 1 from images at different steps of the pipeline.

'mcmc_CCvsSWM_GEV.ipynb' performs the MCMC modeling and plots all main figures, including supplementary figures S7, S8, and S9. The modeling part requires an installation of PyMC3.

'pymc_env.yml' contains the conda environment required to run the MCMC sampling.
