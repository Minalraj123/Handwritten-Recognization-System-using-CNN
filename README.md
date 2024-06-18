# Handwritten-Recognization-System-using-CNN
This project demonstrates a handwritten digit recognition system using Pygame for drawing digits and a trained Keras convolutional neural network (CNN) to recognize and classify the drawn digits.
Handwriting_Recognition using CRNN_CTC architecture for an deep-learning-based OCR Model.
Introduction
OCR = Optical Character Recognition. In other words, OCR systems transform a two-dimensional image of text, that could contain machine printed or handwritten text from its image representation into machine-readable text. OCR as a process generally consists of several sub-processes to perform as accurately as possible. The subprocesses are:

Preprocessing of the Image
Line Segmentation
Word Segmentation
Text Recognition
Post Processing
Problem Statement
For almost two decades, optical character recognition systems have been widely used to provide automated text entry into computerized systems. Yet in all this time, conventional OCR systems (like zonal OCR) have never overcome their inability to read more than a handful of type fonts and page formats.

Next-generation OCR engines deal with these problems mentioned above really good by utilizing the latest research in the area of deep learning. By leveraging the combination of deep models and huge datasets publicly available, models achieve state-of-the-art accuracies on given tasks. Nowadays it is also possible to generate synthetic data with different fonts using generative adversarial networks and few other generative approaches.

Optical Character Recognition remains a challenging problem when text occurs in unconstrained environments, like natural scenes, due to geometrical distortions, complex backgrounds, and diverse fonts. The technology still holds an immense potential due to the various use-cases of deep learning based OCR like

building license plate readers
digitizing invoices
digitizing menus
digitizing ID cards
In this notebook, we'll go through the steps to train a CRNN (CNN+RNN) model for handwriting recognition. The model will be trained using the CTC(Connectionist Temporal Classification) loss function.
