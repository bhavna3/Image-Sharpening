# Image Sharpening using Gradient Operators in MATLAB

This MATLAB project demonstrates how to capture an image using a webcam, apply gradient operators (like the Sobel filter) to compute the image gradients, and use these gradients to sharpen the image.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Example Output](#example-output)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project captures an image from a connected webcam and applies image processing techniques to enhance its sharpness. The sharpening is done using gradient operators, specifically the Sobel operator, which highlights the edges and fine details of the image.

## Requirements

- MATLAB (R2014a or later)
- Image Processing Toolbox
- A connected webcam

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/webcam-image-sharpening.git
   cd webcam-image-sharpening

2. **Open MATLAB:**

   Open MATLAB and navigate to the cloned repository folder.

3. **Ensure Your Webcam is Properly Connected:**

   Make sure your webcam is connected and recognized by MATLAB.

## Usage

1. **Run the Script:**

   Execute the `webcam_image_sharpening.m` script in MATLAB.

   ```matlab
   webcam_image_sharpening

2. **Capture Image**

    The script will initialize the webcam and capture an image.

3. **Image Processing**

    The script converts the captured image to grayscale, applies the Sobel operator to compute gradients, and enhances the image by sharpening it using the gradient magnitude.

4. **Display Results**

    The original grayscale image, the gradient magnitude, and the sharpened image will be displayed side by side.

## Example Output



