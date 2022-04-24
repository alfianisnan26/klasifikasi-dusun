[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alfianisnan26/klasifikasi-dusun/HEAD?labpath=train.ipynb)
## Klasifikasi Jenis Wisata Desa menggunakan Machine Learning
- Kategori  : Supervised machine learning
- Algoritma : Support vector machine
## Cara run
### Install dan Buat Virtualenv
```bash
# Install
python -m pip install virtualenv

# Creating Virtual Environment
python -m virtualenv venv

# Activate Virtual Environment
# Windows
./venv/Scripts/activate

# MacOS, Linux
source ./venv/bin/activate
```
### Install dependensi
```bash
python -m pip install -r requirements.txt
```
### Jika memerlukan noteboo
```bash
# Install
python -m pip install notebook

# Open
python -m notebook
```

## Referensi
- Tutorial : https://data-flair.training/blogs/iris-flower-classification/
- KNN : https://www.upgrad.com/blog/knn-classifier-for-machine-learning/
- SVM : https://www.javatpoint.com/machine-learning-support-vector-machine-algorithm
- Scikit SVC : https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html