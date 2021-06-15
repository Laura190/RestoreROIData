# Restore ROI Data To OMERO from Database Files
20210615 Laura Cooper

Read text files generated from database and import recoved ROIs to the associated images. Use for the case where images/ROIs have been accidentally deleted.

## Installation:

conda create -n myenv
conda activate myenv
conda install notebook
pip install omero-py
conda install pandas

## Package versions
pandas 1.2.4
omero-py 5.9.2
notebook 6.4.0
