
# Project for GEOG788P MnM4SDS
## Topic: Projection of Permanent Forest Loss by Random Forest 
### The files are listed chronologically
* [Initial Proposal](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/Initial%20proposal.docx)
* [First Project Presentation](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/788P%20Project_update.pptx)
* [Project Presentation Update 1](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/788P%20Project_update1.pptx)
* [Project Presentation Update 2](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/788P%20Project_update2.pptx)
* [Final Project Paper](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/final_paper.docx)

### The codes used in the final project are in the [Code](https://github.com/quan-shen/QuanShen_MnM4SDS_project/tree/master/code) folder
### The codes are listed by step
* [Step 1. Identify the permanent forest loss](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/code/Permanent%20loss.ipynb)
* [Step 2. Create NLCD permanent forest loss rasters](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/code/NLCD_loss_rasters.ipynb)
* [Step 3. Preprocess the population density datasets](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/code/PopDen_preprocess.ipynb)
* [Step 4. Run regression models](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/code/GWR.ipynb)
* [Step 5. Run random forest model](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/code/Random_Forest_PopDen.ipynb)
* [Step 6. Assess GFW as reference data](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/code/NLCDloss_GFW.ipynb)

### Some of the raster files used in random forest model are in the [data](https://github.com/quan-shen/QuanShen_MnM4SDS_project/tree/master/data) folder
### Due to the space limit of GitHub, there are only:
* 1 NLCD landcover file: [NLCD 2004](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/data/NLCD04.tif)
* 1 permanent loss file: [Loss between 2005 and 2006](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/data/Loss06.tif) 
* 1 population density file: [Population Density 2005](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/data/Pop05.tif)
* 1 project result file: [The best projection result](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/data/projected_loss2019_7_100.tif), and 
* 1 reference data file: [GFW forest loss by year](https://github.com/quan-shen/QuanShen_MnM4SDS_project/blob/master/data/GFW_lossyear_2019.tif)
