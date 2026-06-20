# Data Structure

## 1. Document Purpose  
Dokumen ini bertujuan untuk memberikan gambaran mengenai data yang digunakan dalam sistem, fungsi masing - masing data, serta hubungan antar data. 

## 2. Data Structure Overview  
Sistem ini menggunakan tiga jenis data yaitu Data Penyakit, Data Gejala, dan Data Relasi Diagnosis. Masing - masing data memiliki peran yang berbeda dalam sistem. Data Penyakit digunakan sebagai sumber informasi penyakit yang ditampilkan kepada pengguna, Data Gejala digunakan sebagai input dalam proses konsultasi, sedangkan Data Relasi Diagnosis digunakan untuk menghubungkan Data Gejala dan Data Penyakit dalam proses konsultasi. Ketiga data tersebut saling mendukung proses konsultasi dan penyampaian informasi kepada pengguna. 

## 3. Struktur Data Penyakit  
**Purpose**  
Data Penyakit digunakan sebagai sumber informasi penyakit yang ditampilkan kepada pengguna. 

**Stored Information**  
- Nama Penyakit digunakan sebagai identitas penyakit yang ditampilkan kepada pengguna.
- Deskripsi Penyakit digunakan untuk memberikan gambaran umum mengenai penyakit.
- Penanganan Awal Penyakit digunakan untuk menyediakan informasi penanganan awal yang dapat dipahami pengguna.

**System Usage**  
1. Digunakan untuk menampilkan informasi penyakit pada fitur Informasi Penyakit.
2. Digunakan untuk menampilkan informasi penyakit berdasarkan hasil analisis gejala pada fiturs Hasil Konsultasi.

**Data Relationships**  
Data Penyakit terhubung dengan Data Gejala melalui Data Relasi Diagnosis untuk mendukung proses konsultasi. 


