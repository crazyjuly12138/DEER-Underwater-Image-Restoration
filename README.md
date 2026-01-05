# DEER: Diffusion-Empowered Efficient Restoration for Underwater Images


**Authors**: Cheng Wang, Junyang Chen, Weichen Zhao, Wanhui Zhao and Ge Jiao.

---
>**Abstract:** Underwater images suffer from severe degradation caused by light attenuation and noise interference. 
> Existing methods struggle to achieve a balance between performance and inference efficiency. 
> To address this problem, we propose a Diffusion-Empowered Efficient Restoration (DEER) framework, 
> comprising an enhancement network and a restoration network. The former incorporates two key modules: 
> the High-Frequency Detail Enhancement (HFDE) module introduces a min-pooling channel to recover dark 
> details suppressed by medium absorption, complementing max-pooling and average-pooling to capture 
> comprehensive physical edge characteristics; meanwhile, the Multi-Scale Fusion (MSF) module utilizes 
> multi-scale analysis to address the spatial non-uniformity of color casts. Collectively, they provide 
> rich frequency-domain priors for the subsequent restoration. Regarding the latter, unlike previous 
> approaches that directly utilized a diffusion model for generation, we employ it as a structured prior 
> discriminator. By providing dynamic gradient guidance during the training phase, the lightweight network
> learns the natural image manifold while avoiding smoothing artifacts induced by pixel-wise mimicry. 
> During inference, the diffusion model is discarded, allowing the lightweight restoration model to achieve 
> accelerated inference. Experimental results demonstrate that DEER outperforms state-of-the-art approaches
> , achieves improvement of 0.7% ~ 5.6% across nearly all metrics on the LSUI and UIEB datasets. 
<hr />

![Visual Comparison with SOTA Methods](Figure1.jpg)

##  Requirements
To install requirements:

```setup
pip install -r requirements.txt
```


## 📢 News / Updates
*   **[2026-01-5]**: The repository is created.
*   **[Status]**: The code is currently being refactored for readability. **The full source code will be released immediately upon the acceptance of the paper.**


