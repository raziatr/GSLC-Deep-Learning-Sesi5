# Tugas GSLC Sesi 5 — Transfer Learning untuk Klasifikasi Citra dengan Data Terbatas

ResNet-18 pada Oxford-IIIT Pet (10 kelas): B1 scratch, B2 feature extraction, B3 progressive fine-tuning, B4 uji augmentasi, B5 EfficientNet-B0 / MobileNetV3-Small, plus failure analysis (C3) dan Grad-CAM (C5).

## Cara menjalankan (Google Colab, GPU T4)
1. Runtime → Change runtime type → **T4 GPU**.
2. Unggah `GSLC_Transfer_Learning.ipynb` ke Colab (direktori kerja yang sama).
3. **Runtime → Run all.** Dataset dan bobot pretrained diunduh otomatis. Perkiraan waktu total: puluhan menit (tergantung runtime).
4. Hasil muncul di `outputs/logs/` (CSV/JSON mentah) dan `outputs/figures/` (tabel dan angka terisi otomatis dari log). `2802559326_Fahrurrazi.zip` otomatis diunduh.
