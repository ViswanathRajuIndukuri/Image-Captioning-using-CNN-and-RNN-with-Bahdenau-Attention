# Image Captioning using CNN and RNN with Bahdenau Attention

[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

### Objective
The objective of this project is to develop an image captioning model capable of generating accurate and contextually relevant captions for images.

## Project Description
- In this project, I've developed an image captioning model that effectively combines techniques from both computer vision and natural language processing, utilizing the COCO (Common Objects in Context) dataset.
- Implemented Convolutional Neural Networks (CNNs) to extract features from images in the COCO dataset, enabling the model to understand the visual content.
- Utilized Recurrent Neural Networks (RNNs) to generate sequential text for captions, ensuring coherence and grammatical correctness, based on the image features extracted from the COCO dataset.
- Incorporated Bahdanau Attention mechanism into the model to dynamically focus on different parts of the images from the COCO dataset, enhancing the relevance and detail of the generated captions.
- Trained the model on the COCO dataset, which provides a large collection of images paired with corresponding captions, allowing the model to learn the relationship between visual content and textual descriptions in various contexts.

### Key Components
1. **CNN Feature Extraction**: Utilized CNNs to extract meaningful features from images, enabling the model to understand visual content.
2. **RNN Caption Generation**: Implemented RNNs to generate sequential text for captions, ensuring grammatical correctness and coherence.
3. **Bahdanau Attention**: Incorporated Bahdanau Attention mechanism to dynamically focus on different parts of images, enhancing the relevance and detail of generated captions.
