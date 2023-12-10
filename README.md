# Pose Adapted Shape Learning for Large-Pose Face Reenactment
![PASL.png](PASL.png)
> **Pose Adapted Shape Learning for Large-Pose Face Reenactment**  
> Gee-Sern Jison Hsu, Jie-Ying Zhang, Huang Yu Hsiang, Wei-Jie Hong
> **Abstract:** We propose the Pose Adapted Shape Learning (PASL) for large-pose face reenactment. The PASL framework consists of three modules, namely the Pose-Adapted face Encoder (PAE), the Cycle-consistent Shape Generator (CSG), and the Attention-Embedded Generator (AEG). Different from previous approaches that use a single face encoder for identity preservation, we propose multiple Pose-Adapted face Encodes (PAEs) to better preserve facial identity across large poses.  Given a source face and a reference face, the CSG generates a recomposed shape that fuses the source identity and reference action in the shape space and meets the cycle consistency requirement. Taking the shape code and the source as inputs, the AEG learns the attention within the shape code and between the shape code and source style to enhance the generation of the desired target face. As existing benchmark datasets are inappropriate for evaluating large-pose face reenactment, we propose a scheme to compose large-pose face pairs and introduce the MPIE-LP (Large Pose) and VoxCeleb2-LP datasets as the new large-pose benchmarks. We compared our approach with state-of-the-art methods on MPIE-LP and VoxCeleb2-LP for large-pose performance and on VoxCeleb1 for the common scope of pose variation.
## Getting Started
- Clone the repo:
    ```
    git clone https://https://github.com/xxxxxx321/PASL
    cd PASL
    ```
## Installation
### Python 3.8
### Pytorch 1.11.0
## Pretrained Model

## Auxiliary Models

## Inference
- Run the demo.py
    ```
    python demo.py
    ```
