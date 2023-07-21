# Evaluating machine comprehension of sketch meaning at different levels of abstraction

This repository contains code to reproduce the results in our CogSci 2023 paper, *Evaluating machine comprehension of sketch meaning at different levels of
abstraction*.

Directory Structure

```bash
├── paper
├── analysis
├── experiments
│   ├── category-selfpaced  
│   ├── recognition
├── results
│    ├── plots
├── data

```
`paper` contains the LaTeX source code along with figures for our paper.
`analysis` contains 3 main files -
1. `analysis_nb.ipynb` is a jupyter notebook that contains code to reproduce the results we present in our submission with headers corresponding to the different sections in the paper.
2. `linear_models.Rmd` is an R markdown notebook that contains additional analyses, specifically the results of mixed-effects models.
3. `sketch_models.yml` specifies a conda environment with the appropriate packages to reproduce our code. We recommend creating a new conda environment using the following command:
   
   ```
   conda env create -f sketch_models.yml
   ```
`experiments` contains 2 subfolders -
`category-selfpaced` contains code and materials for the human sketch production experiment
`recognition` contains code and maetrials for the human sketch recognition experiment

`results` contains a subdirectory called `plots` which is where the jupyter notebooks will save plots that are generated.

`data` will need to contain intermediate outputs, which serve as input for the R markdown and jupyter notebooks. Please place the contents found inside the `recog_exp_data` folder <a href="https://www.dropbox.com/scl/fo/2oqncsagow0k7sbn52pd1/h?dl=0&rlkey=i7ezf9lezft7o0amawb24zlvd" target="_blank">here</a>
 inside the `data` directory running any notebook cells. Refer to the README.md in the `data` directory for more details.

