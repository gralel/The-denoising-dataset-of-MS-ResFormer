MS-ResFormer

MS-ResFormer is a deep-learning framework for denoising transient electromagnetic (TEM) data. It features a multi-scale residual Transformer architecture designed to improve late-time stability and enhance underground signal recovery. This repository provides complete scripts for training, evaluation, inference, visualization, and reproducible experiments.

Features

Multi-Scale Residual Transformer architecture (MS-ResFormer)

Local temporal attention for capturing weak late-time signals


Five synthetic noise types:

Relative noise

Background noise

Electromagnetic interference

Sferic noise

Combined noise

Training, validation, and denoising visualization included

Evaluation metrics: RMSE, RRMSE, SNR

Example notebook for quick demonstration

Repository Structure：


├── train_data.npy/out_
├── MS-ResFormer.ipynb                      
└── README.md                               

Model Overview

MS-ResFormer integrates:

Multi-scale convolutional stems

Residual feature enhancement

Local window temporal attention

Late-time stability enhancement

The model is optimized for the characteristics of TEM db/dt data and achieves strong denoising performance without relying on overly complex architectures.
