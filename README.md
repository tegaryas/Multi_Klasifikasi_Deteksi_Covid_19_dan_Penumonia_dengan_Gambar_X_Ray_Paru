# Deteksi Covid Menggunakan X-Ray Paru

Petunjuk Running Tinggal Run All Namun Dataset harus terlebih dahulu diupload ke GDrive anda. Silahkan melakukan konfigurasi sesuai kemauan anda.Terimakasih


## Detail Dataset
Nama Dataset            : COVID-19 Radiography Database

Link Dataset		: https://www.kaggle.com/tawsifurrahman/covid19-radiography-database

Banyak Kelas            : 3

Banyak dataset	        : Total      : 1232
                          Training   : 1121 
                          Validation : 60 
                          Testing    : 51  

## Model Parameter
Machine Learning Library: Keras

Base Model              : InceptionV3

Optimizers              : Adam

Loss Function           : categorical_crossentropy

Metrics			: Accuracy

Untuk Custom Deep Convolutional Neural Network : 

Training Parameter

Batch Size              : 32
Number of Epochs        : 30

Output (Prediction/ Recognition / Classification Metrics)

Testing

Accuracy (F-1) Score    : 96.08%

---------------------------------------------------------
---------------------------------------------------------
	      precision    recall  f1-score   support

       Covid       1.00      0.88      0.94        17
      Normal       0.94      1.00      0.97        17
   Pneumonia       0.94      1.00      0.97        17

    accuracy                           0.96        51
   macro avg       0.96      0.96      0.96        51
weighted avg       0.96      0.96      0.96        51
---------------------------------------------------------
---------------------------------------------------------
