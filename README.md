[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Luo-Z13/Awesome-High-Resolution-Multimodal-LLMs)


# <p align=center>`Awesome High-Resolution Multimodal-LLMs`</p>

:star2:**A collection of papers on Multimodal Large Language Models (MLLMs) specifically designed for efficiently processing high-resolution or large-size images.**

## 📢 Latest Updates
:fire::fire::fire: Last Updated on 2024.07.18 :fire::fire::fire:

- **2024.7.16**: Initial version.


## Table of Contents
- **Models**
  - [General High-Resolution MLLMs](#general-high-resolution-mllms)
  - [Efficient MLLMs for High-Resolution Imagery](#efficient-mllms-for-high-resolution-imagery)
  - [Focus and Search MLLMs](#focus-and-search-mllms)
  - [Other High-Resolution MLLMs](#other-high-resolution-mllms)
- **Others**
  - [Relevant Projects](#relevant-projects)
  
## General High-Resolution MLLMs

|Abbreviation|Title|Publication|Method|Code & Weights|
|:---:|---|:---:|:---:|:---:|
|**OtterHD**|OtterHD: A High-Resolution Multi-modality Model|[Arxiv2023](https://arxiv.org/pdf/2311.04219)|LR+HR|[link](https://github.com/Luodian/Otter)|
|**UReader**|UReader: Universal OCR-free Visually-situated Language Understanding with Multimodal Large Language Model|[Arxiv2023](https://arxiv.org/pdf/2310.05126)|LR+HR|[link](https://github.com/LukeForeverYoung/UReader)|
|**SPHINX**|SPHINX: A Mixer of Tasks, Domains, and Embeddings Advances Multi-modal Large Language Models|[Arxiv2023](https://arxiv.org/pdf/2311.07575)|LR+HR|[link](https://github.com/Alpha-VLLM/LLaMA2-Accessory)|
|**LLaVA-1.5-HD**|Improved Baselines with Visual Instruction Tuning|[CVPR2024](https://arxiv.org/abs/2310.03744)|LR+HR|[link](https://llava-vl.github.io/)|
|**Monkey**|Monkey: Image Resolution and Text Label Are Important Things for Large Multi-modal Models|[CVPR2024](https://arxiv.org/abs/2311.06607)| LR+HR |[link](https://github.com/Yuliang-Liu/Monkey)|
|**InternVL 1.5/2.0**|How Far Are We to GPT-4V? Closing the Gap to Commercial Multimodal Models with Open-Source Suites|[CVPR2024](https://arxiv.org/pdf/2404.16821)| LR+ Dyn. HR|[link](https://github.com/OpenGVLab/InternVL)|
|**CogAgent**|CogAgent: A Visual Language Model for GUI Agents|[CVPR2024](https://arxiv.org/pdf/2312.08914)|LR+HR|[link](https://github.com/THUDM/CogVLM)|
|**S<sup>2</sup>-Wrapper**|When Do We Not Need Larger Vision Models?|[ECCV2024](https://arxiv.org/abs/2403.13043)|LR+HR|[link](https://github.com/bfshi/scaling_on_scales)|
|**LLaVA-HR**|Feast Your Eyes: Mixture-of-Resolution Adaptation for Multimodal Large Language Models|[Arxiv2024](https://arxiv.org/abs/2403.03003)|LR+ CNN HR|[link](https://github.com/luogen1996/LLaVA-HR)|
|**LLaVA-UHD**|LLaVA-UHD: an LMM Perceiving Any Aspect Ratio and High-Resolution Images|[Arxiv2024](https://arxiv.org/pdf/2403.11703)|LR+ Dyn. HR|[link](https://github.com/thunlp/LLaVA-UHD)|
|**TextMonkey**|TextMonkey: An OCR-Free Large Multimodal Model for Understanding Document|[Arxiv2024](https://arxiv.org/abs/2403.04473)|LR+HR|[link](https://github.com/Yuliang-Liu/Monkey)|
|**Mini-Gemini**|Mini-Gemini: Mining the Potential of Multi-modality Vision Language Models|[Arxiv2024](https://arxiv.org/pdf/2403.18814)|LR+ CNN HR|[link](https://github.com/dvlab-research/MGM)|
|**DeepSeek-VL**|DeepSeek-VL: Towards Real-World Vision-Language Understanding|[Arxiv2024](https://arxiv.org/pdf/2403.05525)|LR+HR|[link](https://github.com/deepseek-ai/DeepSeek-VL)|
|**InternLM-XComposer2-4KHD**|InternLM-XComposer2-4KHD: A Pioneering Large Vision-Language Model Handling Resolutions from 336 Pixels to 4K HD|[Arxiv2024](https://arxiv.org/pdf/2404.06512)|LR+HR|[link](https://github.com/InternLM/InternLM-XComposer)|
|**SliME**|Beyond LLaVA-HD: Diving into High-Resolution Large Multimodal Models|[Arxiv2024](https://arxiv.org/abs/2406.08487)|LR+ Dyn. HR|[link](https://github.com/yfzhang114/SliME)|
|**DeepStack**|DeepStack: Deeply Stacking Visual Tokens is Surprisingly Simple and Effective for LMMs|[Arxiv2024](https://arxiv.org/pdf/2406.04334)|LR+HR|[link](https://github.com/MengLcool/DeepStack-VL)|
|**HiRes-LLaVA**|HiRes-LLaVA: Restoring Fragmentation Input in High-Resolution Large Vision-Language Models|[Arxiv2024](https://arxiv.org/pdf/2407.08706)|LR+HR|None|
|**INF-LLaVA**|INF-LLaVA: Dual-perspective Perception for High-Resolution Multimodal Large Language Model|[Arxiv2024](https://arxiv.org/pdf/2407.16198)|LR+HR|[link](https://github.com/WeihuangLin/INF-LLaVA)|

## Efficient MLLMs for High-Resolution Imagery
|Abbreviation|Title|Publication|Method|Code & Weights|
|:---:|---|:---:|:---:|:---:|
|**BLIP-2**|BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models|[ICML2023](https://arxiv.org/pdf/2305.06500)|Q-Former|[link](https://huggingface.co/docs/transformers/v4.28.1/model_doc/blip-2)|
|**LLaMA-VID**|LLaMA-VID: An Image is Worth 2 Tokens in Large Language Models|[Arxiv2023](https://arxiv.org/pdf/2311.17043)|embedding compression|[link](https://github.com/dvlab-research/LLaMA-VID)|
|**VoCo-LLaMA**|VoCo-LLaMA: Towards Vision Compression with Large Language Models|[Arxiv2024](https://arxiv.org/abs/2406.12275)|token compression|[link](https://yxxxb.github.io/VoCo-LLaMA-page/)|
|**TokenPacker**|TokenPacker: Efficient Visual Projector for Multimodal LLM|[Arxiv2024](https://arxiv.org/abs/2407.02392)|token compression|[link](https://github.com/CircleRadon/TokenPacker)|

## Focus and Search MLLMs
|Abbreviation|Title|Publication|Method|Code & Weights|
|:---:|---|:---:|:---:|:---:|
|**V<sup>*</sup>**|$V^*$: Guided Visual Search as a Core Mechanism in Multimodal LLMs|[CVPR2024](https://openaccess.thecvf.com/content/CVPR2024/papers/Wu_V_Guided_Visual_Search_as_a_Core_Mechanism_in_Multimodal_CVPR_2024_paper.pdf)|Search+Zoom|[link](https://vstar-seal.github.io/)|
|**DualFocus**|DualFocus: Integrating Macro and Micro Perspectives in Multi-modal Large Language Models|[Arxiv2024](https://arxiv.org/pdf/2402.14767)|Search+Zoom|[link](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/DualFocus)|
|**Visual CoT**|Visual CoT: Advancing Multi-Modal Language Models with a Comprehensive Dataset and Benchmark for Chain-of-Thought Reasoning|[Arxiv2024](https://arxiv.org/pdf/2403.16999)|Focus+CoT|[link](https://github.com/deepcs233/Visual-CoT)|
|**P<sup>2</sup>G**|Plug-and-Play Grounding of Reasoning in Multimodal Large Language Models|[Arxiv2024](https://arxiv.org/pdf/2403.19322)|Focus+Ground Agent|None|
|**TextCoT**|TextCoT: Zoom In for Enhanced Multimodal Text-Rich Image Understanding|[Arxiv2024](https://arxiv.org/pdf/2404.09797)|Focus+Zoom|[link](https://github.com/bzluan/TextCoT)|

## Other High-Resolution MLLMs

|Abbreviation|Title|Publication|Paper|Code & Weights|
|:---:|---|:---:|:---:|:---:|
|**Llama3-Med**|Advancing High Resolution Vision-Language Models in Biomedicine|Arxiv2024|[link](https://arxiv.org/pdf/2406.09454)|[link](https://github.com/standardmodelbio/Llama3-Med)|



## Relevant Projects
*（TODO. This section is dedicated to recommending more relevant and impactful projects. :smile: :rocket:）*
|Title|Link|Brief Introduction|
|---|:---:|:---:|
|**Efficient-Multimodal-LLMs-Survey**|[github](https://github.com/lijiannuist/Efficient-Multimodal-LLMs-Survey)|A survey about efficient and lightweight MLLMs.|
|**Awesome-Multimodal-Large-Language-Models**|[github](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)|A survey about MLLMs.|

If you find this repository useful, please consider giving a star :star:!
