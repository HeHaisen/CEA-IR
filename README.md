<div align="center">

# CEA-IR

### Continuous Expert Assembly<br>Instance-Conditioned Low-Rank Residuals for All-in-One Image Restoration

<p>
  Haisen He<sup>1</sup> &nbsp;·&nbsp;
  Xiangyu Zou<sup>2</sup> &nbsp;·&nbsp;
  SongLin Dong<sup>3</sup> &nbsp;·&nbsp;
  Heng Li<sup>3</sup> &nbsp;·&nbsp;
  Yihong Gong<sup>4</sup> &nbsp;·&nbsp;
  Zhiheng Ma<sup>3,*</sup>
</p>

<p>
  <sup>1</sup>Southern University of Science and Technology<br>
  <sup>2</sup>Shenzhen University &nbsp;·&nbsp;
  <sup>3</sup>Shenzhen University of Advanced Technology<br>
  <sup>4</sup>Xi'an Jiaotong University<br>
  <sub>* Corresponding author</sub>
</p>

<p>
  <a href="https://arxiv.org/abs/2605.06127"><img src="https://img.shields.io/badge/arXiv-2605.06127-B31B1B?style=flat-square" alt="arXiv: 2605.06127"></a>
  <a href="https://arxiv.org/pdf/2605.06127"><img src="https://img.shields.io/badge/Paper-PDF-2563EB?style=flat-square" alt="Read the paper PDF"></a>
  <a href="#release-status"><img src="https://img.shields.io/badge/Code-Coming%20soon-D97706?style=flat-square" alt="Code: coming soon"></a>
</p>

**Image-conditioned components. Token-dependent restoration.**

[Overview](#overview) · [Release status](#release-status) · [Citation](#citation)

</div>

---

> [!NOTE]
> **Coming soon.** We are preparing the code, pretrained models, and reproduction instructions for release. This repository currently serves as the project landing page.

## Overview

**Continuous Expert Assembly (CEA)** adapts a shared image restoration backbone to unknown, spatially varying, and compositional degradations, without requiring degradation labels at inference time.

A lightweight **Cross-Attention Hyper-Adapter** probes intermediate spatial features and generates low-rank routing bases and residual directions. Each spatial token combines these image-conditioned components through dense signed coefficients to produce its own residual response.

| Component | Role |
| :--- | :--- |
| **Spatial probing** | Learnable queries extract degradation-relevant information from intermediate features. |
| **Dynamic low-rank factors** | Compact routing bases and residual directions are generated for each input. |
| **Continuous assembly** | Spatial tokens combine the generated components through dense signed affinities. |

The work evaluates restoration on **AIO-3**, **AIO-5**, and **CDD-11**, with additional evaluation on real-captured **WeatherBench** images in the accompanying manuscript.

## Release status

| Resource | Status |
| :--- | :--- |
| Paper | [Available on arXiv](https://arxiv.org/abs/2605.06127) |
| Model implementation | Coming soon |
| Pretrained checkpoints | Coming soon |
| Training and evaluation configurations | Coming soon |
| Setup, dataset preparation, and inference guides | Coming soon |

## Citation

If you find this work useful in your research, please consider citing our paper:

```bibtex
@misc{he2026continuousexpertassembly,
  title         = {Continuous Expert Assembly: Instance-Conditioned Low-Rank Residuals for All-in-One Image Restoration},
  author        = {Haisen He and Xiangyu Zou and SongLin Dong and Heng Li and Yihong Gong and Zhiheng Ma},
  year          = {2026},
  eprint        = {2605.06127},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV},
  doi           = {10.48550/arXiv.2605.06127},
  url           = {https://arxiv.org/abs/2605.06127}
}
```

## License

License information for the code and model weights will accompany the public release.
