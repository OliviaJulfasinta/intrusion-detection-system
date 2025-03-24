# intrusion-detection-system

Sistem deteksi serangan (IDS) menggunakan deep learning dengan dataset NSL-KDD.

## Dataset
Program ini menggunakan dataset NSL-KDD yang diunduh otomatis dari:
- [KDDTrain+.txt](https://raw.githubusercontent.com/defcom17/NSL_KDD/master/KDDTrain%2B.txt)
- [KDDTest+.txt](https://raw.githubusercontent.com/defcom17/NSL_KDD/master/KDDTest%2B.txt)

## Cara menggunakan

### Menggunakan Google Colab
1. Buka file [Intrusion_Detection_System.ipynb](Intrusion_Detection_System.ipynb) di GitHub 
2. Klik tombol "Open in Colab" di bagian atas notebook atau buka [link Colab langsung](https://colab.research.google.com/drive/1_VQwx-5Fdk9tlSw4A4DKWbcD9_658Ga_?usp=sharing)
3. Jalankan semua sel kode secara berurutan

### Menjalankan secara lokal
1. Clone repositori ini:
git clone https://github.com/OliviaJulfasinta/intrusion-detection-system.git
cd intrusion-detection-system

2. Instal dependensi:
pip install -r requirements.txt

3. Jalankan kode Python:
python intrusion_detection_system.py

### Model Pre-trained
Repositori ini menyediakan model pre-trained `ids_model.h5` yang telah dilatih dengan dataset NSL-KDD. sehingga dengan adanya model ini dapat:
- Langsung menjalankan proses evaluasi tanpa perlu melatih model dari awal
- Mendapatkan hasil yang sesuai dengan yang ditunjukkan dalam laporan

Untuk menggunakan model pre-trained:
1. Pastikan file `ids_model.h5` ada di direktori yang sama dengan kode
2. Kode secara otomatis akan memuat model jika file tersebut ditemukan

## Fitur
- Preprocessing data NSL-KDD
- Model deep learning menggunakan TensorFlow/Keras
- Visualisasi kurva ROC
- Evaluasi performa dengan laporan klasifikasi
