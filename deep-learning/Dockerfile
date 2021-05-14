FROM pytorch/pytorch:1.8.1-cuda11.1-cudnn8-runtime

RUN apt-get update && apt-get upgrade -y
RUN pip install pytorch-lightning       
RUN pip install jupyterlab              
RUN pip install pandas                  
RUN pip install numpy                   
RUN pip install scipy                   
RUN pip install matplotlib              
RUN pip install ipython                 
RUN pip install jupyter                 
RUN pip install pandas                  
RUN pip install sympy                   
RUN pip install nose                    
RUN pip install einops                  
RUN pip install opencv-python           
RUN pip install wandb                   
RUN pip install kornia                  
RUN pip install torchfunc torchsummary 
RUN pip install hydra-core              
RUN pip install captum                  
RUN pip install timm


RUN apt-get install ffmpeg libsm6 libxext6  -y
RUN apt-get install libxvidcore4 -y
