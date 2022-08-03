# Projecting_SDMs
Simulation code used to project species distribution models and develop reccommendations.

Code used for Brodie et al., (in press). Recommendations for quantifying and reducing uncertainty in projections of species distributions. Global Change Biology.

# Steps:

1. Create rasters of environmental projections (using Create_ROMS_Rasters.R)
2. Operating_Models: simulations of HMS (albacore), CPS (sardine), and groundfish (sablefish)
3. Estimation_Models_Functions: functions to run species distribution models (GAM, GLMM, BRT, and MLP)
4. Estimation_Models_Working: working file to run above species distribution model functions

See Brodie et al., for full methods description, and results. 

Data:
Environmental data files, simulated species distributions, and predicted species distribution model output are stored on Dryad: https://doi.org/10.7291/D1JQ2K
