# Image Encryption Using Chaos Theory and PSO

## 📌 Description
This project is a student-level implementation of an image encryption algorithm based on chaotic systems (Logistic Map) and Particle Swarm Optimization (PSO).  

The goal of this project is purely educational and it is developed as part of an academic coursework assignment.

## ⚠️ Disclaimer
This project is intended **only for educational and research purposes**.  
It has no commercial use and should not be used in any production or security-critical systems.

The author does not take any responsibility for any misuse of this code.

## 🛠️ Technologies Used
- Python  
- NumPy  
- OpenCV  
- Matplotlib  
- Google Colab

## 📚 Features
- Chaotic key generation using Logistic Map  
- Parameter optimization using PSO  
- Image permutation and diffusion stages  
- Encryption and decryption pipeline  
- Security analysis (NPCR, UACI, Entropy)

## 🔐 Security Evaluation

Additional experiments were performed to evaluate the robustness of the encryption algorithm.
The following security tests are included:

### Noise Attack Analysis
File:
- noise_attack.ipynb

Evaluation of encryption robustness against:
- Gaussian Noise
- Salt & Pepper Noise

### Key Sensitivity Analysis
File:
- key_sensitivity.ipynb

Evaluation of the effect of small changes in encryption key parameters on the decrypted image.

### Geometric Attack Analysis
File:
- geometric_attack.ipynb

Evaluation of algorithm behavior under image cropping attacks.

## 📖 Note
This repository is part of a university assignment and is not intended for real-world cryptographic deployment.
