### Basic Server Information
**WALTER**
- CPU: i7-6850K @ 3.60GHz
  - Cores: 6
  - Threads: 12
- RAM: 32 GB
- GPU: RTX 2080 Ti (11 GB) + RTX 2070 (8 GB)

**PLASTER**
- CPU: i7-5960X @ 3.00GHz
  - Cores: 8
  - Threads: 16
- RAM: 128 GB
- GPU: 3 × GTX 1080 Ti (11 GB)

### CUDA 13 Compatibility Notice
"Architecture support for Maxwell, Pascal, and Volta is considered feature-complete. Offline compilation and library support for these architectures have been removed in CUDA Toolkit 13.0 major version release. The use of CUDA Toolkits through the 12.x series to build applications for these architectures will continue to be supported, but newer toolkits will be unable to target these architectures."\
[Source](https://docs.nvidia.com/cuda/cuda-toolkit-release-notes/index.html#deprecated-architectures)

**Important:** Our GTX 1080 Ti GPUs are based on the Pascal microarchitecture.\
**Recommendation:** Choose CUDA 12.x as the Compute Platform when [installing PyTorch](https://pytorch.org/get-started/locally/).
