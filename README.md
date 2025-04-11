# 🧠 Autoencoder for Anomaly Detection on MNIST (Deep Learning 1 - Homework)

This project explores training an autoencoder on the MNIST dataset and using it for **unsupervised anomaly detection**. We reconstruct digits and use reconstruction error as an anomaly score, aiming to detect samples that significantly deviate from normal training data.

---

## 🧬 What’s Inside

- Train an **autoencoder** to reconstruct digits from the MNIST dataset
- Use **MSE reconstruction loss** as anomaly score
- ROC AUC evaluation of anomaly detection
- Heatmap visualization of anomalies
- 2D latent space projection using a bottleneck of size 2

---

## 📊 Results

- Reconstructed images preserve digit structure well  
- **AUC score**: 0.9933. It demonstrate strong separation between normal and anomalous digits.
- Heatmaps visually highlight anomaly regions  
- Latent space clusters digits with surprising clarity

---

## 🖼 Plots

All plots (reconstructions, heatmaps, scatter plots) saved to the `plots/` directory. They’re cute. You’re welcome.

---

## 🛠 Tech Stack

- PyTorch  
- Torchvision  
- NumPy  
- Scikit-learn  
- Matplotlib  
- tqdm
