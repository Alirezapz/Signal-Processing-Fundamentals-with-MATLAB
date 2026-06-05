# DSP Lab Experiment 1: Signal Analysis, Noise, and Convolution

## 📌 Overview

This project is a comprehensive Digital Signal Processing (DSP) laboratory experiment implemented in MATLAB. It explores the fundamental concepts of signal generation, discrete and continuous representation, noise modeling, and filtering using convolution.

The experiment is structured step-by-step to build a deep understanding of how signals behave in real-world scenarios and how signal processing techniques improve signal quality.

---

## 🎯 Objectives

* Understand continuous vs discrete signals
* Learn signal visualization techniques
* Analyze the effect of noise on signals
* Implement convolution manually and using MATLAB
* Apply filtering techniques to reduce noise
* Interpret results in both time domain and visually

---

## 🧩 Project Sections

### 🔹 1. Signal Generation

* Creation of a sinusoidal signal using:

  * Amplitude (A)
  * Frequency (f)
  * Time vector (t)
* Mathematical representation:

  x(t) = A sin(2πft)

---

### 🔹 2. Continuous-Time Visualization

* Plotting the signal using `plot`
* Smooth representation of the waveform
* Understanding signal behavior over continuous time

---

### 🔹 3. Discrete-Time Representation

* Sampling the signal
* Visualization using `stem`
* Observing differences between continuous and sampled signals

---

### 🔹 4. Sampling Analysis

* Effect of sampling rate on signal quality
* Demonstration of:

  * Proper sampling
  * Under-sampling (aliasing concept)

---

### 🔹 5. Noise Addition

* Adding random noise to the signal:

  x_noisy = x + noise

* Typically Gaussian or uniform noise

* Visualization of noisy vs clean signal

---

### 🔹 6. Noise Impact Analysis

* Observing distortion caused by noise
* Comparing:

  * Original signal
  * Noisy signal
* Understanding real-world signal corruption

---

### 🔹 7. Convolution Implementation

* Applying convolution using MATLAB:

  y[n] = x[n] * h[n]

* Using `conv()` function

* Understanding LTI system behavior

---

### 🔹 8. Moving Average Filter

* Designing a simple smoothing filter:

  h[n] = (1/N)[1 1 1 ... 1]

* Reduces high-frequency noise

* Acts as a low-pass filter

---

### 🔹 9. Signal Filtering

* Applying filter to noisy signal:

  y = conv(x_noisy, h)

* Comparing:

  * Noisy signal
  * Filtered signal

---

### 🔹 10. Result Visualization

* Plotting:

  * Original signal
  * Noisy signal
  * Filtered signal
* Side-by-side comparison

---

### 🔹 11. Performance Analysis

* Observing smoothing effect
* Trade-offs:

  * Noise reduction vs signal distortion
* Effect of filter length (N)

---

## 📊 Results & Observations

* Noise significantly distorts the original signal
* Convolution with a moving average filter smooths the signal
* Increasing filter length improves noise reduction but may blur the signal
* Proper sampling is critical to avoid aliasing

---

## 🛠️ Tools & Technologies

* MATLAB (.mlx Live Script)
* Signal Processing Techniques

---

## 📁 File Structure

* `DSPL_EXP1_40023096.mlx` → Main MATLAB Live Script
* Figures generated within script

---

## ▶️ How to Run

1. Open MATLAB
2. Load the `.mlx` file
3. Run each section sequentially
4. Analyze plots and outputs

---

## 🧠 Key Learnings

* Practical understanding of DSP fundamentals
* Visualization of signal transformations
* Real-world insight into noise and filtering
* Hands-on experience with convolution

---

## 🚀 Future Improvements

* Implement advanced filters (FIR/IIR)
* Frequency domain analysis (FFT)
* Real-time signal processing
* GUI-based visualization

---

## 👤 Author

Alireza Pazooki

---

## 📌 Notes

This project was developed as part of a DSP laboratory course and is intended for educational purposes to reinforce theoretical concepts through practical implementation.
