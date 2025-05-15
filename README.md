# Vehicle Classification with ResNet50

This project implements a deep learning model using **ResNet50** to classify images of various vehicle types. The model was trained on a custom dataset containing classes like SUV, bus, fire engine, and others. It includes training, evaluation, prediction, and visualization components, and uses PyTorch and torchvision.

---

## 📂 Dataset

The dataset used consists of labeled vehicle images organized in class-wise folders for training. The test set contains unlabeled images used for prediction only.

**Classes:**
- SUV  
- Bus  
- Family Sedan  
- Fire Engine  
- Heavy Truck  
- Jeep  
- Minibus  
- Racing Car  
- Taxi  
- Truck

---

## 🚀 Features

- Transfer Learning using pretrained **ResNet50**
- Data augmentation and normalization
- Custom training loop with progress tracking using `tqdm`
- Evaluation metrics: Accuracy, Precision, Recall, F1-score
- Visualization of predictions
- Saving and loading trained model
- Clean code structure for reproducibility

---

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/vehicle-classifier-resnet50.git
   cd vehicle-classifier-resnet50
