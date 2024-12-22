### **README: Automated Fruit Classification and Grading System**

---

## **Project Overview**
This project leverages deep learning to automate fruit classification, detection, and grading, revolutionizing traditional sorting processes. A Mask R-CNN model was developed to classify 48 fruit varieties with high accuracy, optimized for precise boundary detection and anomaly detection to ensure quality control.

---

## **Features**
- **Fruit Classification**: Achieved a 94% F1 score on a 30,000-image dataset, identifying 48 fruit varieties.
- **Enhanced Fruit Detection**: Optimized boundary masking techniques, improving detection precision to 86% for accurate sorting.
- **Anomaly Detection**: Developed a system with 90.5% accuracy to identify defective or inedible fruits, enhancing grading efficiency.

---

## **Technologies Used**
- **Deep Learning Frameworks**: TensorFlow/Keras or PyTorch.
- **Model Architecture**: Mask R-CNN for segmentation and classification.
- **Dataset**: 30,000 labeled fruit images for training and validation.
- **Anomaly Detection**: Custom pipeline for detecting non-standard features.

---

## **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   ```
2. Navigate to the project directory:
   ```bash
   cd repository-name
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Prepare the dataset and place it in the `/data` directory.

---

## **Usage**
1. **Train the Mask R-CNN Model**:
   ```bash
   python train_model.py
   ```
2. **Run Fruit Detection**:
   ```bash
   python detect_fruits.py --image_path <path_to_image>
   ```
3. **Perform Anomaly Detection**:
   ```bash
   python detect_anomalies.py --image_path <path_to_image>
   ```

---

## **Results**
- **Classification Accuracy**: 94% F1 score across 48 fruit varieties.
- **Detection Precision**: 86% with optimized masking techniques.
- **Anomaly Detection**: 90.5% accurate system for fruit grading.

---

## **Contributions**
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Contact**
For inquiries or suggestions, contact **Md Nematullah** at **mdnematullah.iitkgp@gmail.com**.