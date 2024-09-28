# Diffusion-Based Image Restoration: A Zero-Shot Approach
---
There is a need for high-quality images in various applications, such as medical
imaging, remote sensing, and surveillance. The problem of image restoration is to
recover a high-quality image from a degraded observation. The degradation can be
caused by various factors, such as noise, blur, or missing pixels. Traditional image
restoration methods often require task-specific training and cannot generalize to
different types of degradation. The core part of the problem is to design a generic
restoration model that can effectively remove the degradation and recover the original
image for variety of degradation. This project is based on one of the solutions
provided by the DDNM paper - "Zero-Shot Image Restoration Using Denoising
Diffusion Null-Space Model" [] The performance of the proposed method is compared
after applying it on pre-trained as well as self- trained diffusion models for
an image inpainting task using evaluation metrics like Peak Signal-to-Noise Ratio
(PSNR) and Structural Similarity Index (SSIM). The dataset used for self-trainig
and evaluation is the DREAMING - Diminished Reality for Emerging Applications
in Medicine through Inpainting Dataset provided as part of DREAMING 2024
Grand challenge by IEEE ISBI 2024.[]

---
