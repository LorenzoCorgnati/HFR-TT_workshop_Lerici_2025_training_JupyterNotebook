# HFR-TT_workshop_Lerici_2025_training_JupyterNotebook
This ython-based Jupyter notebook (EU_HFR_NODE_Lerici2025.ipynb) focuses on providing basic routines for inspecting the HFR-derived surface current dataset produced by the operational Near Real Time (NRT) workflow of the [European HFR Node](https://www.hfrnode.eu/). The inspection is useful for assessing the datasets and modify the processing and QC parameters, if needed.
The operational routines of the European HFR Node are available on the GitHub repository [https://github.com/LorenzoCorgnati/EU_HFR_NODE_pyHFR](https://github.com/LorenzoCorgnati/EU_HFR_NODE_pyHFR).

The datasets used by this notebook are directly read from the [THREDDS Data Server](https://thredds.hfrnode.eu) of the European HFR Node.

The comprehensive information about HFR networks and stations are read from the operational database of the European HFR Node. In order to insert or modify the information stored in the database, please use the online [webform](https://webform.hfrnode.eu) of the European HFR Node.

The required packages are:
- pandas
- fsspec
- xarray
- hvplot
- os
- intake
- cf_xarray
- panel
- numpy
- matplotlib
- xoak


Cite as:
Lorenzo Corgnati. (2025). HFR-TT_workshop_Lerici_2025_training_JupyterNotebook.


Author: Lorenzo Corgnati

Date: May 15, 2025

E-mail: lorenzo.corgnati@sp.ismar.cnr.it
