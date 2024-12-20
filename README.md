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
1. **Model Development**:  
   - A hybrid QC-CNN architecture was designed to combine classical convolutional layers with quantum processing.  
   - Mel-spectrograms from audio data were used as input features.  

2. **Training and Evaluation**:  
   - The models were trained on small and large datasets, including a birdsong dataset.  
   - Performance metrics such as accuracy and cross-entropy loss were compared with classical CNNs.  

## Results  

#### Small-Sized Music Genre Classification Dataset:
![Training and Validation Loss](Readme%20images/result.png)

#### Large-Sized Birdsong Dataset:
![Test Accuracy Comparison](Readme%20images/result1.png)

- On the small dataset, QC-CNN performed comparably to classical CNNs during training.  
- For the large birdsong dataset, QC-CNN outperformed classical CNNs with a test accuracy of 95.04% versus 92.88%.  
- QC-CNN demonstrated reduced overfitting and better generalization capabilities.  

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
