### Education
- **Ph.D. in Electrical and Computer Engineering** (Aug. 2012 ~ Aug. 2018) </br>
*The University of Arizona*
- **B.S. in Electrical and Information Enigneering** (Sept. 2008 ~ Jul. 2012)</br>
*Tianjin Polytechnic University*

### Summary
- **Research**: design, prototype, and implement health-care monitoring systems, biomedical applications using machine learning and signal/image processing.
- **Skills**: Tensorflow, OpenCV, scikit-learn; design and implement machine learning based models (preprocessing ,data augmentation, hyper-parameter tuning, postprocessing); image/signal processing: compressive sensing, adaptive filtering, bilateral filtering, etc.

### Programming
- **Python**： Tensorflow, scikit-learn, OpenCV, scikit-image, numpy, scipy, matplotlib.
- **JAVA**： Android development for wearable sensor health-care monitoring system.

### Projects
- **Cell nuclei detection and segmentation**: (Python: Tensorflow, OpenCV, scikit-image, scikit-learn) </br>
  - Implemented U-net base model to detect location and boundary of neclei in H&E stained microscopy images;
  - Customized loss function to include edge enhancement;
  - Implemented overlapping patch based strategy;
  - Implemented post processing for calculating nuclei center and enhance boundary detection;
- **Multi-sensor signal fusion for neurological activity estimation**: (Python: Tensorflow, scikit-learn)</br>
  - Proposed and implemented a multi-sensor signal fusion model (CNN, RNN) to estimate human neurological activity (data: 3D accelerometer, skin temperature, GSR, SpO2, and heart rate).
  - Evaluate model using wrist wearable sensor data.
- **Heartbeat classification based ECG monitoring system prototype**: (Python: Tensorflow, scikit-learn) </br>
  - Implemented neural network based heartbeat model (identify 8 types of beats).
  - Implemented R peak detection algorithm.
- **Stress management App on Android**: (JAVA) </br>
  - Developed an App that communicates with wearable sensor (Zephyr Biopatch) to receives signals (ECG, HR, posture, activity level, respiration).
  - Implemented real-time stress level monitoring using HRV.
  - Implemented animation for paced breathing exercise based relaxation when over-stress detected and terminate animation when user relaxed.
- **ECG noise removal for wearable sensor**
  - Implemented noise generator (baseline wandering, instrument noise, powerline interference, muscle noise in MATLAB).
  - Implemented wavelet transform based noise removal (MATLAB).
  - Implemented autoencoder based noise removal (Python, tensorflow).
- **Image de-noising and inpainting using sparse coding (dictionary learning)**: (MATLAB) </br>
  - Impelmented dictionary learning based model to find the sparse domian (a domain with minimal number of non-zero coefficients).
  - Implemented sparse domain denoising for images recovery process.
- **Compressive sensing based compression and noise removal for fluorescence microbial instrument**: (MATLAB) </br>
  - Implemented compressive sensing in DCT domain.
  - Implemented error tolerance based noie removal in recovering DCT coefficients.
