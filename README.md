# Tugas 3 Pembelajaran Mesin

| Nama                  |      NPM      | Kelas |
| --------------------- | :-----------: | :---: |
| Aditya Rizki Ramadhan | 2108107010002 |   A   |

# Studi Kasus

- Klasifikasi Pengidap Diabetes Menggunakan ANN

# Dataset

Dataset yang digunakan yaitu :

- [Diabetes Dataset - link Kaggle](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)
- [Diabetes Dataset - link csv](https://github.com/AditRizkii/2108107010002_Pertemuan_11_ANN/blob/main/data/diabetes.csv)

# Source Code

- [ANN.ipynb](https://github.com/AditRizkii/2108107010002_Pertemuan_11_ANN/blob/main/ANN.ipynb)
- [Contoh pada artikel menggunakan tensorflow pada python environment](https://github.com/AditRizkii/2108107010002_Pertemuan_11_ANN/blob/main/POIN_1.ipynb)

# Cara Menjalankan Code

- Install semua requirements yang diperlukan

```bash
pip install -r requirement.txt
```

- Jalankan semua cell code berurutan dari atas kebawah

# Perbandingan SVM dengan ANN

| Aspek                |                                                           SVM                                                            |                                                                         ANN                                                                         |
| -------------------- | :----------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| `Kompleksitas Model` |                              relatif sederhana dan memiliki kompleksitas yang lebih rendah                               |                                          sangat kompleks dan dapat menangani masalah yang sangat kompleks                                           |
| `Waktu Pelatihan`    |                  cenderung lebih cepat dalam komputasi dan pelatihan terutama untuk dataset yang besar                   |                             memerlukan waktu pelatihan yang lebih lama, terutama untuk dataset yang besar dan kompleks                              |
| `Overfitting`        |                                       cenderung kurang rentan terhadap overfitting                                       |                         lebih rentan terhadap overfitting, terutama jika model terlalu kompleks atau jika data tidak cukup                          |
| `Penggunaan`         | sering digunakan untuk klasifikasi dan regresi di mana dimensi data relatif rendah dan kompleksitas model dapat dikelola | sering digunakan untuk klasifikasi dan regresi dalam kasus di mana dimensi data tinggi dan kompleksitas model dapat menangani masalah yang kompleks |

# Perbandingan Akurasi

## SVM (Support Vector Machine):

![SVM_result](https://github.com/AditRizkii/2108107010002_Pertemuan_11_ANN/assets/92986198/1f50a27b-31a6-4153-8aee-e95d5777c6f8)

- Akurasi: 0,76
- SVM adalah algoritma pembelajaran yang digunakan untuk masalah klasifikasi dan regresi. SVM berusaha untuk menemukan hyperplane terbaik yang memisahkan dua kelas dalam ruang fitur. Dengan akurasi sebesar 0,76, model SVM telah mengklasifikasikan 76% data dengan benar pada dataset pengujian.
- Kelebihan:
  1.  Efektif dalam ruang fitur yang tinggi.
  2.  Tidak terlalu dipengaruhi oleh overfitting.
- Keterbatasan: Kurang fleksibel dalam menangani dataset yang sangat besar.

## ANN (Artificial Neural Network):

![ANN_result](https://github.com/AditRizkii/2108107010002_Pertemuan_11_ANN/assets/92986198/63ea9746-41c8-4b53-9bea-d6f066cba1ff)

- Akurasi: 0,80
- ANN adalah model komputasi terinspirasi dari struktur jaringan saraf manusia. Ini terdiri dari lapisan neuron yang saling terhubung dan mampu mempelajari pola yang rumit dalam data. Dengan akurasi sebesar 0,80, model ANN telah mengklasifikasikan 80% data dengan benar pada dataset pengujian.
- Kelebihan:
  1. Fleksibel dalam menangani dataset yang kompleks dan pola yang rumit.
  2. Mampu belajar dari data tanpa perlu spesifikasi model secara eksplisit.
- Keterbatasan: Rentan terhadap overfitting, terutama pada dataset yang kecil.

## Penjelasan Perbandingan:

Dalam kasus ini, ANN memberikan kinerja yang sedikit lebih baik dibandingkan dengan SVM, dengan akurasi sebesar 0,80 dibandingkan dengan 0,76. Ini menunjukkan bahwa ANN mampu menangkap pola yang lebih kompleks dalam data penyakit diabetes, yang mungkin sulit untuk ditangani oleh SVM. Namun, perlu dicatat bahwa kinerja model sangat tergantung pada berbagai faktor seperti ukuran dataset, kompleksitas masalah, dan pemilihan parameter. Oleh karena itu, pemilihan model harus didasarkan pada evaluasi yang cermat terhadap kebutuhan dan karakteristik khusus dari dataset dan masalah yang sedang dihadapi.
