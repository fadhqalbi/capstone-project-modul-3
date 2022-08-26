# capstone-project-modul-3

Dokumentasi capstone project modul tiga, yang berjudul **California House Price Prediction** dari dataset data_california_house.csv yang tersedia di [Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

## Deskripsi
Projek ini merupakan bagian dari pembalajaran data science di Purwadhika, untuk melakukan analisis regresi menggunakan machine learning dengan pendekatan analisis:
1. Algoritma: Random Forest Regressor
2. Metrik Evaluasi:
  - RMSE: untuk mengukur standar deviasi residu dari hasil prediksi dengan nilai sebenrarnya
  - MAE: alternatif untuk data dengan banyak outlier di residu
  - RMSLE: pengukuran rmse dalam skala logaritmik karena rentang nilai prediksi nya besar, dalam skala ratusan ribu USD
  - MAPE: mengukur relative error dalam persen
  - R-Square: mengukur kemampuan model dalam menjelaskan hasil prediksi
 3. Metodologi:
  ![image](https://user-images.githubusercontent.com/36106884/186903919-dd6357a5-0d64-45dd-91c7-4a82d425455a.png)
 
 ## Hasil
 ![image](https://user-images.githubusercontent.com/36106884/186905218-02e267aa-0dec-4446-8a0d-f8233c002e35.png)

**Kesimpulan:** Pengurangan fitur efektif dalam meningkatkan kinerja model yang ditandai dengan penurunan skor metrik RMSE, MAE, RMSLE, & MAPE dan peningkatan skor R-Square
