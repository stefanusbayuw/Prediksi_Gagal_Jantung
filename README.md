# Prediksi Kematian Akibat Penyakit Jantung

## Latarbelakang

Penyakit jantung merupakan salah satu penyakit yang menyebabkan kamtian cukup besar di dunia. Umumya penyakit jantung disebabkan gaya hidup tidak sehat dari pengidapnya. Untuk mengurangi risiko kematian akibat penyakit jantung, kali ini saya kan membuat model supervised learning untuk memprediksi kematian pasien akibat penyakit jantung. Molel ini dibuat dengan harapan tenaga kesehatan dapat lebih memfokuskan pasien dengan risiko kematian dan meminimalisir kematian yang disebabkan oleh penyakit jantung. Model yang akan dibuat akan menggunakan model supervised learning dengan menggunakan algoritme Random Forest dan algoritme Boosting.

## Model

Model yang digunakan pada prediksi gagal jantung adalah model Bagging - RandomForestClassifier. Model tersebut digunakan karena memiliki akurasi train 0.984472049689441 dan test 0.8666666666666667 meskipun model yang digunakan masih cenderung overfitting. Selain Model tersebut, saya juga membandingkan dengan beberapa model lain yaitu RandomForestClassifier, AdaBoostClassifier dan Bagging - AdaBoostClassifier namun memiliki nilai kaurasi yang cenderung lebih rendah daan overfitting.

Model yang dibuat dilakukan oversampling dengan SMOTE karena data yang dimiliki Imbalance.

## Pengembangan Kedepan

Pengembangan kedepan yang dapat dilakukan adalah dengan melakukan seleksi fitur yang akan digunakan pada model, mencoba menggunkaan algoritme lain atau melakukan undersampling untuk melakukan balancing data agar model memiliki akurasi yang tinggi dan goodfit.
