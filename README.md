# Image Compression using Sparse Matrix Multiplication  
**Hackathon:** Thread Masters – Threads in Parallel Programming  
**Dates:** 12.04.2025 – 13.04.2025  

---

## Problem Statement

Develop a **sparse matrix multiplication algorithm** for image compression that efficiently reduces image size while preserving quality. The solution must leverage **parallel computing** (CPU & GPU) to accelerate processing time.

---

## Project Description

This project demonstrates a **block-wise SVD compression** approach using **sparse matrices (CSR)** and compares performance across:

-  Serial CPU (NumPy)
-  Multithreaded CPU (PyTorch)
-  GPU (CuPy)

We evaluate image quality using **PSNR** and **SSIM**, and also track memory efficiency and execution time.

---

## How to Run the Project

1. Click here to open the notebook in 
[Google Colab](https://colab.research.google.com/github/RAMYA-M-08/image_compression_parallel_computing/blob/main/Image_Compression.ipynb)
2. Go to `Runtime > Change runtime type`
3. Set **Hardware accelerator** to `GPU` and click **Save**
4. Run all cells via `Runtime > Run all` 


