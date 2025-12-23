# breast-cancer-ml-analysis
Comparative analysis of machine learning models for breast cancer diagnosis

# breast-cancer-ml-analysis

Bu proje, Wisconsin Breast Cancer (Diagnostic) veri seti kullanılarak meme kanseri tanısında farklı makine öğrenmesi modellerinin performanslarının karşılaştırılmasını amaçlamaktadır. Logistic Regression, SVM, KNN ve Random Forest modelleri eğitilmiş; Accuracy ve ROC-AUC metrikleri ile değerlendirilmiştir. En iyi model için ayrıca Confusion Matrix ve Classification Report analizleri sunulmuştur.

## Veri Seti
- Dataset: Wisconsin Breast Cancer (Diagnostic)
- Hedef değişken: diagnosis (M: malignant, B: benign)

## Yöntem
- Eksik değer kontrolü
- Gereksiz sütunların kaldırılması
- Hedef değişkenin sayısallaştırılması (M=1, B=0)
- Train/Test split (%80/%20, stratify)
- StandardScaler ile ölçekleme
- Modellerin eğitimi ve karşılaştırılması (Accuracy, ROC-AUC)
- En iyi model için Confusion Matrix ve Classification Report

## Kullanılan Modeller
- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Random Forest

## Kurulum
```bash
pip install -r requirements.txt
