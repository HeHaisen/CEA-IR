# CEA-IR

**Continuous Expert Assembly for All-in-One Image Restoration**

### Instance-Conditioned Low-Rank Residuals for All-in-One Image Restoration

**Coming soon.** Code, pretrained models, and reproduction instructions are being prepared for public release.

This repository is being prepared to host the implementation of:

> **Continuous Expert Assembly: Instance-Conditioned Low-Rank Residuals for All-in-One Image Restoration**
> Haisen He, Xiangyu Zou, SongLin Dong, Heng Li, Yihong Gong, and Zhiheng Ma

## Overview

Continuous Expert Assembly (CEA) is an instance-conditioned low-rank parameterization framework for all-in-one image restoration. It is designed to handle unknown, spatially varying, and compositional image degradations without requiring degradation labels at inference time.

A lightweight **Cross-Attention Hyper-Adapter** probes intermediate spatial features to generate low-rank routing bases and residual directions. These factors are shared across spatial tokens within each layer and target projection, while token features produce dense signed coefficients and token-dependent residual responses.

The accompanying work studies CEA on **AIO-3**, **AIO-5**, **CDD-11**, and real-captured adverse-weather images from **WeatherBench**.

## Release status

This repository currently contains release information only. The implementation, model weights, and runnable examples are not yet available here.

Planned release contents:

- [ ] CEA model implementation
- [ ] Environment setup and dependency instructions
- [ ] Dataset preparation guides
- [ ] Training and evaluation configurations
- [ ] Pretrained model checkpoints
- [ ] Inference examples and reproducibility instructions

## Paper and citation

The public paper link and citation details will be added when available.

## License

A license will be specified with the public release. No license for the forthcoming code or model weights is granted by this placeholder repository.
