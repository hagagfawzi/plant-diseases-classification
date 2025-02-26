Plant Disease Classification Using MobileNetV2
Project Overview
This project focuses on developing an advanced Plant Disease Classification Model using MobileNetV2, a lightweight and efficient deep learning architecture. The goal is to identify plant diseases based on leaf images with high accuracy, assisting farmers and researchers in early disease detection.

Dataset
The dataset consists of images of healthy and diseased plant leaves, categorized into multiple disease classes. Each image is labeled with the corresponding disease type, enabling the model to learn patterns distinguishing healthy from affected plants. The dataset is preprocessed by:

Resizing & Normalization to ensure uniform input size.
Data Augmentation (rotation, flipping, brightness adjustments) to enhance model robustness.
Splitting into Training, Validation, and Test Sets for reliable evaluation.
Model: MobileNetV2
MobileNetV2 is chosen for its efficiency and accuracy, making it suitable for deployment on mobile devices. The model:

Uses depthwise separable convolutions to reduce computational complexity.
Extracts meaningful features from images and classifies them into the correct disease category.
Achieves 99% training accuracy and 96% test accuracy, indicating strong performance.
Training & Evaluation
The model is trained using TensorFlow/Keras with:

Categorical Crossentropy Loss for multi-class classification.
Adam Optimizer for efficient learning.
Metrics like Accuracy, Precision, Recall, and F1-Score for performance evaluation.
Deployment & Application
The trained model can be deployed in real-world applications, including:

Mobile or Web Applications using TensorFlow Lite (TFLite) for real-time disease detection.
Agricultural Advisory Systems to help farmers take preventive actions.
Integration with Drones or IoT Devices for automated field monitoring.
Conclusion
This project demonstrates how deep learning can revolutionize agriculture and plant disease management. By deploying an accurate and efficient MobileNetV2 model, we can assist farmers in detecting diseases early, improving crop yield and reducing losses.

