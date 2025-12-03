# PycWB-Tutorial

Mybinder link: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/xuyumeng/PycWB-Tutorial/HEAD)

Coherent WaveBurst (cWB) is a long-established gravitational-wave detection algorithm that has contributed significantly to LIGO–Virgo–KAGRA discoveries of transient sources. However, its monolithic C++ implementation can be a barrier for new researchers and further complex studies. In this tutorial, we introduce PycWB, a modular Python reimplementation of the core cWB pipeline, designed to make unmodeled searches more accessible, transparent, and extensible.

Through this hands-on tutorial, participants will: (1) Explore the time–frequency domain with wavelet transforms for different sources.  (2) Reproduce the first detected event, GW150914, with a step-by-step guide to understand the search process. (3) Assess detection significance using background estimation with time slides, illustrated with GW231123 data. (4) Learn advanced usage and development, including PycWB’s modular architecture, flexible injection framework, and streamlined post-processing tools.

## Outline of the tutorial

1. Dive into the time frequency domain: step by step
    1. Time frequency domain with WDM
    2. Find the pixels with coherent excess energy
    3. Likelihood, distinguish between noise and signal
    4. Results interpretation / waveform reconstruction 
2. Step-by-step search: Uncover the very first event GW150914
3. Measure the Statistical Significance: example of GW231123
    1. Background estimation with time slides
    2. Measure the statistical significance of the detection
4. Advanced topics: Stress-free development with PycWB
    1. Modular design
    2. Flexible injection framework
    3. Streamlined post-processing framework

## How to use this tutorial

This tutorial is designed to be run on [Mybinder](https://mybinder.org/), which allows you to execute Jupyter notebooks in a cloud environment without any local installation. Simply click the Mybinder link at the top of this README to launch the tutorial.

Due to the limitation of the memory resources on Mybinder, some steps in the tutorial use precomputed data. For a complete experience, you can clone the repository and run the notebooks on your local machine with sufficient memory (>=6GB recommended). To install pycwb, please refer to the [PycWB Gitlab repository](https://git.ligo.org/yumeng.xu/pycwb#installation). Note that for MacOS with Apple Silicon, you will need to install pycwb in a conda environment with x86 architecture as described in the installation instructions.


