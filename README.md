# Tugas 3 Pembelajaran Mesin

| Nama                  |      NPM      | Kelas |
| --------------------- | :-----------: | :---: |
| Aditya Rizki Ramadhan | 2108107010002 |   A   |

# Studi Kasus

- Klasifikasi Pengidap Diabetes Menggunakan ANN

# Dataset

Dataset yang digunakan yaitu :

- [Diabetes Dataset - link Kaggle](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)
- [Diabetes Dataset - link csv](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)

# Source Code

- [ANN.ipynb](https://github.com/AditRizkii/Tugas-2-Pembelajaran-Mesin-2108107010002/blob/main/SVM_for_Classification.ipynb)

# Cara Menjalankan Code

- Install semua requirements yang diperlukan

```bash
pip install -r requirement.txt
```

- Jalankan semua cell code berurutan dari atas kebawah

# Perbandingan SVM dengan ANN

| Aspek                |                                                               SVM                                                                |                                                                         ANN                                                                         |
| -------------------- | :------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| `Kompleksitas Model` |                                  relatif sederhana dan memiliki kompleksitas yang lebih rendah                                   |                                          sangat kompleks dan dapat menangani masalah yang sangat kompleks                                           |
| `Waktu Pelatihan`    |                      cenderung lebih cepat dalam komputasi dan pelatihan terutama untuk dataset yang besar                       |                             memerlukan waktu pelatihan yang lebih lama, terutama untuk dataset yang besar dan kompleks                              |
| `Overfitting`        |                                           cenderung kurang rentan terhadap overfitting                                           |                         lebih rentan terhadap overfitting, terutama jika model terlalu kompleks atau jika data tidak cukup                          |
| `Penggunaan`         |     sering digunakan untuk klasifikasi dan regresi di mana dimensi data relatif rendah dan kompleksitas model dapat dikelola     | sering digunakan untuk klasifikasi dan regresi dalam kasus di mana dimensi data tinggi dan kompleksitas model dapat menangani masalah yang kompleks |
| `Akurasi`            | ![SVM_result](https://github.com/AditRizkii/2108107010002_Pertemuan_11_ANN/assets/92986198/1f50a27b-31a6-4153-8aee-e95d5777c6f8) |          ![ANN_result](https://github.com/AditRizkii/2108107010002_Pertemuan_11_ANN/assets/92986198/63ea9746-41c8-4b53-9bea-d6f066cba1ff)           |
