# AMR-Dataset-for-MIMO-system-with-precoding

Related dataset for the paper "Deep Learning Based Automatic Modulation Recognition: Models, Datasets, and Challenges", which is published in Digital Signal Processing.

The article is available here:[Deep Learning Based Automatic Modulation Recognition: Models, Datasets, and Challenges](https://www.sciencedirect.com/science/article/pii/S1051200422002676?via%3Dihub)

If you have any question, please contact e-mail: zhangxx8023@gmail.com

# Content
Precoding for MIMO systems has gradually become a research hot spot in recent years with the development of millimeter wave communications technology, and research on the MIMO system incorporating precoding is gaining increased attention. In this paper, we test DL-AMR for the MIMO system containing precoding, and the detailed
MIMO system can be find in our paper.

## Training data generation

**Fig.1** Training data generation for AMR in MIMO system with precoding.
![MIMO AMR framework](https://user-images.githubusercontent.com/56213845/180169488-a82d0606-bc50-4a1d-a48c-7564c1e2d37a.png)

## Accuracy
**Fig.2** Recognition accuracy comparison of four DL models on the MIMO system containing precoding. (a) 𝑁𝑡 = 4, 𝑁𝑟 = 2, (b) 𝑁𝑡 = 16, 𝑁𝑟 = 4, (c) 𝑁𝑡 = 64, 𝑁𝑟 = 16.
![MIMOcombine](https://user-images.githubusercontent.com/56213845/180170315-eefb26a9-bf1b-4b52-a692-f1c66bc9216c.png)

# Dataset Description
The dataset is generated by MATLAB and then Keras with Tensorflow as the backend is used to train the modulation recognition model. The data are modulated using different modulation methods, including ‘2PSK‘, ‘QPSK‘, ‘8PSK‘,
‘16QAM‘, ‘64QAM‘, and ‘128QAM‘. The number of transmitted symbols per sample is 128, and we prepare 500 samples per SNR per scheme, which are divided into three parts for training, validation, and testing by the ratio of 6:2:2.

The dataset is available here: [MIMO dataset](https://pan.baidu.com/s/1YvOmfXL6RXR76bx9fwVMhw?pwd=5cx4)

You can refer to the code we have released to process the dataset, or you can follow the data generation framework to generate your own dataset.

# Citation
If our work is helpful to your research, please cite:
    @article{ZHANG2022103650,
        title={Deep Learning Based Automatic Modulation Recognition: Models, Datasets, and Challenges},
        author={Fuxin Zhang and Chunbo Luo and Jialang Xu and Yang Luo and FuChun Zheng},
        journal={Digital Signal Processing},
        year={2022},
        doi = {https://doi.org/10.1016/j.dsp.2022.103650}
    }
