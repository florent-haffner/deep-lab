# Deep-lab

## Environment

### Environment creation 
```bash
conda create -n deep-lab-p3.9 python=3.9
conda activate deep-lab-p3.9
conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1
pip install tensorflow-gpu==2.10
pip install -r requirements.txt
```

### Environment launching
```bash
jupyter lab .
```
