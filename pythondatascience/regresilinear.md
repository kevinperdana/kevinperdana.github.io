## Machine Learning : Prediksi Harga Rumah dengan Regresi Linear (Satu Variabel)

### Pendahuluan
<img src="/pythondatascience/images/MachineLearning.jpg?raw=true"/>

Machine Learning adalah cabang aplikasi dari Artificial Intelligence (Kecerdasan Buatan) yang fokus pada pengembangan sebuah sistem yang mampu belajar "sendiri" tanpa harus berulang kali di program oleh manusia.

Aplikasi Machine Learning membutuhkan data sebagai bahan belajar (training) sebelum mengeluarkan output. Aplikasi sejenis ini juga biasanya berada dalam domain spesifik alias tidak bisa diterapkan secara general untuk semua permasalahan. 

### Output Debug
<img src="/pythondatascience/images/RegresiLinear0.jpg?raw=true"/>

Analisis Regresi Linear adalah metode statistika yang digunakan untuk membentuk model hubungan antara variabel terikat/dependen (Y) dengan satu atau lebih variabel bebas/independen (X). Berdasarkan banyaknya variabel bebas yang ada dalam model, Regresi Linear dibagi menjadi 2 jenis yaitu : Regresi Linear sederhana dan Regresi Linear berganda. Apabila banyaknya variabel bebas (X) hanya ada satu, maka disebut sebagai Regresi Linear sederhana. Sedangkan apabila terdapat lebih dari 1 variabel bebas (X) maka disebut sebagai Regresi Linear berganda.

<img src="/pythondatascience/images/RegresiLinear1.jpg?raw=true"/>
<img src="/pythondatascience/images/RegresiLinear2.jpg?raw=true"/>
<img src="/pythondatascience/images/RegresiLinear3.jpg?raw=true"/>
<img src="/pythondatascience/images/RegresiLinear4Revisi1.jpg?raw=true"/>
<img src="/pythondatascience/images/RegresiLinear5.jpg?raw=true"/>
<img src="/pythondatascience/images/RegresiLinear6.jpg?raw=true"/>
<img src="/pythondatascience/images/RegresiLinear7.jpg?raw=true"/>

***

### Download Dataset Data Rumah
[![](https://img.shields.io/badge/Data%20Rumah-Download%20Disini-critical?style=for-the-badge&logo=mathworks&logoColor=FFF)](https://github.com/kevinperdana/kevinperdana.github.io/raw/master/pythondatascience/datarumah.csv)

Save as pada Browser untuk menyimpan file CSV.

***

### Implementasi dengan Python. Zoom browser Anda agar dapat melihat kode dengan jelas.
<img src="/pythondatascience/images/RegresiLinearCode4.jpg?raw=true"/>

### Kesimpulan
Dari implementasi diatas, bahwa model sudah belajar berdasarkan datarumah.csv. Dan dilakukan input apabila luas rumah 138m2, model menetapkan harga rumah sebesar Rp.154.456.042
