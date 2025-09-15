<div align="center">

<h1>Spatial Prior-Guided Boundary and Region-Aware 2D Lesion Segmentation in Neonatal Hypoxic Ischemic Encephalopathy</h1>

<h3>MICCAI 2025 🇰🇷</h3>

[Amog Rao]([https://github.com/amograo](https://www.linkedin.com/in/amog-rao/))*<sup>1</sup>, [Ananya Shukla]([https://github.com/ananyashukla](https://www.linkedin.com/in/-ananya-shukla/))*<sup>1</sup>, [Jia Bhargava](https://github.com/jiabhargava)<sup>1</sup>, [Yangming Ou]([https://www.childrenshospital.org/directory/yangming-ou](https://research.childrenshospital.org/researchers/yangming-ou))<sup>2</sup>, [Rina Bao]([https://www.childrenshospital.org/directory/rina-bao](https://baorina.github.io))**<sup>1,2</sup>

<sup>1</sup>Plaksha University, Mohali, India <br>
<sup>2</sup>Boston Children's Hospital, Harvard Medical School, Boston, USA <br>

* Equal Contribution, ** Corresponding Author

[Paper](https://papers.miccai.org/miccai-2025/paper/4455_paper.pdf) | [Dataset]([https://zenodo.org/records/10602767](https://zenodo.org/records/13690270))

</div>

<p align="center">
  <img src="assets/architecture.png" width="90%">
</p>

## Abstract

Segmenting acute and hyper-acute brain lesions in neonatal hypoxic ischemic encephalopathy (HIE) from diffusion-weighted MRI (DWI) is critical for prognosis and treatment planning but remains challenging due to severe class imbalance and lesion variability. 

We propose a computationally efficient 2D segmentation framework leveraging ADC and Z_ADC maps as a three-channel input to UNet++ with an Inception-v4 encoder and scSE attention for enhanced spatial-channel recalibration. To address class critical imbalance and lack of volumetric context in 2D methods, we introduce a novel boundary-and-region-aware weighted loss integrating Tversky, Log-Hausdorff, and Focal losses. 

Our method surpasses state-of-the-art 2D approaches and achieves competitive performance against computationally intensive 3D architectures, securing a DSC of 0.6060, MASD of 2.6484, and NSD of 0.7477. These results establish a new benchmark for neonatal HIE lesion segmentation, demonstrating superior detection of both acute and hyper-acute lesions while mitigating the challenge of loss collapse.

## Citation

If you use this work in your research, please cite:

```bibtex
@InProceedings{RaoAmo_Spatial_MICCAI2025,
  author = {Rao, Amog and Shukla, Ananya and Bhargava, Jia and Ou, Yangming and Bao, Rina},
  title = {{Spatial Prior-Guided Boundary and Region-Aware 2D Lesion Segmentation in Neonatal Hypoxic Ischemic Encephalopathy}},
  booktitle = {proceedings of Medical Image Computing and Computer Assisted Intervention -- MICCAI 2025},
  year = {2025},
  publisher = {Springer Nature Switzerland},
  volume = {LNCS 15963},
  month = {September},
}
```

---

<div align="center">

**Code, pre-trained models, and detailed instructions coming soon!**

</div>
