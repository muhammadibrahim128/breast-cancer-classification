# breast-cancer-classification

Cancer Classification Using DenseNet121 Model
Steps:

Data Collection: • Source: "https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset"

Data Preprocessing: • Review quantity, quality, and size of images • Resize images for consistency

Model Selection: • DenseNet121 used for image classification

Model Training: • Train using custom class count and optional mask input (3 or 6 channels) • Choose epochs based on your hardware capabilities and time availability

Model Evaluation: • Evaluate the trained model on test data to check accuracy and performance

Model Optimization: • Convert the trained PyTorch model (.pth) to ONNX • Convert ONNX to TensorFlow (.pb) • Convert to TensorFlow Lite (.tflite) with float16 quantization for efficient deployment on edge devices
