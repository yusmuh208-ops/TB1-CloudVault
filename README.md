# ☁️ CloudVault

## Smart Object Storage Manager

CloudVault adalah aplikasi sederhana berbasis Python untuk mengelola Object Storage menggunakan layanan Amazon S3 yang dijalankan melalui MiniStack sebagai emulator AWS lokal.

Project ini dibuat sebagai Tugas Besar Mata Kuliah Cloud Computing.

---

## 👤 Author

**Nama** : Muhammad Yusuf Anwar

**NIM** : 32602500068

**Kelas** : RPL LP MAARIF

---

## 📖 Deskripsi

CloudVault memanfaatkan library **Boto3** untuk berkomunikasi dengan layanan Amazon S3. Seluruh proses dijalankan secara lokal menggunakan MiniStack sehingga tidak memerlukan akun AWS maupun koneksi internet.

Aplikasi mampu melakukan pengelolaan file (object) pada bucket S3 melalui fungsi-fungsi dasar Object Storage.

---

## ✨ Fitur

- Membuat Bucket
- Menampilkan Daftar Bucket
- Upload File
- Menampilkan Daftar File
- Download File
- Menghapus File
- Pencarian File
- Storage Statistics
- Bucket Information
- Exit Program

---

## 🛠 Teknologi

- Python 3.13
- Jupyter Notebook
- Boto3
- MiniStack
- StackPort
- Amazon S3 API

---

## 📂 Struktur Project

```
TB1-CloudVault
│
├── CloudVault.ipynb
├── README.md
├── contoh.txt
├── contoh2.txt
├── docs
│   ├── ManualBook.pdf
│   └── Screenshot1.png
│   └── Screenshot2.png
│   └── Screenshot3.png
│   └── Screenshot4.png
│   └── Screenshot5.png
│   └── Screenshot6.png
│   └── Screenshot7.png
│   └── Screenshot8.png
│   └── Screenshot9.png
│   └── Screenshot10.png
│   └── Screenshot11.png
│   └── Screenshot12.png
```

---

## ⚙ Persiapan

Pastikan telah menginstall:

- Python
- JupyterLab
- boto3
- MiniStack
- StackPort

Jalankan MiniStack terlebih dahulu sebelum menjalankan notebook.

---

## ▶ Cara Menjalankan

1. Jalankan MiniStack.
2. Jalankan StackPort.
3. Buka JupyterLab.
4. Buka file **CloudVault.ipynb**.
5. Jalankan seluruh cell secara berurutan.
6. Gunakan fungsi-fungsi CloudVault sesuai kebutuhan.

---

## 📋 Fitur yang Diimplementasikan

### 1. Create Bucket

Membuat bucket baru pada Object Storage.

### 2. Upload File

Mengunggah file ke bucket.

### 3. List Files

Menampilkan seluruh file pada bucket.

### 4. Download File

Mengunduh file dari bucket.

### 5. Delete File

Menghapus file dari bucket.

### 6. Search File

Mencari file berdasarkan nama.

### 7. Storage Statistics

Menampilkan jumlah file dan total ukuran penyimpanan.

### 8. Bucket Information

Menampilkan informasi bucket yang digunakan.

---

## 📸 Hasil Pengujian

Seluruh fitur telah berhasil dijalankan menggunakan MiniStack sebagai emulator Amazon S3.

---

## 📄 Lisensi

Project ini dibuat untuk keperluan akademik pada Mata Kuliah Cloud Computing.