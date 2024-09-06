# 📒Awesome-SD-Inference
<div align='left'>
  <img src=https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg >
  <img src=https://img.shields.io/github/forks/DefTruth/Awesome-SD-Inference.svg?style=social >
  <img src=https://img.shields.io/github/stars/DefTruth/Awesome-SD-Inference.svg?style=social >
  <img src=https://img.shields.io/github/watchers/DefTruth/Awesome-SD-Inference.svg?style=social >
  <img src=https://img.shields.io/badge/Release-v0.5-brightgreen.svg >
  <img src=https://img.shields.io/badge/License-GPLv3.0-turquoise.svg >
 </div>   

📒A **small** curated list of Awesome **SD/DiT/Diffusion** Inference with **Distributed/Caching/Sampling**. For Awesome LLM Inference, please check 📖[Awesome-LLM-Inference](https://github.com/DefTruth/Awesome-LLM-Inference)  ![](https://img.shields.io/github/stars/DefTruth/Awesome-LLM-Inference.svg?style=social)

## 🤖Contents

- [📙Awesome SD Inference with Sampling](#Sampling)
- [📙Awesome SD Inference with Caching](#Caching)
- [📙Awesome SD Inference with Multi-GPUs](#Distributed)
- [📙Other Awesome SD Inference Paper with codes](#Others)


## ©️Citations 

```BibTeX
@misc{Awesome-SD-Inference@2024,
  title={Awesome-SD-Inference: A small curated list of Awesome SD/DiT/ViT/Diffusion Inference with Distributed/Caching/Sampling.},
  url={https://github.com/DefTruth/Awesome-SD-Inference},
  note={Open-source software available at https://github.com/DefTruth/Awesome-SD-Inference},
  author={DefTruth},
  year={2024}
}
```


## 📙Awesome SD Inference with Sampling  

<div id="Sampling"></div>  

|Date|Title|Paper|Code|Recom|
|:---:|:---:|:---:|:---:|:---:|   
|2020.06| 🔥[**DDPM**] Denoising Diffusion Probabilistic Models(@UC Berkeley)  | [[pdf]](https://arxiv.org/abs/2006.11239) |[[diffusion]](https://github.com/hojonathanho/diffusion) ![](https://img.shields.io/github/stars/hojonathanho/diffusion.svg?style=social) |⭐️⭐️ | 
|2020.10| 🔥[**DDIM**] DENOISING DIFFUSION IMPLICIT MODELS(@cs.stanford.edu) | [[pdf]](https://arxiv.org/pdf/2010.02502) |⚠️|⭐️⭐️ |
|2022.02| 🔥[**PNDM**] PSEUDO NUMERICAL METHODS FOR DIFFUSION MODELS ON MANIFOLDS(@) | [[pdf]](https://arxiv.org/pdf/2202.09778) |[[PNDM]](https://github.com/luping-liu/PNDM) ![](https://img.shields.io/github/stars/luping-liu/PNDM.svg?style=social) |⭐️⭐️ | 
|2022.02| 🔥[**DPM-Solver**] DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps(@Cheng Lu) | [[pdf]](https://arxiv.org/pdf/2206.00927) |[[dpm-solver]](https://github.com/LuChengTHU/dpm-solver) ![](https://img.shields.io/github/stars/LuChengTHU/dpm-solver.svg?style=social) |⭐️⭐️ | 
|2022.11| 🔥[**DPM-Solver++**] DPM-SOLVER++: FAST SOLVER FOR GUIDED SAMPLING OF DIFFUSION PROBABILISTIC MODELS(@Cheng Lu) | [[pdf]](https://arxiv.org/pdf/2211.01095) |[[dpm-solver]](https://github.com/LuChengTHU/dpm-solver) ![](https://img.shields.io/github/stars/LuChengTHU/dpm-solver.svg?style=social) |⭐️⭐️ | 
|2023.10| 🔥[**DPM-Solver-v3**] DPM-Solver-v3: Improved Diffusion ODE Solver with Empirical Model Statistics(@Kaiwen Zheng) | [[pdf]](https://arxiv.org/pdf/2310.13268) |[[DPM-Solver-v3]](https://github.com/thu-ml/DPM-Solver-v3) ![](https://img.shields.io/github/stars/Lthu-ml/DPM-Solver-v3.svg?style=social) |⭐️⭐️ | 
|2023.11| 🔥[**Parallel Sampling**] Parallel Sampling of Diffusion Models(@Stanford University) | [[pdf]](https://papers.nips.cc/paper_files/paper/2023/file/0d1986a61e30e5fa408c81216a616e20-Paper-Conference.pdf) | [[paradigms]](https://github.com/AndyShih12/paradigms) ![](https://img.shields.io/github/stars/AndyShih12/paradigms.svg?style=social) |⭐️⭐️ |
|2023.11| 🔥[**SAMPLER SCHEDULER**] SAMPLER SCHEDULER FOR DIFFUSION MODELS(@sysu)| [[pdf]](https://arxiv.org/pdf/2311.06845) |⚠️|⭐️⭐️ |
|2024.02| 🔥[**Parallel Sampling**] Accelerating Parallel Sampling of Diffusion Models(@Zhiwei Tang) | [[pdf]](https://arxiv.org/pdf/2402.09970) | [[ParaTAA-Diffusion]](https://github.com/TZW1998/ParaTAA-Diffusion) ![](https://img.shields.io/github/stars/TZW1998/ParaTAA-Diffusion.svg?style=social) |⭐️⭐️ | 
|2024.01| 🔥[**YONOS**] You Only Need One Step: Fast Super-Resolution with Stable Diffusion via Scale Distillation(@Samsung AI) | [[pdf]](https://arxiv.org/pdf/2401.17258) |⚠️|⭐️⭐️ |
|2024.01| 🔥[**S^2-DM**] S^2-DMs: Skip-Step Diffusion Models(@Yixuan Wang) | [[pdf]](https://arxiv.org/pdf/2401.01520) |⚠️|⭐️⭐️ |
|2024.08| 🔥[**StepSaver**] StepSaver: Predicting Minimum Denoising Steps for Diffusion Model Image Generation(@intel) | [[pdf]](https://arxiv.org/pdf/2408.02054) |⚠️|⭐️⭐️ |

## 📙Awesome SD Inference with Caching  

<div id="Caching"></div>  

- **UNet Based (DeepCache)**

<img width="1645" alt="image" src="https://github.com/user-attachments/assets/a7257462-80d3-40af-a4ce-3550508fabe7">


- **DiT Based (Fast-Forward Caching)**
<img width="1119" alt="image" src="https://github.com/user-attachments/assets/fad8f187-d4ac-4290-9943-7b34116fed05">

|Date|Title|Paper|Code|Recom|
|:---:|:---:|:---:|:---:|:---:|   
|2023.05|🔥🔥[**Cache-Enabled Sparse Diffusion**] Accelerating Text-to-Image Editing via Cache-Enabled Sparse Diffusion Inference(@pku.edu.cn etc)|[[pdf]](https://arxiv.org/pdf/2305.17423) |⚠️|⭐️⭐️ | 
|2023.12|🔥🔥[**DeepCache**] DeepCache: Accelerating Diffusion Models for Free(@nus.edu)|[[pdf]](https://arxiv.org/pdf/2312.00858) | [[DeepCache]](https://github.com/horseee/DeepCache) ![](https://img.shields.io/github/stars/horseee/DeepCache.svg?style=social)| ⭐️⭐️ |   
|2023.12|🔥🔥[**Block Caching**] Cache Me if You Can: Accelerating Diffusion Models through Block Caching(@Meta GenAI etc)|[[pdf]](https://arxiv.org/pdf/2312.03209) |⚠️|⭐️⭐️ | 
|2023.12|🔥🔥[**Approximate Caching**] Approximate Caching for Efficiently Serving Diffusion Models(@Adobe)|[[pdf]](https://arxiv.org/pdf/2312.04429) |⚠️|⭐️⭐️ |
|2024.06| 🔥🔥[**Layer Caching**] Learning-to-Cache: Accelerating Diffusion Transformer via Layer Caching(@nus.edu)  | [[pdf]](https://arxiv.org/pdf/2406.01733) | [[learning-to-cache]](https://github.com/horseee/learning-to-cache/) ![](https://img.shields.io/github/stars/horseee/learning-to-cache.svg?style=social)| ⭐️⭐️ | 
|2024.07|🔥[**ElasticCache-LVLM**] Efficient Inference of Vision Instruction-Following Models with Elastic Cache(@Tsinghua University etc)|[[pdf]](https://arxiv.org/pdf/2407.18121)|[[ElasticCache]](https://github.com/liuzuyan/ElasticCache) ![](https://img.shields.io/github/stars/liuzuyan/ElasticCache.svg?style=social)|⭐️ |
|2024.07| 🔥🔥[**Fast-Forward Caching(DiT)**] FORA: Fast-Forward Caching in Diffusion Transformer Acceleration(@microsoft.com etc) | [[pdf]](https://arxiv.org/pdf/2407.01425) | [[FORA]](https://github.com/prathebaselva/FORA) ![](https://img.shields.io/github/stars/prathebaselva/FORA.svg?style=social)|⭐️⭐️ |
|2024.07| 🔥🔥[**Faster I2V Generation**] Faster Image2Video Generation: A Closer Look at CLIP Image Embedding’s Impact on Spatio-Temporal Cross-Attentions(@Ashkan Taghipour etc)|[[pdf]](https://arxiv.org/pdf/2407.19205) |⚠️|⭐️⭐️ |
|2024.04| 🔥🔥[**T-GATE V1**] Cross-Attention Makes Inference Cumbersome in Text-to-Image Diffusion Models(@Wentian Zhang etc)|[[pdf]](https://arxiv.org/pdf/2404.02747v1) | [[T-GATE]](https://github.com/HaozheLiu-ST/T-GATE) ![](https://img.shields.io/github/stars/HaozheLiu-ST/T-GATE.svg?style=social)|⭐️⭐️ |
|2024.04| 🔥🔥[**T-GATE V2**] Faster Diffusion via Temporal Attention Decomposition(@Haozhe Liu etc)|[[pdf]](https://arxiv.org/pdf/2404.02747v2) | [[T-GATE]](https://github.com/HaozheLiu-ST/T-GATE) ![](https://img.shields.io/github/stars/HaozheLiu-ST/T-GATE.svg?style=social)|⭐️⭐️ |

## 📙Awesome SD Distributed Inference with Multi-GPUs

<div id="Distributed"></div>  

- **UNet Based: Displaced Patch parallelism (DistriFusion)**

<img width="1677" alt="image" src="https://github.com/user-attachments/assets/aefb2ae7-73eb-4e9c-bf1a-ec540f4dfa7d">

- **DiT Based: Displaced Patch parallelism (PipeFusion)**

<img width="1346" alt="image" src="https://github.com/user-attachments/assets/692c5d54-19b3-4ce7-9613-9eb8bb035c7d">


|Date|Title|Paper|Code|Recom|
|:---:|:---:|:---:|:---:|:---:|   
|2024.02|🔥🔥[**DistriFusion**] DistriFusion: Distributed Parallel Inference for High-Resolution Diffusion Models(@MIT etc)|[[pdf]](https://arxiv.org/abs/2402.19481) | [[distrifuser]](https://github.com/mit-han-lab/distrifuser) ![](https://img.shields.io/github/stars/mit-han-lab/distrifuser.svg?style=social)| ⭐️⭐️ |   
|2024.05|🔥🔥[**PipeFusion**] PipeFusion: Displaced Patch Pipeline Parallelism for Inference of Diffusion Transformer Models(@Tencent etc)|[[pdf]](https://arxiv.org/pdf/2405.14430) | [[xDiT]](https://github.com/xdit-project/xDiT) ![](https://img.shields.io/github/stars/xdit-project/xDiT.svg?style=social)| ⭐️⭐️ | 
|2024.06| 🔥🔥[**AsyncDiff**] AsyncDiff: Parallelizing Diffusion Models by Asynchronous Denoising(@nus.edu) | [[pdf]](https://arxiv.org/pdf/2406.06911) | [[AsyncDiff]](https://github.com/czg1225/AsyncDiff) ![](https://img.shields.io/github/stars/czg1225/AsyncDiff.svg?style=social)| ⭐️⭐️ |   
|2024.05 | 🔥🔥[**TensorRT-LLM SDXL**] SDXL Distributed Inference with TensorRT-LLM and synchronous comm(@Zars19) | [[pdf]](https://arxiv.org/abs/2402.19481) | [[SDXL-TensorRT-LLM]](https://github.com/NVIDIA/TensorRT-LLM/pull/1514) ![](https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM.svg?style=social)| ⭐️⭐️ | 
|2024.06| 🔥🔥[**Clip Parallelism**] Video-Infinity: Distributed Long Video Generation(@nus.edu)|[[pdf]](https://arxiv.org/pdf/2406.16260) | [[Video-Infinity]](https://github.com/Yuanshi9815/Video-Infinity) ![](https://img.shields.io/github/stars/Yuanshi9815/Video-Infinity.svg?style=social)|⭐️⭐️ | 
|2024.05| 🔥🔥[**FIFO-Diffusion**] FIFO-Diffusion: Generating Infinite Videos from Text without Training(@Seoul National University)|[[pdf]](https://arxiv.org/pdf/2405.11473) |  [[FIFO-Diffusion]](https://github.com/jjihwan/FIFO-Diffusion_public) ![](https://img.shields.io/github/stars/jjihwan/FIFO-Diffusion_public.svg?style=social) |⭐️⭐️ | 

## 📙Other Awesome SD Inference Paper with codes
<div id="Others"></div>  

|Date|Title|Paper|Code|Recom|
|:---:|:---:|:---:|:---:|:---:|   
|2024.06| 🔥[**DiTFastAttn**] DiTFastAttn: Attention Compression for Diffusion Transformer Models(@Zhihang Yuan etc)|[[pdf]](https://arxiv.org/pdf/2406.08552) | [[DiTFastAttn]](https://github.com/thu-nics/DiTFastAttn) ![](https://img.shields.io/github/stars/thu-nics/DiTFastAttn.svg?style=social)|⭐️⭐️ |
|2024.08| 🔥[**Transfusion**] Transfusion: Predict the Next Token and Diffuse Images with One Multi-Modal Model(@meta)|[[pdf]](https://www.arxiv.org/pdf/2408.11039) | [[transfusion-pytorch]](https://github.com/lucidrains/transfusion-pytorch) ![](https://img.shields.io/github/stars/lucidrains/transfusion-pytorch.svg?style=social)|⭐️⭐️ |
|2024.08| 🔥[**VQ4DiT**] VQ4DiT: Efficient Post-Training Vector Quantization for Diffusion Transformers(@ZJU)|[[pdf]](https://arxiv.org/pdf/2408.17131)  |⚠️|⭐️⭐️ |
|2024.08| 🔥[**LBQ**] Low-Bitwidth Floating Point Quantization for Efficient High-Quality Diffusion Models(@toronto.edu)|[[pdf]](https://arxiv.org/pdf/2408.06995)  |⚠️|⭐️⭐️ |
|2024.08| 🔥[**EE-Diffusion**] A Simple Early Exiting Framework for Accelerated Sampling in Diffusion Models(@KAIST AI)|[[pdf]](https://arxiv.org/pdf/2408.05927) | [[ee-diffusion]](https://github.com/taehong-moon/ee-diffusion) ![](https://img.shields.io/github/stars/taehong-moon/ee-diffusion.svg?style=social)|⭐️⭐️ |
|2024.08| 🔥[**TFM-PTQ**] Temporal Feature Matters: A Framework for Diffusion Model Quantization(@SenseTime)|[[pdf]](https://arxiv.org/pdf/2407.19547)  |⚠️|⭐️⭐️ |
|2024.08| 🔥[**Diffusion-RWKV**] Diffusion-RWKV: Scaling RWKV-Like Architectures for Diffusion Models(@Zhengcong Fei)|[[pdf]](https://arxiv.org/pdf/2404.04478) | [[Diffusion-RWKV]](https://github.com/feizc/Diffusion-RWKV) ![](https://img.shields.io/github/stars/feizc/Diffusion-RWKV.svg?style=social)|⭐️⭐️ |
|2024.09| 🔥[**LinFusion**] LINFUSION: 1 GPU, 1 MINUTE, 16K IMAGE(@NUS)|[[pdf]](https://arxiv.org/pdf/2409.02097) | [[LinFusion]](https://github.com/Huage001/LinFusion) ![](https://img.shields.io/github/stars/Huage001/LinFusion.svg?style=social)|⭐️⭐️ |

## ©️License  

GNU General Public License v3.0  

## 🎉Contribute  

Welcome to star & submit a PR to this repo! 

<div align='center'>
<a href="https://star-history.com/#DefTruth/Awesome-SD-Inference&Date">
  <picture align='center'>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=DefTruth/Awesome-SD-Inference&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=DefTruth/Awesome-SD-Inference&type=Date" />
    <img width="350" height="250" alt="Star History Chart" src="https://api.star-history.com/svg?repos=DefTruth/Awesome-SD-Inference&type=Date" />
  </picture>
</a>
</div>
