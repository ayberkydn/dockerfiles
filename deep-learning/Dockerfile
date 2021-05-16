FROM pytorch/pytorch:1.8.1-cuda11.1-cudnn8-runtime

RUN apt-get update && apt-get upgrade -y

RUN apt-get install -y --no-install-recommends    \
ffmpeg                                            \ 
libsm6                                            \
libxext6                                          \
libxvidcore4                                      \
fish                                              


RUN pip install --no-cache-dir pytorch-lightning  \
                               jupyterlab         \ 
                               pandas             \
                               numpy              \
                               scipy              \
                               matplotlib         \
                               ipython            \
                               jupyter            \
                               sympy              \
                               nose               \
                               einops             \
                               opencv-python      \
                               wandb              \
                               kornia             \
                               torchfunc          \
                               torchsummary       \
                               hydra-core         \
                               captum             \
                               timm               \
                               transformers
                 


RUN useradd -ms /usr/bin/fish ayb

##will be tidiedup
