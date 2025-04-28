# 🎶 Klasifikasi Komponen Musik menggunakan ML

Fungsi Utama:
Program ini digunakan untuk memprediksi komposer (Beethoven, Mozart, Chopin, atau Schubert) dari sebuah file musik berformat MIDI berdasarkan ekstraksi fitur musik dan model machine learning.

## 🛠️ Teknologi dan Library yang Digunakan
1. pretty_midi: Membaca file MIDI dan mengambil informasi musik.
2. music21: Manipulasi dan analisis musik simbolik (sedikit digunakan di awal, tapi tidak banyak dipakai di kode ini).
3. scikit-learn:
   - Untuk preprocessing (standarisasi data).
   - Untuk model klasifikasi (Random Forest dan K-Nearest Neighbors).
   - Untuk evaluasi model (classification report, confusion matrix).
4. numpy dan os: Untuk manipulasi array dan file system.
