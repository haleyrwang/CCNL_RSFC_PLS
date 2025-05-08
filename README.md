# CCNL_RSFC_PLS
This repository contains code and data created in support of my project "Multivariate Resting-State Functional Connectivity Features Linked to Transdiagnostic Psychopathology in Early Psychosis". All code was written in Python.

## Prerequisites
Before you begin, ensure you have met the following requirements:

- Python 3.x installed
- Jupyter Notebook or JupyterLab installed

### Libraries Used
This project depends on several Python libraries. Ensure you have the following installed:

NumPy: For numerical computing.
Pandas: For data manipulation and analysis.
Matplotlib: For creating static, interactive, and animated visualizations in Python.
SciPy: For scientific and technical computing.
Scikit-learn: For machine learning and data mining.
NiBabel: For reading and writing neuroimaging data.
Seaborn: For making statistical graphics.

You can install all dependencies by running:
pip install numpy pandas matplotlib scipy scikit-learn nibabel seaborn

## Project Structure
The project is structured to follow a specific analysis workflow. Here's how to navigate through the notebooks in the recommended order:

- [HCPEP_main.ipynb](https://github.com/haleyrwang/CCNL_RSFC_PLS/blob/main/Code/HCPEP_main.ipynb): Starts with the Partial Least Squares (PLS) analysis. This notebook is the entry point for understanding the primary patterns and relationships within the EP cohort data. It also includes visualizations and figures for the manuscript.
- [HCPEP_GSRlv0.ipynb](https://github.com/haleyrwang/CCNL_RSFC_PLS/blob/main/Code/HCPEP_GSRlv0.ipynb): This notebook contains the PLS analysis parallel to the main analysis, but uses the global signal regression (GSR) version of RSFC raw features. This result is reported in the supplementary material in the paper.
- [HCPEP_behav_correlation.ipynb](https://github.com/haleyrwang/CCNL_RSFC_PLS/blob/main/Code/HCPEP_behav_correlation.ipynb): Follows the PLS analysis with post-hoc assessments to delve deeper into the findings from the PLS analysis, correlating NIH behavioral self-report data using emotion batteries with PLS identified clinical loadings.


## Folder Structure
- The [Code](https://github.com/haleyrwang/CCNL_RSFC_PLS_EP/tree/main/Code) folder contains all the code used to run the analyses and generate the figures.
- The [Data](https://github.com/haleyrwang/CCNL_RSFC_PLS_EP/tree/main/Data) folder contains all the data used to run the analyses, including parcellation files and preprocessed RSFC data from the HCP-EP datasets. If you use any of the processed RSFC data, please cite this paper. The PLS outputs are not included due to file size.

## Contact
For any questions regarding the study, you can reach me at haleywang@ucla.edu.
