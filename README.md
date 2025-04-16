# 📊 Decision Tree Classifier: Prediksi Diabetes

Proyek ini bertujuan untuk mengimplementasikan algoritma **Decision Tree** pada kasus klasifikasi kesehatan, khususnya untuk memprediksi apakah seseorang berpotensi mengalami diabetes berdasarkan data medis.

## 📁 Dataset

Dataset yang digunakan adalah **Pima Indians Diabetes Database** dari [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database), yang berisi informasi medis dari wanita keturunan Pima Indian di atas usia 21 tahun.  
Dataset ini terdiri dari 768 baris dan 9 kolom (termasuk label), dengan fitur-fitur seperti:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (1 = diabetes, 0 = tidak diabetes)

## 🧠 Model Machine Learning

Model yang digunakan:  
🔸 `DecisionTreeClassifier` dari Scikit-Learn dengan `criterion='entropy'`

Langkah-langkah:
1. Load dataset dan cek deskripsi data
2. Visualisasi korelasi antar fitur
3. Split data ke dalam training dan testing (70:30)
4. Training model Decision Tree
5. Evaluasi model dengan:
   - Classification report
   - Confusion matrix
   - Visualisasi pohon keputusan
6. Prediksi data baru

## 🔍 Hasil Evaluasi

Model berhasil dikembangkan dan dievaluasi menggunakan metrik:

- **Akurasi**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**
- **Visualisasi pohon keputusan (Decision Tree Plot)**


## 📌 Tools & Library

- Python
- Jupyter Notebook / Google Colab
- Scikit-learn
- Pandas
- Seaborn
- Matplotlib

