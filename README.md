# Trash Type Detection Using Image Classification

An image-based deep learning model to classify trash into six categories: Plastic, Metal Can, Paper, Rotten Fruits, E-Waste, and Water Bottle. This helps automate waste segregation and improve recycling efficiency.

##  Objective
To build and deploy a lightweight ML model capable of identifying different trash types from images, with potential deployment on embedded devices like Arduino Nano 33 BLE Sense.

## Tech Stack
- **Language:** Python  
- **Libraries:** TensorFlow, Keras, PIL  
- **Tools:** Google Colab, Edge Impulse Studio  
- **Optional Hardware:** Arduino Nano 33 BLE Sense  

## Workflow Summary
1. **Data Cleaning** – Removed corrupted images using PIL.
2. **Preprocessing** – Normalized images and applied augmentation.
3. **Model Training** – Used CNN for image classification (6 categories).
4. **Evaluation** – Achieved ~85% validation accuracy.
5. **Deployment** – Exported model to Edge Impulse for testing and optimization.

## Results
- **Validation Accuracy:** ~88%  
- **Test Accuracy:** ~95%  
- Minor misclassifications in visually similar categories.

## Future Scope
- Real-time mobile app integration  
- Deployment on Raspberry Pi or similar hardware  
- Object detection for multi-item classification  
- Dataset expansion for better accuracy

## References
- TensorFlow & Edge Impulse Documentation  
- Research on ML-based waste classification
