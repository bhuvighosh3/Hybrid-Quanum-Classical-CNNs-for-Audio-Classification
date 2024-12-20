# Performance Analysis of Hybrid Quantum-Classical Convolutional Neural Networks for Audio Classification

**Authors**: Yash Thakar, Bhuvi Ghosh, Vishma Adeshra, Kriti Srivastava  

## Overview  
This research explores a hybrid quantum-classical convolutional neural network (QC-CNN) architecture for audio classification using mel-spectrograms. The QC-CNN demonstrated competitive performance with classical models, especially on large datasets, showcasing its potential for audio data applications.  

## Manuscripts  
This paper was presented at the **15th International Conference on Computing Communication and Networking Technologies (ICCCNT)**, IIT Mandi, and published in **[IEEE Xplore](https://ieeexplore.ieee.org/document/10725668)**.  

**DOI**: [10.1109/ICCCNT61001.2024.10725668](https://doi.org/10.1109/ICCCNT61001.2024.10725668)  

## Abstract  
Audio signals, known for their high dimensionality and complexity, present challenges for classical machine learning techniques in computation and generalization. This paper evaluates a hybrid QC-CNN architecture that leverages quantum phenomena such as superposition and entanglement for audio classification using mel-spectrograms.  

Key findings include:  
- QC-CNN achieved comparable training accuracy with classical CNN on small datasets but surpassed it on test accuracy (95.04% vs. 92.88%) for a large birdsong dataset.  
- The architecture reduced overfitting and exhibited significantly lower cross-entropy loss on larger datasets.  
- Demonstrates the application of QC-CNN for robust and efficient audio classification tasks.  

## Methodology

<p align="center">
  <img src="Readme images/architecture diagram.png" height="500" />
</p>

1. **System Architecture**:
   - Developed a system to build and evaluate QC-CNN models, focusing on data preparation, feature extraction, and model evaluation.

2. **Dataset Preparation**:
   - Utilized two datasets:
     - **GTZAN Genre Classification** (small dataset): 10 music genres with 100 files per genre for binary classification.
     - **Birdsong Dataset** (large dataset): 1000 audio files per bird species for binary classification.

3. **Feature Extraction**:
   - Converted audio signals from both datasets into **Mel-Spectrograms** to capture frequency-domain features aligned with human auditory perception.

4. **Classical CNN Architecture**:
   - Comprised three convolutional layers, max-pooling, dropout regularization, and fully connected layers.
   - Optimized using **Stochastic Gradient Descent (SGD)** and **binary cross-entropy loss**.

5. **Quantum-Classical Hybrid Model**:
   - Integrated a quantum neural network (QNN) layer with an 8-qubit quantum circuit, including **ZZFeatureMap** for embedding classical data and **RealAmplitudes** ansatz for quantum processing.

6. **Model Evaluation**:
   - Models were trained and evaluated on:
     - **GTZAN Genre Classification Dataset** (small dataset)
     - **Birdsong Dataset** (large dataset)
   - Performance was compared using metrics like accuracy, precision, and cross-entropy loss.  

## Results  

- On the small dataset, QC-CNN performed comparably to classical CNNs during training.  
- For the large birdsong dataset, QC-CNN outperformed classical CNNs with a test accuracy of 95.04% versus 92.88%.  
- QC-CNN demonstrated reduced overfitting and better generalization capabilities.

<img src="Readme images/result.png" width="500" />
<img src="Readme images/result1.png" width="500" />

## Software Implementation  

The project provides:  
1. **Code and Notebooks**: All computations and visualizations are implemented in Jupyter Notebooks.  
2. **Data**: The dataset used for analysis is stored within the repository.  
3. **Results**: All results are reproducible using the scripts provided.  

## Dependencies

You'll need a working Python environment to run the code.
The recommended way to set up your environment is through the
[virtualenv](https://virtualenv.pypa.io/en/latest/) python package.
The required dependencies are specified in the file `requirements.txt`.

## Getting the Code  
Clone the repository to access the code:  

```bash  
git clone https://github.com/bhuvighosh3/Hybrid-Quantum-Classical-CNNs-for-Audio-Classification.git
