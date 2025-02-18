
# ✍️ Recognizing Handwritten Digits using Scikit-Learn  


## **📖 Overview**  
This project demonstrates how to **recognize handwritten digits** using **Scikit-Learn**. We train an **MLP (Multi-Layer Perceptron) model** on the **Digits dataset**, a well-known dataset for optical character recognition (OCR).  

🔹 **Machine Learning Library:** Scikit-Learn  
🔹 **Dataset:** Scikit-Learn Digits Dataset (0-9 handwritten numbers)  
🔹 **Model Used:** Multi-Layer Perceptron (MLP) Classifier  
🔹 **Techniques Used:** Feature Scaling, Model Training, Evaluation  

---


## **📦 Installation & Setup**  
To run this project locally, follow these steps:  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/thenewsyria/Recognizing-HandWritten-Digits-in-Scikit-Learn.git
cd Recognizing-HandWritten-Digits-in-Scikit-Learn
```

### **2️⃣ Create a Virtual Environment (Optional but Recommended)**  
```bash
python -m venv venv  
source venv/bin/activate  # On Windows: venv\Scripts\activate  
```

### **3️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **4️⃣ Run the Jupyter Notebook**  
```bash
jupyter notebook
```
Open **Handwritten_Digits.ipynb** and run the cells step by step.

---

## **🛠️ Technologies Used**  
- **Python** 🐍  
- **Scikit-Learn** 🤖  
- **NumPy & Pandas** 📊  
- **Matplotlib & Seaborn** 📈  
- **MLP Classifier for Handwriting Recognition** ✍️  

---

## **🔢 Dataset Description**  
The **Digits dataset** contains **1,797 images (8x8 pixels)** of handwritten digits (0-9). Each image is represented as a **flattened feature vector** of 64 values (grayscale intensity).  

---

## **📊 Model Training & Testing**  
### **1️⃣ Data Preprocessing**  
- Load the **Digits dataset** using `sklearn.datasets.load_digits()`.  
- Normalize pixel values for better convergence.  
- Split data into **training (80%) and testing (20%)**.  

### **2️⃣ Train the MLP Classifier**  
```bash
python src/train.py
```
- Uses a Multi-Layer Perceptron (MLP) model with **ReLU activation**.  
- Optimized using **Adam optimizer**.  

### **3️⃣ Evaluate the Model**  
```bash
python src/test.py
```
- Measures **accuracy, precision, recall, and F1-score**.  

---

## **📈 Results & Performance**  
✅ Achieved **~98% accuracy** on test data.  
✅ Optimized using **Hyperparameter Tuning**.  
✅ Improved training efficiency with **Feature Scaling**.  

---


## **📌 Future Improvements**  
🔹 Implement **CNNs with TensorFlow** for better accuracy.  
🔹 Extend the project for **real-time handwriting recognition**.  
🔹 Deploy as a **web application** using Flask/Streamlit.  

---

## **🤝 Contributing**  
Contributions are welcome! Follow these steps:  
1. **Fork the repository**  
2. **Create a feature branch** (`git checkout -b feature-name`)  
3. **Commit your changes** (`git commit -m "Add feature X"`)  
4. **Push to GitHub** (`git push origin feature-name`)  
5. **Open a Pull Request**  

---

## **📄 License**  
This project is licensed under the **MIT License**.  

---

## **📞 Contact**  
📧 **Email:** omar123321123mohamed@gmail.com  
🔗 **LinkedIn:** [Omar Alhaj Ali](https://www.linkedin.com/in/omar-alhaj-ali-3a76aa254/)  
```
