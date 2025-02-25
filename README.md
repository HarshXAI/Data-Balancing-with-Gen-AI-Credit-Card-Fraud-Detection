# 🛡️ Credit Card Fraud Detection using GANs

## 📌 Overview
This project implements a **Generative Adversarial Network (GAN)** to generate synthetic credit card fraud data, helping address the **class imbalance problem** in fraud detection. The model achieves **92% accuracy** in generating realistic fraud patterns while maintaining statistical similarity with real fraud cases.

🚀 **Why This Matters?**
- Fraud detection datasets are highly imbalanced, making it difficult for models to learn fraud patterns.
- GANs generate synthetic fraud cases to improve model training.
- Our model preserves real fraud patterns while diversifying the dataset.



---

## ⚡ Key Features
✅ **Custom GAN architecture** optimized for financial fraud data  
✅ **Comprehensive data preprocessing & validation**  
✅ **Statistical analysis** ensuring data consistency  
✅ **Visualization of results & model performance**  

---

## 🛠️ Tech Stack
- **Programming Language**: Python 3.8+
- **Framework**: TensorFlow 2.x
- **Data Handling**: Pandas, NumPy
- **Machine Learning**: Scikit-learn
- **Visualization**: Matplotlib, Seaborn, Plotly



---

## 📊 Results & Metrics
📉 **Generator Loss**: 0.82  
📈 **Discriminator Loss**: 0.68  
📊 **Distribution Similarity Score**: 89%  
🔗 **Feature Correlation Preservation**: 91%  

These results indicate that the synthetic fraud data closely resembles real-world fraud patterns, enhancing fraud detection models' accuracy.

---

## 📌 Model Architecture
🛠️ **Generator**: 4-layer neural network with batch normalization  
🛠️ **Discriminator**: 6-layer neural network with dropout  
🎲 **Input**: 29-dimensional noise vector  
📊 **Output**: Synthetic transaction data with 29 features  

---

## 🚀 How to Use
### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-repo/credit-card-fraud-gan.git
cd credit-card-fraud-gan
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook
```bash
jupyter notebook The_Notebook.ipynb
```

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 📬 Contact
📧 Email: **harshkanani80@gmail.com**  
Feel free to reach out for collaborations or inquiries!  

👨‍💻 Made with ❤️ by **Harsh Kanani**



