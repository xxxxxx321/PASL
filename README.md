# Pose Adapted Shape Learning for Large-Pose Face Reenactment
![PASL.png](PASL.png)
> **Pose Adapted Shape Learning for Large-Pose Face Reenactment**  
> Gee-Sern Jison Hsu, Jie-Ying Zhang, Huang Yu Hsiang, Wei-Jie Hong
> 
> **Abstract:** We propose the Pose Adapted Shape Learning (PASL) for large-pose face reenactment. The PASL framework consists of three modules, namely the Pose-Adapted face Encoder (PAE), the Cycle-consistent Shape Generator (CSG), and the Attention-Embedded Generator (AEG). Different from previous approaches that use a single face encoder for identity preservation, we propose multiple Pose-Adapted face Encodes (PAEs) to better preserve facial identity across large poses.  Given a source face and a reference face, the CSG generates a recomposed shape that fuses the source identity and reference action in the shape space and meets the cycle consistency requirement. Taking the shape code and the source as inputs, the AEG learns the attention within the shape code and between the shape code and source style to enhance the generation of the desired target face. As existing benchmark datasets are inappropriate for evaluating large-pose face reenactment, we propose a scheme to compose large-pose face pairs and introduce the MPIE-LP (Large Pose) and VoxCeleb2-LP datasets as the new large-pose benchmarks. We compared our approach with state-of-the-art methods on MPIE-LP and VoxCeleb2-LP for large-pose performance and on VoxCeleb1 for the common scope of pose variation.


https://github.com/xxxxxx321/PASL/assets/151173571/88824fb8-fcaa-4035-a510-6e5cb1b9abd3







## Getting Started
- Clone the repo:
    ```
    git clonehttps://github.com/xxxxxx321/PASL
    cd PASL
    ```
## Installation
- Python 3.8
- Pytorch 1.11.0
1. Please refer to [DECA](https://github.com/yfeng95/DECA) to install the required packages.
2. Please refer to [Pytorch3d](https://github.com/facebookresearch/pytorch3d/blob/main/INSTALL.md) to install the required packages.
3. Install other requirements
   ```
    pip install -r requirements.txt
    ```
## Pretrained Model
|Path|Description|
|---|---|
|[CSG Model](https://drive.google.com/file/d/10cNTvXIHllW1_rIgQovHE26_ASfKtLX7/view?usp=sharing)|Unzip it and place it into the data directory|
|[AEG Model](https://drive.google.com/file/d/1fwRuMjjR-CinGd-niwDAvJ_l9UnH5AgM/view?usp=sharing)|Unzip it and place it into the main directory|

## Auxiliary Models
|Path|Description|
|---|---|
|[Albedo model](https://drive.google.com/file/d/1JZwaNh443hO4tLB0F3FSuT4X9euaDQIZ/view?usp=sharing)|Unzip it and place it into the data directory|
## Inference
- Run the demo.py
    ```
    python demo.py
    ```
