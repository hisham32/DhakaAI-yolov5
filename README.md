<a href="https://apps.apple.com/app/id1452689527" target="_blank">
![](DhakaAI.png)


This repository contains the 9th place (out of 241 teams) solution of the DhakaAI traffic detection competition, and incorporates our [evolved hyperparameters](yolov5/data) over training several configurations of yolov5 models on competition [dataset](https://doi.org/10.7910/DVN/POREXF) with the ultralytics [YOLOv5 repository](https://github.com/ultralytics/yolov5). Our approach is briefly described in the [poster](https://github.com/hisham32/yolov5/blob/master/Improving%20Vehicle%20Detection%20Using%20YOLOv5%20with%20Hyperparameter%20Evolution%2C%20Data%20Augmentation%20and%20Model%20Ensemble.pdf). The training and inference codes are available inside the [jupyter notebook](yolov5/Transportist_YOLOv5_DhakaAI_Training+Evaluation.ipynb) **All code and models are under active development, and are subject to modification.** 


## Requirements

Python 3.8 or later with all [requirements.txt](https://github.com/ultralytics/yolov5/blob/master/requirements.txt) dependencies installed, including `torch>=1.6`. To install run:
```bash
$ pip install -r requirements.txt
```


## Tutorials

* [Train Custom Data](https://github.com/ultralytics/yolov5/wiki/Train-Custom-Data) (🚀  recommended)
* [Weights & Biases Logging](https://github.com/ultralytics/yolov5/issues/1289) (🚀  NEW)
* [Multi-GPU Training](https://github.com/ultralytics/yolov5/issues/475)
* [PyTorch Hub](https://github.com/ultralytics/yolov5/issues/36)
* [ONNX and TorchScript Export](https://github.com/ultralytics/yolov5/issues/251)
* [Test-Time Augmentation (TTA)](https://github.com/ultralytics/yolov5/issues/303)
* [Model Ensembling](https://github.com/ultralytics/yolov5/issues/318)
* [Model Pruning/Sparsity](https://github.com/ultralytics/yolov5/issues/304)
* [Hyperparameter Evolution](https://github.com/ultralytics/yolov5/issues/607)
* [TensorRT Deployment](https://github.com/wang-xinyu/tensorrtx)


## Environments

YOLOv5 may be run in any of the following up-to-date verified environments (with all dependencies including [CUDA](https://developer.nvidia.com/cuda)/[CUDNN](https://developer.nvidia.com/cudnn), [Python](https://www.python.org/) and [PyTorch](https://pytorch.org/) preinstalled):

- **Google Colab Notebook** with free GPU: <a href="https://colab.research.google.com/github/ultralytics/yolov5/blob/master/tutorial.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
- **Kaggle Notebook** with free GPU: [https://www.kaggle.com/ultralytics/yolov5](https://www.kaggle.com/ultralytics/yolov5)
- **Google Cloud** Deep Learning VM. See [GCP Quickstart Guide](https://github.com/ultralytics/yolov5/wiki/GCP-Quickstart) 
- **Docker Image** https://hub.docker.com/r/ultralytics/yolov5. See [Docker Quickstart Guide](https://github.com/ultralytics/yolov5/wiki/Docker-Quickstart) ![Docker Pulls](https://img.shields.io/docker/pulls/ultralytics/yolov5?logo=docker)


## Contact

**Issues should be raised directly in the repository.** For business inquiries or professional support requests please visit https://www.ultralytics.com or email Glenn Jocher at glenn.jocher@ultralytics.com. 
