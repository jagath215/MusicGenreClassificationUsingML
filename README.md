# Music Genre Classification using Machine Learning
This project explores the classification of music genres using machine learning techniques. The dataset used is the GTZAN Genre Collection, which consists of 1000 audio tracks categorized into 10 different genres. The project involves several steps, including data preprocessing, feature extraction, model training, and evaluation. Various machine learning algorithms, such as Support Vector Machine (SVM), Decision Tree, Random Forest, K-Nearest Neighbors (KNN), and Artificial Neural Networks (ANN), are employed and compared to determine their effectiveness in classifying music genres.

## Key Features
1. **Dataset**: GTZAN Genre Collection with 1000 audio tracks in 10 genres.
2. **Data Preprocessing**: Includes loading, resampling, normalization, and splitting of audio files.
3. **Feature Extraction**: Utilizes librosa library to extract features like Chroma STFT, RMS, spectral centroid, spectral bandwidth, spectral contrast, ZCR, MFCCs, and chromagram.
4. **Models Used**: SVM, Decision Tree, Random Forest, KNN, and ANN.
5. **Hyperparameter Tuning**: Performed using RandomizedSearchCV.
6. **Evaluation**: Models evaluated based on accuracy and other metrics.
## Visualizations and Results
1. **Waveform Plot**s: Display amplitude over time.
2. **Chroma STFT Plots**: Show intensity of different pitch classes over time.
3. **Spectral Centroid Plots**: Illustrate the brightness of sound over time.
4. **MFCCs Plots**: Depict the timbral characteristics of audio.
## How to Use
1. Clone the repository.
2. Install required dependencies.
3. Run the Jupyter Notebook to preprocess data, extract features, train models, and visualize results.
This project aims to provide a comprehensive approach to music genre classification and serve as a reference for future research in this domain.
