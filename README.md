# AgeDetection

This project involves creating an age detection system using a deep learning model, trained on a dataset of images generated from Stable Diffusion. The primary goal is to predict the age of individuals based on facial features captured in these images.

Project Title: Age Detection from Images

Objective: Develop a machine learning model to accurately estimate a person's age from their image.

Technologies Used: Python, PyTorch, Pandas, PIL, torchvision, NumPy, tqdm

Project Description:
This project involves creating an age detection system using a deep learning model, trained on a dataset of images generated from Stable Diffusion. The primary goal is to predict the age of individuals based on facial features captured in these images.

Methodology:

Data Preparation: Utilized a dataset consisting of pre-labeled images with corresponding age values. The images were loaded and processed using Pandas and PIL libraries, with transformations applied to standardize image sizes and normalize pixel values for model input.
Model Architecture: Employed a pretrained ResNet-18 model, modifying the final fully connected layers to tailor it for age prediction. The model's architecture was adapted to refine learning to specific age-related features in the facial images.
Training and Validation: The dataset was divided into training and validation sets. The model was trained using MSE (Mean Squared Error) as the loss function, optimized with Adam optimizer. Extensive training over 100 epochs was conducted to minimize prediction errors, with a detailed log of training loss provided for performance tracking.
Testing and Results Compilation: A separate test set was prepared and used to evaluate the model, with the predictions saved into a CSV file for potential real-world application or further analysis.
Results: The project achieved significant reduction in loss over the training period, indicating successful model learning and improved accuracy in age prediction.

Conclusion: This project demonstrates the effectiveness of using convolutional neural networks for age detection in images. The methodology and results provide a foundation for further research and potential applications in identity verification, digital media, and demographic studies.
