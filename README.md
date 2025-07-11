<<<<<<< HEAD
# Klasifikasi Gambar Sepatu, Sandal, dan Boot dengan CNN

Proyek ini bertujuan untuk membangun model klasifikasi gambar menggunakan Convolutional Neural Network (CNN) untuk membedakan antara tiga jenis alas kaki: sepatu, sandal, dan boot. Model ini dapat digunakan untuk berbagai keperluan seperti sistem rekomendasi produk, pengenalan gambar otomatis, dan aplikasi berbasis pengolahan citra lainnya.

---

## Tentang Dataset

### Konteks
Dataset ini terdiri dari 15.000 gambar grayscale beresolusi 136x102 piksel yang mewakili tiga kategori alas kaki:
- **Sepatu (Shoe)**
- **Sandal**
- **Boot**

Setiap kelas memiliki 5.000 gambar, yang menjadikan dataset ini seimbang dan cocok untuk tugas klasifikasi multikelas.

### Inspirasi
Dataset ini sangat ideal untuk latihan dan penerapan model klasifikasi multikelas menggunakan jaringan saraf tiruan (ANN) seperti **Convolutional Neural Network (CNN)**, serta untuk konversi model ke format deployment seperti TensorFlow.js dan TFLite.

---

## Struktur Folder
submission/
├── tfjs_model/ # Model versi TensorFlow.js (untuk aplikasi web)
│ ├── group1-shard1of1.bin
│ └── model.json
├── tflite/ # Model versi TensorFlow Lite (untuk aplikasi mobile)
│ ├── model.tflite
│ └── label.txt
├── saved_model/ # Model asli dalam format TensorFlow SavedModel
│ ├── saved_model.pb
│ └── variables/
├── notebook.ipynb # Notebook berisi proses pelatihan dan evaluasi
├── README.md # 
└── requirements.txt # Daftar dependensi Python

---

## Cara Menjalankan

1. Clone repo atau buka folder.
2. Install requirements:
   !pip install -r requirements.txt

---

## Jalankan Notebook
notebook.ipynb
=======
# Klasifikasi Gambar Sepatu, Sandal, dan Boot dengan CNN

Proyek ini bertujuan untuk membangun model klasifikasi gambar menggunakan Convolutional Neural Network (CNN) untuk membedakan antara tiga jenis alas kaki: sepatu, sandal, dan boot. Model ini dapat digunakan untuk berbagai keperluan seperti sistem rekomendasi produk, pengenalan gambar otomatis, dan aplikasi berbasis pengolahan citra lainnya.

---

## Tentang Dataset

### Konteks
Dataset ini terdiri dari 15.000 gambar grayscale beresolusi 136x102 piksel yang mewakili tiga kategori alas kaki:
- **Sepatu (Shoe)**
- **Sandal**
- **Boot**

Setiap kelas memiliki 5.000 gambar, yang menjadikan dataset ini seimbang dan cocok untuk tugas klasifikasi multikelas.

### Inspirasi
Dataset ini sangat ideal untuk latihan dan penerapan model klasifikasi multikelas menggunakan jaringan saraf tiruan (ANN) seperti **Convolutional Neural Network (CNN)**, serta untuk konversi model ke format deployment seperti TensorFlow.js dan TFLite.

---

## Struktur Folder
```plaintext
submission/
├── tfjs_model/              # Model versi TensorFlow.js (untuk aplikasi web)
│   ├── group1-shard1of1.bin
│   └── model.json
├── tflite/                  # Model versi TensorFlow Lite (untuk aplikasi mobile)
│   ├── model.tflite
│   └── label.txt            # Label kelas untuk klasifikasi
├── saved_model/             # Model asli dalam format TensorFlow SavedModel
│   ├── saved_model.pb
│   └── variables/           # Berisi variabel model
├── notebook.ipynb           # Notebook berisi proses pelatihan dan evaluasi
├── README.md                # Dokumentasi proyek ini
└── requirements.txt         # Daftar dependensi Python
```

---

## Cara Menjalankan

1. Clone repo atau buka folder.
2. Install requirements:
   !pip install -r requirements.txt

---

## Jalankan Notebook
notebook.ipynb
>>>>>>> 397c07d9c1347b969c444330395f1f95a29b61a4
