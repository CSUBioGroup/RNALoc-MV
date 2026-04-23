# RNALoc-MV

RNA subcellular localization prediction via multi-view sequence feature learning

This repository contains the code for the RNA Subcellular Localization Prediction Model (RNALoc-MV), which can be used to predict the subcellular localization of three types of RNA: lncRNA, circRNA, and miRNA. 

Before start, you need to create the environment required for the project. 

### Create Environment

1. create the required conda environment

```python
cd RNALoc-MV
conda env create -f environment.yaml
```

2. activate the "RNALoc-MV" environment and enter into the workspace

```python
conda activate RNALoc-MV
```

3. install evo2

```python
pip install flash-attn==2.8.0.post2 --no-build-isolation
pip install evo2
```

4. add Jupyter kernel

```python
conda install ipykernel
python -m ipykernel install --user --name=RNALoc-MV
```

### Usage

Next, you can read the RNALoc-MV.ipynb file and try to train the model.
In the lncRNA, circRNA, and miRNA modules, you can train models to predict the subcellular localization of different RNAs.

Or, you can directly run the Prediction module in RNALoc-MV.ipynb to test the dataset with the trained model.

### Citation
Min Zeng, Xinyu Zhang, Yiming Li, Chengqian Lu, Rui Yin, Fei Guo, Min Li*, “RNALoc-MV: RNA subcellular localization prediction via multi-view sequence feature learning”.
