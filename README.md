# TransEQ_2021_ijcai

TRANSEQ: TRANSFORMER-BASED LOW-FREQUENCY EARTHQUAKE IDENTIFICATION

The emergent onsets, low amplitudes, and unique frequency characteristics of low-frequency seismic wave are challenging to identify potential earthquakes. Instead of leveraging the convolution neural network (CNN) based methods to uncover the local discriminative foreshadow, in this paper, we propose a Transformer-based UNet (TransEQ) with amplitude and temporal consistency awareness to locate ‘abnormal’ oscillation where may be the earthquake. Specifically, we first encode a wave sample as a sequence of amplitude and temporal patches and then build a transformer-based baseline, including a lightweight version and an accurate version, with several critical improvements. (1) We propose a decomposed patch division to extract individual spatial-series and time series context in dual self-attention module without interference. (2) We propose a self-supervised temporal consistency loss and a unsupervised amplitude consistency loss for each transformer block to expel semantic ambiguity and refine decision uncertainty. Extensive experiments using data from permanent and temporary stations near Parkfield demonstrate that our lightweight baseline achieves % with FPS and accurate baseline achieves % with FPS, outperforming existing methods with a large margin. Our code is now available at.


We are sorry that we cannot provide the original data. If you need raw data, please contact Mingjie.
The main code and data come from：
https://github.com/amtseismo/Parkfield-LFE-CNN
