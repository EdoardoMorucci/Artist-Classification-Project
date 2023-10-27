
# Artist Image Classification

Image classification using CNN from scratch, pretrained networks and ensemble optimized with a genetic algorithm.

Project completed for the “Deep Learning” exam.


## Short Description

The primary objective of this project is to develop an algorithm with a high degree of precision to correctly identify the artist of a given painting. We specifically explore the utilization of Convolutional Neural Networks (CNNs) for artist identification. Our approach encompasses various techniques, including constructing **CNNs from scratch**, employing **pre-trained networks**, and assembling an **ensemble** network composed of the most effective classifiers. 

Furthermore, we employ a **genetic algorithm** to search for the optimal ensemble parameters. Additionally, we conduct an explainability study to gain insights into the critical features that influence the neural networks used for image classification.

The most promising results are achieved through the ensemble model, which attains an 87% accuracy rate on the test set.

This research holds particular significance as it has the potential for practical applications in museums seeking to modernize through digitalization. For instance, many museums, such as the Louvre in Paris, employ technology guides to assist visitors during exhibitions. We believe that our model's predictions could offer a dynamic means of obtaining information about paintings and their artists simply by capturing a photograph of the artwork during a visit.

To summarize our project, the following key steps were taken (further details can be found in the attached PDF documentation):

1. Introduction
2. Review of Existing Approaches
3. Description of the Dataset
4. Data Preprocessing
5. Image Resizing
6. Data Balancing (Including Data Augmentation and Class Weights)
7. Building CNN from Scratch
8. Development of the Base Model
9. Various Experiments with Different Model Parameters (e.g., number of layers, learning rate, dropout, early stopping, dense layers, strides, regularization, single and double inception layers, hyperparameter optimization)
10. Utilization of Pre-Trained Models
11. VGG16
12. ResNet50
13. Inception V3
14. Ensemble Learning
15. Application of a Genetic Algorithm to Determine the Best Weight Combinations
16. Explainability Study
17. Investigation of Intermediate Activations
18. Generation of Heatmaps
