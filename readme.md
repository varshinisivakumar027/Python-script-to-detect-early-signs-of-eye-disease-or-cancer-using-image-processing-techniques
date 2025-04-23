# 👁️ Eye Disease Detection in Retinal Images using MATLAB

This project uses basic image processing techniques in MATLAB to detect suspicious bright regions in retinal images, which may indicate the presence of eye diseases such as **diabetic retinopathy** or **macular edema**.

## 🧠 What It Does

The script:
- Reads a retinal image
- Converts it to grayscale
- Applies Gaussian blur to reduce noise
- Performs adaptive thresholding to isolate bright lesions
- Removes small noisy regions
- Detects and highlights large bright spots (potential lesions)
- Outputs the result visually and with a medical advisory message
