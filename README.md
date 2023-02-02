# Deep-lab
This repository was inspired by : [Dan Suh's - Deep Learning Roadmap](https://github.com/dansuh17/deep-learning-roadmap).

> This repository is my digital laboratory. It will allow me to deepen my knowledge, to work with different architectures and maybe to gather new ideas outside my research field.


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
