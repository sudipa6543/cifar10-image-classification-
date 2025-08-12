# cifar10-image-classification-
Image Classification on CIFAR-10 using CNN and transfer learning

Overview:
Image classification on CIFAR-10 using CNN and Transfer Learning.

Dataset:
CIFAR-10: 60,000 32*32 color images in 10 classes(airplane,automobile,bird,cat,deer,dog,frog,horse,ship,truck).

Features:
-Basic CNN model
-Data augmentation
-Transfer learning with MobileNetV2
-Model evaluation with accuracy and confusion matrix.
-Saved trained moel(cnn_model.h5).

Requirements:
-TensorFlow
-Matplotlib
-Scikit-learn
-Seaborn
Install with: !pip install tensorflow matplotlib scikit-learn seaborn

Results:
-CNN accuracy:~60-65%
-Augmented CNN:~63-67%
-Transfer learning:70-85%(improved with fine-tuning)

