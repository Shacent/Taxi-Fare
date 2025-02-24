## **Taxi Fare Prediction: Prediksi Tarif Taksi Menggunakan Model Regresi**

### **📌 Latar Belakang**
Industri transportasi berbasis taksi sangat bergantung pada sistem penentuan tarif yang akurat dan transparan. Namun, fluktuasi dalam faktor-faktor seperti jarak tempuh, kondisi lalu lintas, jumlah penumpang, dan cuaca sering kali menyebabkan ketidakpastian dalam estimasi tarif.

Dengan menerapkan model regresi, kita dapat mengembangkan sistem prediksi tarif yang lebih akurat berdasarkan data historis perjalanan. Model ini akan membantu penyedia layanan taksi memberikan estimasi tarif yang lebih transparan, serta memungkinkan pengemudi dan pelanggan untuk mengantisipasi biaya perjalanan sebelum memulai perjalanan.

---

### **🎯 Tujuan Proyek**
Proyek ini bertujuan untuk membangun model machine learning berbasis regresi yang dapat memprediksi tarif perjalanan taksi dengan mempertimbangkan berbagai faktor seperti:
- **Jarak tempuh**
- **Durasi perjalanan**
- **Jumlah penumpang**
- **Kondisi lalu lintas**
- **Waktu dan hari perjalanan**
- **Cuaca**

Manfaat dari model ini:
✅ Meningkatkan akurasi estimasi tarif perjalanan.
✅ Meningkatkan transparansi dalam penentuan harga.
✅ Membantu pengemudi mengoptimalkan strategi perjalanan.
✅ Memudahkan pelanggan dalam perencanaan anggaran perjalanan.

---

### **💡 Permasalahan Bisnis**
1. **Estimasi Tarif yang Tidak Konsisten**: Pengguna sering kali tidak mendapatkan estimasi harga yang jelas sebelum perjalanan dimulai.
2. **Pengaruh Eksternal**: Tarif sering kali dipengaruhi oleh kondisi eksternal seperti lalu lintas dan cuaca, yang sulit diprediksi secara manual.
3. **Ketidakpastian bagi Pengemudi**: Pengemudi tidak selalu mengetahui apakah tarif yang dikenakan sudah optimal berdasarkan kondisi perjalanan saat itu.

Untuk mengatasi masalah ini, model prediksi ini dikembangkan untuk memberikan estimasi tarif berdasarkan data historis.

---

### **🔍 Tugas Machine Learning**
Proyek ini termasuk dalam kategori **regresi**, karena target variabel yang diprediksi adalah **Fare Amount (Tarif dalam USD)**, yang bersifat kontinu.

Model yang digunakan:
- **Gradient Boosting Regressor** (model terbaik yang dipilih berdasarkan evaluasi)

Metrik evaluasi yang digunakan:
📌 **Mean Absolute Error (MAE)**: 3.8068
📌 **Mean Squared Error (MSE)**: 49.5344
📌 **R² Score**: 0.9803 (akurasi tinggi)

---

### **📊 Hasil Model Machine Learning**
1. **Akurasi Model**: Model dapat memprediksi tarif perjalanan dengan error yang minimal.
2. **Dampak Bisnis**: Model membantu meningkatkan transparansi dan efisiensi dalam sistem penentuan tarif taksi.
3. **Implementasi Model**: Model dapat diintegrasikan ke dalam aplikasi atau sistem berbasis web untuk memberikan estimasi tarif secara real-time kepada pengguna.

---

### **🛠️ Rubrik/Kriteria Penilaian**
| Kriteria | Bobot | Deskripsi |
|----------|--------|-----------|
| **Pemahaman Data** | 20% | Kemampuan dalam melakukan eksplorasi data, menangani missing values, dan memahami distribusi data. |
| **Preprocessing Data** | 20% | Kualitas dalam membersihkan data, menangani outlier, dan melakukan feature engineering. |
| **Pemilihan Model** | 20% | Pemilihan algoritma regresi yang sesuai berdasarkan karakteristik dataset. |
| **Evaluasi Model** | 20% | Penggunaan metrik evaluasi seperti MAE dan RMSE untuk mengukur performa model. |
| **Kemudahan Penggunaan** | 20% | Model dapat digunakan secara praktis dengan input yang mudah dimasukkan dan dipahami oleh pengguna. |

---

### **📝 Contoh Prediksi Tarif**
**Input Data:**
- **Jarak Tempuh**: 80 km
- **Jumlah Penumpang**: 2
- **Tarif Dasar**: 3.5 USD
- **Tarif per km**: 1 USD
- **Tarif per menit**: 0.35 USD
- **Durasi Perjalanan**: 60 menit
- **Kondisi Lalu Lintas**: Rendah
- **Cuaca**: Hujan

**Hasil Prediksi:** 🏆 **$282.53**

---

### **🚀 Langkah Selanjutnya**
1️⃣ **Melakukan deployment model** ke dalam aplikasi berbasis web.
2️⃣ **Integrasi API** agar dapat digunakan oleh layanan taksi.
3️⃣ **Melakukan pengujian lebih lanjut** dengan dataset baru untuk meningkatkan akurasi prediksi.

🚖📊 **Proyek ini bertujuan untuk memberikan solusi praktis bagi industri transportasi!**
