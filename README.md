# FastMRI with SwinIR

FastMRI aims to solve the problems of the slow scanning process of MRI images. In the following solution we use the Swin Transformer for super resolution of MRI images. The model is trained with a dataset of 10,000 images on Nivida A100 GPU's with 40 GB of GPU memory.

## Getting Started

- Clone the repositiory.
- Run "streamlit run dashboard.py".
- Upload low resolution MRI image to upscale.

<img src="./dashboard.png" title="demo" alt="demo"/>&nbsp;


## Finetuning

### Dataset
Download additional dataset from https://fastmri.med.nyu.edu and save the file in the h5datafiles folder.

### Training

- Run Data_collection.ipynb and new data would be appended to data in the dataset folder.

- Run SwinIR_Train.ipynb file in google colab or any other eviroment. 
