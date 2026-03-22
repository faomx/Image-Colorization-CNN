# 🎨 Image Colorization CNN

A deep learning project that brings grayscale images to life using encoder-decoder CNNs,
built with both **TensorFlow/Keras** and **PyTorch**.

## 🚀 Features
- **Dual Implementation**: Two fully trained models — TensorFlow/Keras and PyTorch.
- **LAB Color Space**: Converts images to LAB format, predicting AB (color) channels from L (grayscale).
- **Encoder-Decoder Architecture**: Custom CNN designed for image-to-image translation.
- **Strong Results**: Achieved **PSNR of 68.23** and **SSIM of 0.99** on the test set.
- **Preprocessing Pipeline**: Automated image loading, resizing, and normalization.

## 🛠️ Technologies Used
- **Python** (Core Logic)
- **TensorFlow / Keras** (Model 1 — with EarlyStopping & ReduceLROnPlateau)
- **PyTorch** (Model 2 — full-size image training)
- **OpenCV** (Image processing & LAB conversion)
- **scikit-image** (PSNR & SSIM evaluation)
- **Kaggle** (Dataset & training environment)

## 📁 Project Structure
- `image-colorize.ipynb`: Full notebook — preprocessing, training, and evaluation for both models.
- `colorization_model.pth`: Saved PyTorch model weights.
- `requirements.txt`: All required Python dependencies.

## 📊 Results
| Metric | Score |
| :---: | :---: |
| PSNR | 68.23 |
| SSIM | 0.99 |
| PyTorch Final Loss | ~0.0096 |

## 🎓 Academic Context
This project was built to explore **deep learning for computer vision**, specifically the challenge
of reconstructing color information from grayscale input using convolutional neural networks.
