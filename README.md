# Abuse Detection System
## Overview
With the rise of social media, vast spaces for viral content have emerged, attracting large audiences. Unfortunately, this has also led to the misuse of these platforms, making them breeding grounds for toxicity and harassment. To address this issue, our project focuses on developing effective abuse detection methods using the ADIMA dataset.

## Features
Our abuse detection system is designed to be multimodal and multilingual, incorporating advanced techniques to enhance detection accuracy. The system includes the following features:

* Multimodal Fusion Techniques: Integrating multiple data types (text and audio) for comprehensive abuse detection.
* Liquid Neural Networks (LNN): Utilized for identifying abusive text content with high precision.
* Convolutional Neural Networks (CNN): Applied to detect abusive audio utterances by analyzing sound patterns from melspectrograms.
* Cross-Lingual Settings: Extending multimodal abuse detection to support 10 Indian languages.

## Methodology
### Data Processing:

Text data is processed using Liquid Neural Networks to detect abusive content.
Audio data is converted to melspectrograms and analyzed using Convolutional Neural Networks.
### Model Fusion:

Late fusion technique is applied to combine the outputs of text and audio models, leveraging the strengths of both representations.
Performance:

The ensemble model achieves an accuracy of 77.47% and an AUC of 77.89% on the multilingual test set.
