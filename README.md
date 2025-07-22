# Brain Tumor Detection Using Deep Learning Techniques
## 📌 Overview
This project focuses on the automated detection of brain tumors from MRI images using deep learning techniques. Multiple models were implemented and evaluated, including VGG-19, ResNet, K-Nearest Neighbors (KNN), Kolmogorov-Arnold Networks (KAN), and Deep Belief Network (DBN). The objective was to identify the most accurate and reliable model for classifying brain tumors from MRI scans.

## 🧩 Dataset
The dataset consists of a total of 253 Brain MRI images, organized into two categories:

Yes Folder (155 images): Contains MRI images diagnosed with brain tumors.

No Folder (98 images): Contains MRI images with no tumors (healthy).

This balanced but moderately sized dataset allows for binary classification of brain tumor presence based on image inputs.

## 📊 Models and Accuracy
The table below summarizes the training and testing accuracy scores achieved by each model:

<table border="1">
  <thead>
    <tr>
      <th>Model</th>
      <th>Training Accuracy (%)</th>
      <th>Validation Accuracy (%)</th>
      <th>Test Accuracy (%)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>VGG-19</td>
      <td>94.80</td>
      <td>81.48</td>
      <td>94.44</td>
    </tr>
    <tr>
      <td>ResNet</td>
      <td>78.00</td>
      <td>74.07</td>
      <td>75.93</td>
    </tr>
    <tr>
      <td>KNN</td>
      <td>84.40</td>
      <td>77.78</td>
      <td>79.63</td>
    </tr>
    <tr>
      <td>KAN</td>
      <td>88.80</td>
      <td>77.78</td>
      <td>88.89</td>
    </tr>
    <tr>
      <td>DBN</td>
      <td>78.40</td>
      <td>75.93</td>
      <td>79.63</td>
    </tr>
  </tbody>
</table>

## 📁 Project Files
The repository contains the following Jupyter Notebook files for model implementations:

code1-KAN.ipynb – Implementation of the Kolmogorov-Arnold Networks (KAN) model.

code2-VGG19.ipynb – Implementation of the VGG-19 model.

code3-KNN.ipynb – Implementation of the K-Nearest Neighbors (KNN) model.

code4-RESNET.ipynb – Implementation of the ResNet model.

code5-DBN.ipynb – Implementation of the Deep Belief Network (DBN) model.

## ✅ Results and Observations
<ul>
    <li><b>VGG-19</b> achieved the <b>highest test accuracy (94.44%)</b>, demonstrating superior feature extraction and generalization.</li>
    <li><b>KAN</b> followed with a strong <b>88.89% test accuracy</b>, showing reliable performance.</li>
    <li><b>KNN</b> and <b>DBN</b> provided moderate performance with <b>79.63% test accuracy</b>, but lacked consistency compared to VGG-19 and KAN.</li>
    <li><b>ResNet</b> delivered the lowest test accuracy (<b>75.93%</b>), potentially due to underfitting or insufficient fine-tuning.</li>
    <li>Overall, <b>VGG-19</b> and <b>KAN</b> emerged as the most effective models in this project for brain tumor detection from MRI images.</li>
</ul>

## 🚀 Future Improvements
Hyperparameter Tuning: Explore advanced optimization techniques (Grid Search, Bayesian Optimization) for improving model performance.

Data Augmentation: Apply data augmentation techniques to increase dataset variability and improve model robustness.

Advanced Architectures: Experiment with more sophisticated architectures like EfficientNet, Vision Transformers (ViT), or Swin Transformers.

Transfer Learning Improvements: Further fine-tuning of pre-trained networks to enhance generalization on medical imaging tasks.

## 📢 Conclusion
The project demonstrates the potential of deep learning in medical imaging applications. VGG-19 emerged as the most effective model in this case. With further refinements like data augmentation and hyperparameter optimization, the performance could be further improved for real-world applications.
