# UAS Pengolahan Citra Digital Project: Image to Text Recognation

## Project
**Judul**: Image to Text Recognation  
**MataKuliah**: Pengolahan Citra Digital 2023C 

**Anggota Tim (Kelompok 5 - 2023C)**:  
1. Anisa Khaynun Najwa (23031554007)
2. Thea Bayu Revalina (23031554035)
3. Metha Nailis Saadah (23031554159)

## Pendahuluan 
Kemajuan teknologi telah mendorong perkembangan pemrosesan citra digital, termasuk penerapan Optical Character Recognition (OCR) untuk mengekstraksi teks dari gambar secara otomatis. Namun, akurasi OCR dapat menurun akibat kualitas gambar yang rendah, pencahayaan buruk, atau karakter teks yang tidak jelas. Untuk mengatasi hal tersebut, diperlukan tahapan preprocessing (seperti normalisasi, peningkatan kontras, dan penghapusan noise) serta segmentasi sebelum penerapan metode deep learning.
Thresholding merupakan salah satu teknik segmentasi yang umum digunakan untuk memisahkan teks dari latar belakang. Kombinasi thresholding dan Convolutional Neural Network (CNN) dapat meningkatkan akurasi deteksi teks, terutama pada gambar dengan bentuk teks yang bervariasi.

## Tujuan
1. Mengidentifikasi pengaruh metode segmentasi threshold terhadap akurasi OCR.
2. Menganalisis perbandingan hasil antar parameter threshold pada proses OCR.
3. Mengidentifikasi nilai threshold yang menghasilkan performa terbaik pada proses segmentasi gambar.


## Struktur Folder
```
📁 Pengolahan Citra/
├── README.md               # Dokumentasi proyek (file ini)
├── PCD_OCR.ipnyb           # Berisi notebook proses dan kode yang dijalankan 
├── image_pcd.zip           # Dataset yang digunakan 
├── requirements.txt        # Daftar pustaka yang dibutuhkan
```
---

## Cara Menjalankan code 
1. **Clone Repository**:
   ```bash
   git clone <repository-url>
   cd Pengolahan_Citra
   ```
2. **Instal Dependensi**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Jalankan Notebook**:
   Buka `PCD_OCR.ipynb` menggunakan Jupyter Notebook atau Google Colab, lalu jalankan sel-sel kode secara berurutan.
4. **Dataset**:
   Pastikan file `image_pcd.zip` berada di direktori yang sama dengan notebook.

---

## Tools yang Digunakan
- **Python** : Bahasa pemrograman utama untuk analisis dan pemrosesan citra.
- **OpenCV (cv2)** : Untuk preprocessing dan segmentasi gambar (thresholding).
- **EasyOCR** : Untuk ekstraksi teks dari gambar.
- **Matplotlib** : Untuk visualisasi hasil preprocessing dan thresholding.
- **NumPy** : Untuk manipulasi array dan operasi matematika.

---

## Lisensi
Proyek ini dibuat untuk keperluan akademik sebagai bagian dari tugas UAS Pengolahan Citra Digital untuk Kelompok 5 (2023C).