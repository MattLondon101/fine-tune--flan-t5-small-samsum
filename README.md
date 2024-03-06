# fine-tune--flan-t5-small-samsum  
Pipeline to fine-tune [goole/flan-t5-small](https://huggingface.co/google/flan-t5-small) language model on the [samsum](https://huggingface.co/datasets/samsum) dataset (messenger-like conversations with summaries)  

Docker image coming soon...

## Dependencies  
This was successfully run in a Conda environment with Python 3.10 in VSCode in Ubuntu 22.04  


If you need to create a new Conda environment with ipython kernel (to run Jupyter notebook) follow directions at [Create Conda environment](#create-conda-environment)  

Clone repo from GitHub
'''
git clone 
'''  

Create a .env file in  and enter:
```
HUGGING_FACE_USERNAME=your-hugging-face-username
```

## Run Fine-Tuning
Run cells in [fine-tune-llm.ipynb](fine-tune-llm.ipynb), changing version_number in the Run Training cell if needed


## Create Conda environment:  
```
cd flan-t5-small-samsum
conda create -n hf3-10 python=3.10 -y
conda activate hf3-10
``` 

Install jupyter, notebook, and ipython kernel in conda env to run Jupyter notebook
```
pip install jupyter notebook
ipython kernel install --user --name=hf3-10
```

Restart VSCode to load ipython kernel, then reload conda env
```
conda activate hf3-10
```






