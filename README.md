# Deep Learning Lab: Traffic Sign Recognition System

This repository contains the coursework, assignments, and the final project developed for the Deep Learning Lab. The core focus of this repository is the development of a robust **Traffic Sign Recognition (TSR)** system using Deep Learning techniques.

---

## Main Project: Traffic Sign Recognition (Classification)

The primary objective of this project is to build a high-accuracy classification model capable of identifying 43 different types of traffic signs from the **GTSRB (German Traffic Sign Recognition Benchmark)**.

### Project Overview
In autonomous driving, the vehicle must not only detect that a sign exists but also understand its specific meaning (e.g., distinguishing between a 30km/h and 80km/h zone). This project implements a **Convolutional Neural Network (CNN)** to process cropped traffic sign images and classify them into their respective categories.

**Key Challenges addressed:**
* **Class Imbalance:** Managing datasets where some signs (Speed Limits) are more frequent than others (Bumpy Roads).
* **Environmental Variance:** Training the model to handle motion blur, low lighting, and weather conditions.
* **Real-time Constraints:** Optimizing the model architecture for fast inference.

---