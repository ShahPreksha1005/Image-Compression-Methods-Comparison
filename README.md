# Image Compression Methods Comparison  

## Overview  
This project implements and compares different image compression methods, evaluating their efficiency and quality using Peak Signal-to-Noise Ratio (PSNR). The compression techniques include:  

- **Huffman Coding**  
- **Run-Length Encoding (RLE)**  
- **Lempel-Ziv-Welch (LZW)**  
- **PNG Compression**  
- **WebP Compression**  
- **JPEG2000 Compression**  
- **Bitplane Slicing**  

The analysis helps understand the trade-offs between compression ratio, image quality, and computational complexity.  

## Features  
- Implementation of various lossless and lossy image compression algorithms.  
- PSNR calculation for quality evaluation.  
- Visualization of compressed images alongside the original image.  
- Comparison of different compression techniques.  

## Dependencies  
Ensure you have the following libraries installed before running the notebook:  
```bash
pip install opencv-python numpy matplotlib pillow scikit-learn scipy
```  

## Usage  
1. Clone the repository.
2. Run the notebook in Google Colab or Jupyter Notebook.  
3. Modify `image_path` to use a different input image.  
4. Execute the notebook to apply compression methods and compare their performance.  

## Results  
- The PSNR values indicate the quality preservation of each compression method.  
- Visual comparison of the original and compressed images provides insights into artifacts and data loss.  
- The efficiency of each algorithm can be analyzed based on compression ratio and runtime.  

---
