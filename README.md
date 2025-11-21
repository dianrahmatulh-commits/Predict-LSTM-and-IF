# Predict LSTM and IF
Project ini merupakan implementasi dari skripsi saya dengan fokus pada prediksi curah hujan di Kota Pekanbaru menggunakan metode Long Short-Term Memory (LSTM) dan Isolation Forest

1. Deskripsi Penelitian
Curah hujan merupakan faktor penting dalam analisis iklim dan mitigasi bencana seperti banjir. Penelitian ini bertujuan untuk:
    - Membangun model prediksi curah hujan di Kota Pekanbaru menggunakan long short term memory (LSTM).
    - Mengintegrasikan teknik isolation forest dengan model LSTM untuk mendeteksi kejadian curah hujan di Kota Pekanbaru.
    - Mengetahui hasil evaluasi dari penerapan kedua model dalam memprediksi curah hujan dan deteksi anomali.

2. Dataset
    - Sumber data: situs resmi BMKG
    - Periode data: 2015–2024
    - Fitur yang digunakan:
        - Tanggal
        - Curah hujan (mm)
        - Rata-rata Suhu (Celcius) 
        - Rata-rata Kelembaban (%)
        - Rata-rata Kecepatan angin (m/s)
        - Arah angin terbanyak (°)
  
3. Metode Penelitian
     
     a. LSTM (Long Short-Term Memory)

     Digunakan untuk memprediksi nilai curah hujan pada periode selanjutnya berdasarkan pola historis.

     b. Isolation Forest

     Digunakan untuk mendeteksi anomali pada data curah hujan.

4. Hasil
    - Visualisasi Prediksi dan Aktual
      <img src="LSTM Predict.png" width="400">

