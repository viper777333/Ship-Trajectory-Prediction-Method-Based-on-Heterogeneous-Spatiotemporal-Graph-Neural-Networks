# Ship Trajectory Prediction Method Based on Heterogeneous Spatiotemporal Graph Neural Networks



## Abstract



With the rapid growth of maritime transportation, ensuring navigational safety has become increasingly important. Accurate trajectory prediction is vital in understanding ships' future intentions and supporting safe navigation. In recent years, many researchers have explored ship-to-ship interactions to improve prediction accuracy. However, real-world maritime interactions are often complex and diverse. We propose a ship Trajectory Prediction Model Based on a Heterogeneous Spatiotemporal Graph Neural Network to address this. The model effectively captures diverse social interactions among vessels by heterogeneous graph structures. A Dual-Axis Attention Aggregation (DAA) mechanism is introduced to accurately capture spatial interaction features, while the iTransformer is employed to extract long-term dependencies from trajectory sequences. We evaluate our method on three real-world AIS datasets, comparing it with several state-of-the-art baselines. Experimental results show that our model achieves the highest prediction accuracy in short-term, mid-term, and long-term scenarios while maintaining robustness, efficiency, and practicality even when predicting multi-vessel trajectories in congested and complex maritime environments.



## Requirements



```shell

python==3.10

pytorch==2.1.0+cu121

pyg==2.6.1

matplotlib==3.5.1

numpy==1.22.4

pandas==1.4.3

scipy==1.8.1

```



## Dataset



The project provides the datasets and data preprocessing code used in this study.



##  RUN



After configuring the environment, the HSTDFormer file can be executed directly.

## Citation



If you find this repository useful, please consider citing this paper.

## Contact



If you have any questions, please feel free to contact Zelin Song via email at Songzelin@mail.dlut.edu.cn or through GitHub issues. Pull requests are very welcome!



## Confirm



Thanks to the Danish Maritime Authority (http://www.dma.dk) and the U.S. Federal Maritime Commission (https://www.fmc.gov) for providing the datasets, and to https://github.com/AIR-SkyForecast/METO-S2S for sharing the data preprocessing code.



