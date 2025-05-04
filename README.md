🪼 Jellyfish Image Augmentation Using Python
This project demonstrates how image augmentation techniques can be applied to a jellyfish image dataset to improve dataset diversity for machine learning and computer vision tasks. It uses the Mauve Stinger Jellyfish images as the dataset and applies multiple transformations to enhance the data.

🎯 Project Goal
The goal of this project is to:

Visually demonstrate basic image augmentation techniques.

Show how image diversity can be increased through transformations.

Provide insights into how data augmentation improves model robustness.

📁 Dataset
The project uses a local folder containing images of jellyfish. You can replace the dataset with any other set of images for similar augmentation.

Image formats supported:

.jpg

.jpeg

.png

🧠 Augmentation Techniques Applied
Each original image is transformed using the following techniques:

Horizontal Flip: The image is mirrored left to right.

Rotation: The image is rotated by 30 degrees to simulate different angles.

Zoom: A center crop of 80% of the image is resized back to the original size.

Color Enhancement: The color intensity is increased to enhance visual features.

Each original image results in 4 new versions, producing 5 total images including the original.

📊 Outputs
The script prints the total number of original images.

Calculates the total number of images after augmentation, assuming every image is augmented.

A visualization is generated showing a 3×5 grid of images:

3 randomly selected original images

Each shown with its four augmented variants

📦 Tools & Libraries Used
Pillow (PIL) – For image processing and augmentations

Matplotlib – For visualizing the original and augmented images

Python Built-in Libraries – OS and random for file operations

🖼️ Visualization
The project creates a plot where:

Each row corresponds to a randomly selected image.

Each row contains the original and four augmented versions:

Original

Flipped

Rotated

Zoomed

Color Enhanced

This helps in comparing the impact of each augmentation visually.

✅ Benefits of Augmentation
Increases dataset size without collecting new data.

Improves model generalization and accuracy.

Reduces overfitting in training deep learning models.

Simulates real-world scenarios through transformations.

🚀 Future Enhancements
Save augmented images into a new output directory.

Add more transformations like brightness adjustment, contrast, and noise.

Integrate with machine learning model training pipelines.

Provide command-line options for dynamic augmentation.

