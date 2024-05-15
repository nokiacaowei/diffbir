# ComfyUI DiffBIR
---

Comfyui-DiffBIR is a comfyui implementation of offical DiffBIR. 

---

TODO:
- **2024.05.10** ✅ repo create
- **2024.05.11** ✅ sampler implement
- **2024.05.11** ✅ stage2 load implement
- **2024.05.12** ✅ stage1 load implement
- **2024.05.12** ✅ stage1 tile implement
- **2024.05.12** ✅ simple load implement
- **2024.05.12** ✅ sampler update
- **2024.05.12** ✅ sampler advanced
- **2024.05.13** readme update
- [ ] multi images support
- [ ] basic sr workflow
- [ ] fr support
- [ ] bfr support
- [ ] dn support

# Visual Results
Blind Image Super-Resolution
![1_lq](./asset/bsr/1_lq.png) ![1_hq](./asset/bsr/1_hq.png)


# Installing
### Step 1: clone the repo and install the dependencies
`git clone https://github.com/ComfyUI/ComfyUI-DiffBIR`  
`pip install -r requirements.txt`

### Step 2: download the pretrained model
put the model into `Comfyui/models/diffbir/`
|      model     |                                                          download link                                                         | Baidu Netdisk |
|:--------------:|:------------------------------------------------------------------------------------------------------------------------------:|---------------|
|     bsrnet     | [BSRNet.pth](https://github.com/cszn/KAIR/releases/download/v1.0/BSRNet.pth)                                                   |               |
|   swinir_face  | [face_swinir_v1.ckpt](https://huggingface.co/lxq007/DiffBIR/resolve/main/face_swinir_v1.ckpt)                                  |               |
|   scunet_psnr  |          [scunet_color_real_psnr.pth](https://github.com/cszn/KAIR/releases/download/v1.0/scunet_color_real_psnr.pth)          |               |
| swinir_general | [general_swinir_v1.ckpt](https://huggingface.co/lxq007/DiffBIR/resolve/main/general_swinir_v1.ckpt)                            |               |
|       v2       | [v2.pth](https://huggingface.co/lxq007/DiffBIR-v2/resolve/main/v2.pth)                                                         |               |
|     sd_v21     | [v2-1_512-ema-pruned.ckpt](https://huggingface.co/stabilityai/stable-diffusion-2-1-base/resolve/main/v2-1_512-ema-pruned.ckpt) |               |


# Workflows