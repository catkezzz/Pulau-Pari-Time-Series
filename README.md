# Pulau-Pari-Time-Series
## Pendahuluan

### Gambaran Dataset
Data merupakan informasi dari Google Trend tentang seberapa populer kata kunci `Pulau Pari` telah disearching di Google. Dataset terdapat dua kolom yaitu:

- Week: Data, berisi tanggal pertama di setiap minggu
- Pulau Pari: (Indonesia): berisi persentase popularitas maksimum dari kata kunci yang dicari. Pembagian persentasenya adalah:
    - 0 : tidak ada data,
    - 50 : popularitas hanya setengah,
    - 100 : sangat populer

### Objective
Sebagai data scientist di perusahaan travel agent, ingin membuat model machine learning Time Series untuk memprediksi bagaimana popularitas wisata Pulau Pari selama satu tahun ke depan. Dengan wawasan ini, bisa diberikan ke perusahaan untuk menyesuaikan strategi pemasaran supaya sesuai dengan popularitas market. 

Akan dibuat model dengan algoritma SARIMA dan ARIMA, performa model dinilai dengan metric regresi yaitu Mean Absolute Error (MAE) dan R Squared, dan juga nilai entropi AIC

## EDA
![image](https://github.com/user-attachments/assets/6694fefd-f72c-4d4c-b78f-85dd3842154c)

## Time Series Decomposition
Decomposition Multiplicative

![image](https://github.com/user-attachments/assets/f3d3a0a1-0ca3-4f73-85d9-8a8a3de23411)

## Stationary
Pemeriksaan Stationary data dan melakukan Differencing jika diperlukan

![image](https://github.com/user-attachments/assets/c9997c6f-2cac-46a0-a653-25954692e69d)

Tanpa melakukan differencing sudah stationary

## Forecasting Menggunakan SARIMA
![image](https://github.com/user-attachments/assets/90396025-8854-4462-b9ce-2ee631ef7f95)

Persentase relatif rendah, tetapi terdapat kenaikan secara signifikan diantara bulan april sampai akhir bulan mei






