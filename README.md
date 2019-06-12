# Compare CPU with GPU using MXNet and Colab

Construct two 4096*4096 matrices, then do multiplication on both CPU and GPU. Compare the time it costs.

1. In Google Colab, use  **`!nvcc --version`** to make sure that MXNet version matches the CUDA.
1. Since the numpy in Colab is not compatible with MXNet, we need to **`!pip uninstall numpy`** and then **`!pip install numpy==1.14.6`**.
