# Whisker Voice 🐈

## Overview

*Whisker Voice* is an artificial intelligence-driven research initiative focused on decoding and translating feline vocalizations into human language. By integrating advanced machine learning techniques, sound analysis, and behavioral studies, this project aims to create a system capable of fostering a deeper understanding of cat communication. Ultimately, the goal is to bridge the communication gap between humans and cats, offering invaluable insights into their emotional states, needs, and behaviors.

![Cyborg_Cat](https://i.imgur.com/M4vaeubh.png)

---

## Key Aspects

The development of an AI system capable of accurately interpreting and translating feline vocalizations necessitates a comprehensive approach, which includes data collection, sound analysis, feature extraction, machine learning model development, and ongoing validation through experimentation.

### Sample Dataset of Cat Sounds

The dataset employed for training and analysis consists of a wide variety of cat vocalizations, categorized by type and other relevant acoustic features. Below is a sample of the data used in our analysis:

| Filename          | Duration (s) | Vocalization Type | Peak Frequency (Hz) | Recording Date |
|-------------------|--------------|-------------------|---------------------|----------------|
| cat_meow_01   | 2.5          | Meow              | 750                 | 2025-02-15 14:32   |
| cat.purr_01   | 4.0          | Purr              | 120                 | 2025-02-15 14:35   |
| cat_hiss_01   | 1.2          | Hiss              | 650                 | 2025-02-15 14:40   |
| cat_pain_01   | 1.8          | Chirp             | 850                 | 2025-02-15 14:45   |

https://github.com/user-attachments/assets/62292f44-089e-400d-a7b9-9de906febdc3


https://github.com/user-attachments/assets/0a5f3ec9-2815-4b91-a2cc-833822b82dd2


https://github.com/user-attachments/assets/7cb9779f-0b1f-42f4-802c-1f59cf0ad8a7


https://github.com/user-attachments/assets/b36901ab-a9f4-49d5-998f-c1a2b8999aaf

---

## Tools & Methods Used for Analysis

1. **Audio Recording:** High-quality microphones and pre-recorded audio samples were used to capture feline vocalizations.
2. **Spectrogram Visualization:** Audacity was employed to generate spectrograms that visualize the frequency distribution of vocalizations over time.
3. **Basic Feature Extraction:** Acoustic features such as pitch, loudness, and duration were extracted using the Librosa library.
4. **Machine Learning:** A K-Nearest Neighbors (KNN) algorithm was utilized to classify the vocalizations based on the extracted features.
5. **Visualization:** Matplotlib was used to create visualizations that provided insights into both the dataset and the machine learning model's performance.

### Training Performance of AI Model

This section illustrates the performance of the AI model during training, including the loss function and accuracy metrics.

- **Training Loss Over Time**

![Training Loss](https://github.com/user-attachments/assets/063e9e9e-2d57-4b20-bd43-96797c0c33bb)

- **Accuracy Over Time**

![Training Accuracy](https://github.com/user-attachments/assets/440ef71f-7c28-45af-ae4a-b7d3b8cb1e94)

---

### Cat Helm Prototype Designs

To facilitate accurate data collection and analysis of cat vocalizations in different contexts, multiple prototypes of the "Cat Helm" were developed.

#### First Design: Initial Prototype for Data Collection

This preliminary design focused on ease of use and comfort for the feline subject during the data collection process.

![First Prototype](https://github.com/user-attachments/assets/baa677ad-18dd-4f25-b413-7f3127e70653)

#### Second Design: Enhanced with Camera and Microphone

This iteration integrated a camera and microphone, enabling simultaneous recording of vocalizations and observation of the cat’s behavior, thus improving the quality of data collection.

![Second Design](https://github.com/user-attachments/assets/1afb16cf-188b-45b1-a51d-c62f65fc62ad)

#### Final Printed and Assembled Design

The final working version of the Cat Helm was successfully fitted onto a test subject, capturing the required data for further analysis.

![Final_Design](https://github.com/user-attachments/assets/f351509d-e973-4492-8b37-abe0e6c2bf66)

---

## Data Analysis & Visualizations

The following visualizations provide a summary of key findings from the dataset and the machine learning model training process.

### 1. Spectrogram of Cat Vocalizations

The spectrogram below visualizes the frequency variations over time for different types of vocalizations, offering a clear view of their acoustic structure.

![Spectrogram](https://github.com/user-attachments/assets/7ef40b4d-c3a0-4e77-a74a-f01045f683b6)

### 2. Clustering of Cat Vocalizations

Unsupervised clustering techniques were applied to group similar vocalizations based on key acoustic features such as pitch, duration, and intensity. The resulting clusters are shown below:

| Cluster  | Number of Samples | Common Sound Type |
|----------|------------------|-------------------|
| Cluster 1 | 150              | Short Meows      |
| Cluster 2 | 120              | Purring          |
| Cluster 3 | 80               | Hissing          |
| Cluster 4 | 100              | Chirps & Trills  |

![Clustering](https://github.com/user-attachments/assets/39906c03-6468-4d1d-b8ec-5200b58eac3e)

### 3. Confusion Matrix: Vocalization Classification

The confusion matrix below visualizes the classification performance of the AI model for different types of vocalizations.

| Actual \ Predicted | Meow | Purr | Hiss | Chirp |
|--------------------|------|------|------|-------|
| **Meow**           | 85%  | 5%   | 7%   | 3%    |
| **Purr**           | 4%   | 92%  | 2%   | 2%    |
| **Hiss**           | 10%  | 3%   | 80%  | 7%    |
| **Chirp**          | 6%   | 2%   | 5%   | 87%   |

![Confusion Matrix](https://github.com/user-attachments/assets/fb781d4e-bcdc-45f7-9685-9472014dc82a)

### 4. Frequency Distribution of Vocalization Types

This chart illustrates the distribution of different vocalization types in the dataset, shedding light on their prevalence.

| Vocalization Type | Frequency |
|-------------------|-----------|
| Meow              | 250       |
| Purr              | 200       |
| Hiss              | 80        |
| Chirp             | 100       |

![Frequency Distribution](https://github.com/user-attachments/assets/c85302dc-0c63-40ea-bfbe-ea8a405a8662)

---

## Future Enhancements

As the *Whisker Voice* project continues to evolve, several key areas for improvement and expansion have been identified:

- **Refining AI Accuracy:** Expanding the dataset to include more varied vocalizations will improve the accuracy of the model.
- **Real-Time Translation Application:** The development of a real-time translation app will allow users to interact with their cats more effectively.
- **Breed-Specific Testing:** Testing the model across different cat breeds will ensure the system is generalizable and accurate for a wider range of feline vocalizations.

---

*Whisker Voice* is a pioneering project that holds the potential to transform how humans communicate with their feline companions. By offering insights into the emotions, needs, and behaviors of cats, this research aims to enhance the human-animal bond. The ongoing effort is dedicated to continuous improvements in both the AI model and hardware components.
