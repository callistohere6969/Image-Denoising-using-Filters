Image Denoising Using MATLAB
This repository contains the code, report, and data for the Image Denoising project developed using MATLAB. The project explores and implements various image denoising filters to enhance image quality by reducing different types of noise (e.g., Gaussian, salt-and-pepper, speckle).

Features
Implementation of multiple filters:
Adaptive Riesz Mean Filter
Alpha Trimmed Mean Filter
Geometric Mean Filter
Median Filters (Basic and Modified)
Sector Rotation Filter
Recursive Spline Interpolation Filter
Performance evaluation of filters using metrics like Peak Signal-to-Noise Ratio (PSNR).
Comparison of filter effectiveness for various noise types and intensities.
Project Structure
CODE_COMPILATION.docx: Detailed MATLAB code for all implemented filters.
final report.docx: Comprehensive report explaining algorithms, flowcharts, and results.
Excel_filters_final.xlsx: Performance data and PSNR values for all filters across different noise types.
Getting Started
Prerequisites
MATLAB installed on your system.
Basic understanding of image processing concepts.
Running the Code
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/image-denoising-matlab.git
Open MATLAB and navigate to the repository folder.
Load your noisy image into the workspace.
Run the filter scripts provided in the code file.
Example
Here's a sample usage for the Basic Median Filter:

matlab
Copy code
% Load noisy image
noisy_image = imread('noisy_image.png');

% Apply Basic Median Filter
denoised_image = basic_median_filter(noisy_image);

% Display results
imshow(denoised_image);
Results
The filters were tested on various types of noise, including:

Salt-and-Pepper Noise
Gaussian Noise
Speckle Noise
Key Finding: Adaptive Riesz Mean Filter and Alpha Trimmed Mean Filter consistently provided the best results for high-density noise removal.

Contributors
Chaitanya
License
This project is licensed under the MIT License. See the LICENSE file for details.
