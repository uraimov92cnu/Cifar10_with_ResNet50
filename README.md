# Cifar10_with_ResNet50
Two-stage training was performed using pretrained ResNet50 model weights on the CIFAR-10 dataset. The primary objective was to achieve the highest F1 score.  


# Key Features of the CIFAR-10 Training Code:¶
Two-Stage Training: Trains the final layer first (frozen pretrained layers), then fine-tunes all layers for better accuracy. Pretrained ResNet50: Uses pretrained ResNet50 model for efficient feature extraction. CIFAR-10 Dataset: Processes CIFAR-10 with data augmentation (random crop, flip) and normalization. PyTorch Framework: Leverages PyTorch for model training, optimization, and evaluation. Metrics: Tracks loss, accuracy, and F1 score; visualizes with confusion matrix and plots. Tools Used: PyTorch, torchvision, NumPy, Matplotlib, Seaborn, scikit-learn, tqdm.
