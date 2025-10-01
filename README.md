# Experiment-and-modifications-AMAD
The repository is consiting of mixed optimization strategy for Explicit Boundary Guided Semi-Push-Pull Contrastive Learning for Supervised Anomaly Detection on MVTECAD dataset. 
A small Experiment for implementing **new loss functions** in place of **log likelihood** from work done by Yao at. el.
Implementation of new loss functions has given good performance on few classes of datasets over complete MVTECAD. It is because of the noise and similarity being left out from image frame.

## Anomaly Detection Experiments

This repository contains code for anomaly detection experiments using different loss functions, including KL divergence, Wasserstein, and Cross-Entropy loss.

### Original Repository

This code is based on the work from ([https://github.com/xcyao00/BGAD.git]).
@article{BGAD,
      title={Explicit Boundary Guided Semi-Push-Pull Contrastive Learning for Supervised Anomaly Detection}, 
      author={Xincheng Yao and Ruoqi Li and Jing Zhang and Jun Sun and Chongyang Zhang},
      year={2023},
      booktitle={Conference on Computer Vision and Pattern Recognition 2023},
      url={https://arxiv.org/abs/2207.01463},
      primaryClass={cs.CV}
}

Use the above work as follows:
- Download the repository mentioned above
- Download my repository and place in the BGAD folder from previous step
- use the _init_.py and use different types of opotimization to achieve BGAD based optimization of anolamoly detection on MVTEC AD dataset (Industry standard dataset).
