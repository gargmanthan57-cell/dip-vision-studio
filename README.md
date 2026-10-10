DIP Vision Studio

Digital Image Processing Project

DIP Vision Studio is a browser-based Digital Image Processing (DIP) application for experimenting with image enhancement, document scanning, photo restoration, and pixel-level image operations. It uses HTML, CSS, JavaScript, and the browser Canvas API to process images locally.

🌐 Live Project

"Open DIP Vision Studio" (https://dip-vision-studio-being-serious-this-time.vercel.app)

📄 Project Resources

- "Final Project Report" (https://drive.google.com/file/d/1myqf4l4rFvYX5Xif4orrN29Es16X0Y58/view?usp=drivesdk)
- "Project Presentation (PPTX)" (https://drive.google.com/file/d/1PYH7CC-Gbug7K30s64-7Y2h85t-LPqtr/view?usp=drivesdk)
- "GitHub Repository" (https://github.com/gargmanthan57-cell/dip-vision-studio)

🎯 Problem Statement

To design and develop an interactive, browser-based Digital Image Processing system that enables users to upload images, apply processing and enhancement techniques, analyze pixel-intensity distributions, compare results, and download processed images.

🚀 Project Features

1. Document Scanner

- Upload document photographs.
- Choose black-and-white, grayscale, or color output.
- Adjust brightness, contrast, and threshold.
- Enhance, reset, and download results as PNG.
- Compare original and processed images using a before/after slider.

2. Photo Restoration

- Adjust brightness, contrast, and saturation.
- Apply denoising and sharpening.
- Experiment with scratch repair and dirt cleanup.
- Use Auto Restore or customize settings manually.
- Reset, compare, and download restored images.

3. Classic DIP Tools

- Grayscale conversion.
- Image thresholding.
- Image inversion.
- Sobel-style edge detection.
- Blur and sharpening operations.
- Reset and download processed images.
- Before/after comparison slider.

4. Histogram Analyzer

- Visualize grayscale intensity distributions.
- Analyze red, green, and blue channels individually or together.
- View pixel count, mean brightness, and grayscale intensity range.
- Apply histogram equalization to remap grayscale intensities.
- Apply contrast stretching to expand the intensity range.
- Reset images and download processed PNG files.

🔬 DIP Techniques Demonstrated

Technique| Description
Grayscale Conversion| Converts color pixels to grayscale using weighted RGB intensity values.
Thresholding| Classifies pixels according to an intensity threshold.
Sobel-Style Edge Detection| Highlights areas with significant intensity changes using image gradients.
Blur| Smooths image details and reduces some high-frequency variations.
Sharpening| Emphasizes local differences to enhance edges and details.
Brightness and Contrast| Adjusts pixel intensity and tonal separation.
Denoising and Cleanup| Demonstrates neighborhood-based operations intended to reduce noise and unwanted marks.
Histogram Analysis| Displays the distribution of pixel intensity values.
Histogram Equalization| Uses the cumulative intensity distribution to remap grayscale values and may improve contrast.
Contrast Stretching| Expands the observed intensity range to use more of the available tonal range.
Document Enhancement| Uses tonal adjustment and thresholding to improve document appearance.
Before/After Comparison| Enables visual inspection of original and processed images.

🛠️ Technologies Used

- HTML5 — Page structure
- CSS3 — Responsive layout and styling
- JavaScript — Processing algorithms and interface controls
- Canvas API — Image rendering and manipulation
- ImageData API — Reading and modifying pixel data
- Vercel — Deployment and hosting

📊 Project Workflow

Input Image
    ↓
Image Upload
    ↓
Canvas Rendering
    ↓
Pixel Data Extraction
    ↓
Selected DIP Operation
    ↓
Image Enhancement / Histogram Analysis
    ↓
Before-and-After Inspection
    ↓
Download Processed Image

💡 Applications

- Educational demonstrations of digital image processing
- Basic photo enhancement and restoration
- Document image cleanup and scanning
- Pixel-intensity and color-channel analysis
- Histogram and contrast-enhancement experiments
- Introductory computer-vision concepts

⚠️ Limitations

- This project is intended for academic learning and demonstration.
- Large images may be resized for smoother processing.
- Enhancement results depend on the input image and selected settings.
- Automated restoration cannot guarantee recovery of missing image details.
- Histogram equalization and contrast stretching may not improve every image.
- The project is not intended as a professional restoration system or safety-critical application.

🔮 Future Scope

- Advanced image segmentation and region selection
- Frequency-domain filters, including Fourier-based processing
- Improved noise removal and restoration algorithms
- Object detection and machine-learning-based image analysis
- Real-time camera input and video processing
- Additional image-quality metrics and export options

📚 References

- "MDN Canvas API" (https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- "MDN ImageData" (https://developer.mozilla.org/en-US/docs/Web/API/ImageData)
- "MDN getImageData()" (https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/getImageData)
- "MDN Pixel Manipulation with Canvas" (https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Pixel_manipulation_with_canvas)
- "OpenCV Sobel Derivatives" (https://docs.opencv.org/4.10.0/d2/d2c/tutorial_sobel_derivatives.html)

🔗 Project Links

- Live Website: https://dip-vision-studio-being-serious-this-time.vercel.app
- GitHub Repository: https://github.com/gargmanthan57-cell/dip-vision-studio
- Project Report: https://drive.google.com/file/d/1myqf4l4rFvYX5Xif4orrN29Es16X0Y58/view?usp=drivesdk
- Project Presentation: https://drive.google.com/file/d/1PYH7CC-Gbug7K30s64-7Y2h85t-LPqtr/view?usp=drivesdk

👥 Project Team

Name| Registration Number
Manthan Garg| 10324210150
Aryan Chaudary| 10324210134
Satyansh Verma| 10324210133
Dhruv Gupta| 10324210152

---

Digital Image Processing — DIP Vision Studio
