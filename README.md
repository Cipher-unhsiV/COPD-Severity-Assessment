# COPD Severity Classification using Lung Sound 🩺💡

## 📋 **Contents**
- [Abstract 🌍](#abstract-)
- [Introduction 🚀](#introduction-)
- [Related Work 🔬](#related-work-)
- [Research Methodology 🧠](#research-methodology-)
  - [Dataset 🎤](#dataset-)
  - [Preprocessing 🛠️](#preprocessing-)
  - [Augmentation 🎧](#augmentation-)
  - [Feature Extraction 🖼️](#feature-extraction-)
- [Proposed System ⚙️](#proposed-system-)
  - [Model Architecture 💡](#model-architecture-)
  - [Performance Evaluation 📊](#performance-evaluation-)
- [Conclusion 💬](#conclusion-)
- [Future Work 🔮](#future-work-)
- [Repository Information 📂](#repository-information-)
- [Contributing 🤝](#contributing-)
- [License 📜](#license-)
- [BibTeX 📚](#bibtex-)
- [Citation 📄](#citation-)
- [RIS 📑](#ris-)

---

## **Abstract** 🌍
COPD (Chronic Obstructive Pulmonary Disease) is silently affecting millions across the globe, with 251 million cases reported worldwide. Early detection is key to managing this potentially debilitating condition, and lung sound analysis could be the game-changer we need!

In this project, we present an innovative approach to multi-class COPD severity classification using lung sound data. Using RESNET50 and advanced feature extraction techniques such as spectrograms, Mel spectrograms, and chromograms, our deep learning model is trained to predict COPD severity with impressive accuracy.

Let’s breathe life into early diagnosis and give healthcare professionals a powerful tool to make better decisions, faster.

---

## **Index Terms** 📑
```COPD```, ```RESNET```, ```Deep Learning```, ```Lung Sound Analysis```, ```Early Diagnosis```, ```Multi-Class Classification```.

---

## **Introduction** 🚀
COPD is one of the leading causes of death globally, and its early detection remains one of the biggest challenges in healthcare. With its progressive nature, diagnosing COPD in its early stages could drastically improve patient outcomes. Traditional diagnostic methods often rely on invasive techniques, but what if we could make it as simple as listening to the lungs?

Enter lung sound analysis, a non-invasive method with the potential to revolutionize the early detection of COPD. By utilizing data-driven deep learning models such as RESNET50, we aim to classify lung sounds into distinct severity levels of COPD, opening the door to quicker, more accessible diagnoses.

---

## **Related Work** 🔬
Many efforts have been made to detect COPD through lung sounds. Here are some highlights:

- **Arka et al.** leveraged YAMNet for classifying COPD using Mel spectrograms.
- **Oweis et al.** focused on binary classification using neural networks and autocorrelation functions.
- **Jayalakshmy et al.** enhanced lung sound classification with ALEXNet and scalogram features.
- **Pham et al.** used a deep neural network for sound analysis with a teacher-student scheme.

Our approach builds on these methods, employing a powerful deep learning model (RESNET50) and unique feature extraction techniques to achieve high accuracy and reliability.

---

## **Research Methodology** 🧠
### 🎤 **Dataset**
The dataset used in this study is the [**RespiratoryDatabase@TR**](https://data.mendeley.com/datasets/p9z4h98s6j/1/files/4920eb3e-cecd-47b2-95b0-75b6446a4aad), which contains 12 channels of lung sounds from both healthy individuals and patients with chronic pulmonary diseases. The data also includes chest X-rays, PFT results, and auscultation sounds validated by pulmonologists.

### **Preprocessing** 🛠️
Each audio recording was carefully segmented into 10-second intervals to ensure consistency across the dataset. Longer recordings were divided into overlapping segments, making sure we captured vital lung sound information while maintaining data integrity.

### **Augmentation** 🎧
Data augmentation techniques like Pitch Scaling and Noise Addition were employed to enrich the dataset, ensuring the model generalizes well on unseen data and remains robust across diverse real-world scenarios.

### **Feature Extraction** 🖼️
Raw lung sound recordings were converted into spectrograms, Mel spectrograms, and chromograms, offering a visual representation of the sounds. These images act as a perfect input for the RESNET50 model, boosting its performance in identifying the subtle nuances of lung sound patterns tied to different stages of COPD.

---

## **Proposed System** ⚙️
### **Model Architecture** 💡
The heart of our system is **RESNET50**, a cutting-edge deep learning architecture known for its residual learning framework. It excels in recognizing complex patterns, making it ideal for lung sound classification.

We trained the model on the preprocessed dataset and used multi-class classification to predict different COPD severity levels ranging from COPD 0 (low severity) to COPD 4 (high severity).

### **Performance Evaluation** 📊
The model was evaluated using various metrics like accuracy, precision, recall, and F1-score. The results were highly promising, demonstrating that our approach is a step forward in accurate COPD diagnosis using lung sounds.

---

## **Conclusion** 💬
By leveraging the power of deep learning and lung sound analysis, we present a non-invasive method to detect and classify COPD severity. This research is an exciting step toward making COPD diagnosis quicker, more affordable, and accessible globally. With continued improvements, this tool could be integrated into healthcare practices worldwide, helping to save lives by detecting COPD early.

---

## **Future Work** 🔮
The journey doesn’t stop here! Future improvements include:

- **Enhanced Feature Extraction**: We plan to explore more sophisticated feature extraction techniques for better accuracy.
- **Mobile Health Integration**: We’re looking into ways to bring this model to mobile devices, enabling real-time diagnosis at your fingertips.

This project has the potential to make a lasting impact in healthcare innovation, and we can’t wait to continue this journey of discovery.

---

## **Repository Information** 📂
This repository contains all the necessary files to replicate the COPD severity classification system, including:

- **Data**: Preprocessed and raw lung sound datasets (subject to licensing restrictions).
- **Code**: Python code for feature extraction, model training, and evaluation.
- **Model**: Trained model weights for RESNET50.

---

## **Contributing** 🤝
We welcome contributions from the community! To contribute, please fork the repository, make your changes, and submit a pull request. We ask that all contributors adhere to the following guidelines:

- Ensure that your code is well-documented and adheres to our code style.
- Include test cases for any new features or bug fixes.
- Ensure that your changes do not break existing functionality.
- Follow best practices for deep learning model training.

---

## **License** 📜
This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.

---

## **BibTeX** 📚 

```BibTeX
@INPROCEEDINGS{10543344,
  author={Khanaghavalle, G R and Rahul, G and Senajith, S R and Vishnuvasan, T S and Keerthana, S},
  booktitle={2024 10th International Conference on Communication and Signal Processing (ICCSP)}, 
  title={Chronic Obstructive Pulmonary Disease Severity Classification using Lung Sound}, 
  year={2024},
  pages={428-432},
  keywords={Training, Data preprocessing, Lung, Machine learning, Feature extraction, Chronic obstructive pulmonary disease, Spectrogram, COPD, RESNET, Deep Learning},
  doi={10.1109/ICCSP60870.2024.10543344}
}
```

---

## Citation 📄

**G. R. Khanaghavalle**, **G. Rahul**, **S. R. Senajith**, **T. S. Vishnuvasan**, and **S. Keerthana**, "Chronic Obstructive Pulmonary Disease Severity Classification using lung sound," *2024 10th International Conference on Communication and Signal Processing (ICCSP)*, Melmaruvathur, India, 2024, pp. 428-432, doi: [10.1109/ICCSP60870.2024.10543344](https://doi.org/10.1109/ICCSP60870.2024.10543344) 📚.

---

## RIS 📑

```ris
TY  - CONF
TI  - Chronic Obstructive Pulmonary Disease Severity Classification using lung sound
T2  - 2024 10th International Conference on Communication and Signal Processing (ICCSP)
SP  - 428
EP  - 432
AU  - G. R. Khanaghavalle
AU  - G. Rahul
AU  - S. R. Senajith
AU  - T. S. Vishnuvasan
AU  - S. Keerthana
PY  - 2024
DO  - 10.1109/ICCSP60870.2024.10543344
JO  - 2024 10th International Conference on Communication and Signal Processing (ICCSP)
SN  - 2836-1873
Y1  - 12-14 April 2024
```

---

Feel free to fork, clone, and contribute to this repository. Let’s work together to bring this technology to the world and make a difference!

Happy coding and happy breathing! 🌬️
