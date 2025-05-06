# 🪨📄✂️ Proyek Klasifikasi Batu-Gunting-Kertas

**Nama:** Ammar Qurthuby  
**NPM:** 2208107010031

---

## 📚 Deskripsi Proyek
Proyek ini bertujuan untuk membangun sistem klasifikasi gambar menggunakan pendekatan **Deep Learning** dengan memanfaatkan **Transfer Learning** dan arsitektur **MobileNetV2**. Gambar yang akan diklasifikasikan terdiri dari tiga kategori utama:  
- Batu  
- Kertas  
- Gunting  

Model yang dilatih akan diintegrasikan ke dalam aplikasi backend berbasis **FastAPI**, memungkinkan sistem untuk menerima input gambar dan memberikan prediksi secara langsung melalui REST API. Selain itu, terdapat antarmuka pengguna berbasis **Streamlit** untuk mempermudah interaksi dengan aplikasi.

---

## 🛠️ Teknologi yang Digunakan
- **TensorFlow / Keras** → Digunakan untuk membangun dan melatih model klasifikasi gambar
- **FastAPI** → Backend API yang menangani permintaan dan prediksi
- **Uvicorn** → Server ASGI yang menjalankan aplikasi FastAPI
- **Pillow (PIL)** → Digunakan untuk pemrosesan dan manipulasi gambar
- **NumPy** → Digunakan untuk manipulasi data numerik
- **scikit-learn** → Evaluasi model dengan confusion matrix dan classification report
- **Streamlit** → Framework frontend berbasis web untuk antarmuka pengguna

---

## 📂 Struktur Folder Proyek
```bash
project-root/
├── backend/
│   └── main.py              # Backend FastAPI
├── frontend/
│   └── main.py              # Antarmuka pengguna Streamlit
├── dataset/
│   ├── rock/
│   ├── paper/
│   └── scissors/
├── model/
│   └── best_transfer.keras  # Model hasil pelatihan
├── notebook.ipynb           # Notebook untuk eksplorasi dan pelatihan
├── requirements.txt         # Daftar dependensi
└── README.md                # Dokumentasi proyek

---
