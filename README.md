# Classifying Wiki Articles
- Text classifier to classify Wiki articles into various categories.
- The model is trained by distributing the training process across 2 GPUs in Kaggle notebooks.
- The model is trained using TensorFlow and HuggingFace DistilBERT.
- The TensorFlow/Keras model is converted to ONNX format which resulted in a model size reduction from 800 MB to 180 MB.
