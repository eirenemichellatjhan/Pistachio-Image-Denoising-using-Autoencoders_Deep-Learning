# Pistachio-Image-Denoising-using-Autoencoders_Deep-Learning

This project focused on restoring noisy pistachio images using deep learning–based denoising autoencoders. The goal was to reconstruct clean images from noisy inputs, improving visual quality and preserving structural details for better image clarity and feature extraction.

**Tools**: Python, TensorFlow, Keras, OpenCV, Matplotlib

**Approach**: Compared three architectures: a baseline autoencoder, a U-Net model, and a tuned U-Net with optimized hyperparameters using GridSearch.

**Results**: The Tuned U-Net achieved the lowest MSE (0.000230), lowest MAE (0.006506), and highest reconstruction accuracy, outperforming the baseline and standard U-Net.

**Key Insight**: Careful hyperparameter tuning can significantly improve image reconstruction quality, even when using similar model architectures.
