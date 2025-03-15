# Enhancing Deepfake Detection Through Hybrid MobileNet-LSTM Model

This repository contains the code, documentation, and results for a project focused on enhancing deepfake detection using a hybrid MobileNet-LSTM model.  The project aims to create a robust and efficient system capable of identifying deepfakes in both images and videos.

## Table of Contents

*   [Project Overview](#project-overview)
*   [Features](#features)
*   [Methodology](#methodology)
*   [Architecture](#architecture)
*   [Results](#results)
*   [Future Enhancements](#future-enhancements)
*   [Publications](#publications)
*   [Setup](#setup)


## Project Overview

The increasing sophistication of deepfake technology poses a significant challenge to the authenticity and security of digital media. This project introduces a novel hybrid approach that combines the strengths of MobileNet V3 and Long Short-Term Memory (LSTM) networks to create a more accurate and efficient deepfake detection system. This system has applications in the battle against misinformation, by ensuring that the correct data is reported. The project addresses the challenges related to this problem, and offers a user-friendly interface in the app.

## Features

*   **Hybrid MobileNet-LSTM Architecture:** Combines the efficient feature extraction of MobileNet with the temporal analysis capabilities of LSTM networks.
*   **Image and Video Support:**  The system can analyze both static images and video files for deepfake content.
*   **Real-Time Processing:** Designed for efficient computation, enabling real-time detection.
*   **Key Frame Analysis:** Extraction of key frames from videos for deeper analysis.
*   **Confidence Scoring:** Provides a confidence score to indicate the reliability of the detection.
*   **User-Friendly Interface:** Uses Streamlit to create an intuitive and accessible interface.
*   **Cloud/Local Storage:** Option to save processed data, results, and metadata for future analysis.
*   **Temporal Smoothing**: Ability to smooth video data for more accurrate results

## Methodology

The project follows a structured methodology that includes the following steps:

1.  **Data Collection:** Gathering a diverse dataset of real and deepfake images and videos from various sources. The data is sourced from a well-known Kaggle library.
2.  **Preprocessing:** Resizing, normalizing, and augmenting the data to improve model performance and robustness.
3.  **Feature Extraction:** Using MobileNet V3 to extract spatial features from images and video frames.
4.  **Temporal Analysis:** Using LSTM networks to analyze the temporal coherence of video sequences.
5.  **Classification:**  Employing a classification layer to determine whether the input content is genuine or a deepfake.
6.  **Training and Evaluation:** Training the hybrid model and evaluating its performance using appropriate metrics.

## Architecture

<img src="https://github.com/user-attachments/assets/bcd5bd6d-fa6a-4c65-a6ac-f3206e56ec22" width="300px" height="400px" />

The system architecture consists of the following components:

1.  **Input:** Accepts static images and video files.
2.  **Preprocessing:** Normalization and resizing.
3.  **MobileNet Feature Extraction:** Extracts spatial features.
4.  **LSTM:** Analyzes temporal patterns.
5.  **Classification Layer:** Classifies the input as real or fake.
6.  **Real-time Processing Pipeline**
7.  **Cloud/local Storage**
8.  **Alerts and Reporting**
9.  **User**

## Results

The hybrid MobileNet-LSTM model achieves superior performance compared to baseline models. Key results include:

*   **Accuracy:** 91.8%
*   **Precision:** 89.4%
*   **Recall:** 90.5%
*   **F1-Score:** 89.9%
  
<img src="https://github.com/user-attachments/assets/27cf1ff1-dad9-4a74-8dc8-486bca8d62ac" width="700px" height="250px" />

## Future Enhancements

Future enhancements for this project include:

*   Integration of multimodal inputs (audio and text).
*   Implementation of online training and transfer learning.
*   Development of pruning techniques for improved mobile device performance.
*   Enhancement of model interpretability through advanced visualization.
*   Implementation of adversarial training to strengthen robustness.

## Publications

*   V. S. Anandhasivam, A. K. Anusri, M. Logeshwar, and R. Gopinath, “Enhancing Deepfake Detection Through Hybrid MobileNet-LSTM Model with Real-Time Image and Video Analysis," 4th International Conference on Ubiquitous Computing and Intelligent Information Systems (ICUIS), pp. 1989-1995, Dec. 2024, doi: 10.1109/icuis64676.2024.10867159.

  
  🚀 <a href="https://xploreqa.ieee.org/document/10867159" target="_black">Click here to view the IEEE Conference Paper</a>

## Setup

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/AnandhaSivam-00/Enhancing-Deepfake-Detection-using-MobileNet-LSTM-Hybrid-Model.gitnd
    cd [repository_directory]
    ```

2.  **Install the required dependencies:**
   
     ```bash
     pip install -r requirements.txt
     ```
3. **Run the Project**
   
   ```bash
   python -m streamlit run app.py
   ```

## NOTE
1. Must install all the required packages above (in requirements.txt)
2. Python version == 3.10

***********************  All rights reserved by ANANDHASIVAM V S - (Anandhasivam Sambathkumar) ***********************
