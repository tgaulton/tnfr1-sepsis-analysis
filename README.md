# tnfr1-sepsis-analysis
Analysis code for sTNFR1 sepsis biomarker study (Gaulton et al.)
# sTNFR1-Sepsis Analysis Code

R analysis code for: "Diabetes Mellitus and Atherosclerotic Cardiovascular Disease Modify the Association Between Soluble TNF Receptor 1 and Mortality in Sepsis"

## Main Analysis
- `master.R` - Main analysis script (run this first)

## Figure Generation
- `Fig1_TNFR1_DiabetesASCVD_spline.R` - Restricted cubic spline dose-response curves
- `Fig2_TNFR1_DiabetesASCVD_forest.R` - Forest plot of hazard ratios  
- `Fig3_TNFR1_DiabetesASCVD_specificity.R` - Specificity analysis
- `Fig4_chronic_elevation.R` - Baseline sTNFR1 elevation analysis
- `Fig5_trajectories_combined.R` - Trajectory analysis

## Usage
1. Run `master.R` first to generate the analysis dataset
2. Run individual figure scripts as needed

## Data
Raw data available through NHLBI BioLINCC: https://biolincc.nhlbi.nih.gov/

## Requirements
- R (≥4.0.0)
- Required packages: survival, rms, ggplot2, dplyr, tidyr, patchwork
