# Simplified APOGEE selection function
fits file for apogee selection function (including distance dependent selection due to extinction)

Initially computed for and used in Frankel, Sanders, Rix, Ting (2019), The inside-out growth of the Milky Way disk, only with apogee-1 disk fields. Expanded below to some fields from apogee-2.

It provides a simple way with examples to deal with selection effects with most APOGEE disk fields (but not all)

## Data
The file is available in this repository at  <br />
https://github.com/NeigeF/apogee_selection_function/blob/master/sf_apogee_dr14_disk.fits

## Tutorial

#### Content
An example tutorial showing:
- how to load the file
- how to bring an apogee dataset down to the available selection function
- how to include the selection function in a density model
- and fit this model to apogee data
- how to sample mock stars from a desnsity model in apogee fields (sort of efficiently)
- where to find the literature this work is based on

is available as a jupyter notebook in this repository at  <br />
https://github.com/NeigeF/apogee_selection_function/blob/master/selection_function_ap1-2_publ.ipynb

if the notebook does not render here, please visit:  <br />
https://nbviewer.jupyter.org/github/NeigeF/apogee_selection_function/blob/master/selection_function_ap1-2_publ.ipynb

#### Authors
Neige Frankel & Jason Sanders


