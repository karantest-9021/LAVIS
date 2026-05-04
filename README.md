<p align="center">
    <br>
    <img src="docs/_static/logo_final.png" width="400"/>
    <br>
<p>

<div align="center">
  <a href="https://github.com/salesforce/LAVIS/releases"><img alt="Latest Release" src="https://img.shields.io/github/release/salesforce/LAVIS.svg" /></a>
  <a href="https://opensource.salesforce.com/LAVIS/index.html">
  <img alt="docs" src="https://github.com/salesforce/LAVIS/actions/workflows/docs.yaml/badge.svg"/>
  <a href="https://opensource.org/licenses/BSD-3-Clause">
  <img alt="license" src="https://img.shields.io/badge/License-BSD_3--Clause-blue.svg"/>
  </a> 
  <a href="https://pepy.tech/project/salesforce-lavis">
  <img alt="Downloads" src="https://pepy.tech/badge/salesforce-lavis">
  </a>
</div>

<div align="center">
<a href="https://opensource.salesforce.com/LAVIS//latest/benchmark.html">Benchmark</a>,
<a href="https://arxiv.org/abs/2209.09019">Technical Report</a>,
<a href="https://opensource.salesforce.com/LAVIS//latest/index.html">Documentation</a>,
<a href="https://github.com/salesforce/LAVIS/tree/main/examples">Jupyter Notebook Examples</a>,
<a href="https://blog.salesforceairesearch.com/lavis-language-vision-library/">Blog</a>
</div>

# LAVIS - A Library for Language-Vision Intelligence

## What's New: 🎉 
  * [Model Release] November 2023, released implementation of **X-InstructBLIP** <br>
  [Paper](https://arxiv.org/pdf/2311.18799.pdf), [Project Page](https://github.com/salesforce/LAVIS/tree/main/projects/xinstructblip), [Website](https://artemisp.github.io/X-InstructBLIP-page/), [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/salesforce/LAVIS/blob/main/projects/xinstructblip/demo/run_demo.ipynb)
  > A simple, yet effective, cross-modality framework built atop frozen LLMs that allows the integration of various modalities (image, video, audio, 3D) without extensive modality-specific customization.
  * [Model Release] July 2023, released implementation of **BLIP-Diffusion** <br>
  [Paper](https://arxiv.org/abs/2305.06500), [Project Page](https://github.com/salesforce/LAVIS/tree/main/projects/blip-diffusion), [Website](https://dxli94.github.io/BLIP-Diffusion-website/)
  > A text-to-image generation model that trains 20x than DreamBooth. Also facilitates zero-shot subject-driven generation and editing.
  * [Model Release] May 2023, released implementation of **InstructBLIP** <br>
  [Paper](https://arxiv.org/abs/2305.06500), [Project Page](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)    
  > A new vision-language instruction-tuning framework using BLIP-2 models, achieving state-of-the-art zero-shot generalization performance on a wide range of vision-language tasks.
  * [Model Release] Jan 2023, released implementation of **BLIP-2** <br>
  [Paper](https://arxiv.org/abs/2301.12597), [Project Page](https://github.com/salesforce/LAVIS/tree/main/projects/blip2), [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/salesforce/LAVIS/blob/main/examples/blip2_instructed_generation.ipynb)
  > A generic and efficient pre-training strategy that easily harvests development of pretrained vision models and large language models (LLMs) for vision-language pretraining. BLIP-2 beats Flamingo on zero-shot VQAv2 (**65.0** vs **56.3**), establishing new state-of-the-art results on the VQA benchmark.
</div>

Related project: [BLIP](https://github.com/salesforce/BLIP)