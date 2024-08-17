
# New Product Development at Big Ramen Companies
![image](/bigramen.png)


_Dibuat guna menganalisis dataset diluar dari perusahaan Big Ramen Untuk Menentukan Produk baru yang akan dibuat._

---

## Background

Perusahaan Ramen Cup yang bernama "Big Ramen", adalah sebuah startup yang berbasis di kota besar yang terinspirasi oleh popularitas dan permintaan yang terus meningkat untuk makanan cepat saji berkualitas tinggi. Big Ramen berkomitmen untuk menciptakan pengalaman makanan yang unik dan memuaskan bagi pelanggan mereka.Karena akhir akhir ini minat konsumen dalam Ramen beragam maka itu adalah sebuah tantangan tersendiri bagi perusahaan, oleh karena itu Dalam hal ini karena perusahaan Big Ramen menginginkan produk baru dengan mempertimbangkan minat dan kualitas berdasarkan Rating, review dari berbagai negara dan brand pesaing lainnya, Tim di BigRamen berusaha untuk terus mengembangkan variasi rasa dan tekstur ramen mereka,Meskipun hanya memiliki 4 macam produk ramen, dengan memperhatikan tren dan preferensi pasar yang berkembang. Mereka percaya bahwa dengan menggabungkan penelitian pasar yang cermat dan kreativitas, mereka dapat menghasilkan produk ramen cup yang tidak hanya memuaskan selera, tetapi juga memenuhi harapan pelanggan yang semakin tinggi.

## Objective

Big Ramen hanya memiliki 4 macam variasi ramen dan ingin Berfokus pada bagaimana Big Ramen dapat secara efektif menggunakan data ulasan dan rating pelanggan yang mereka miliki dalam setiap negara dan brand pesaing lainnya untuk mengidentifikasi peluang inovasi produk. Hal ini akan melibatkan analisis mendalam terhadap data ulasan dan rating yang ada, penggunaan metode analisis yang tepat untuk mengungkap pola dan tren konsumen, dan pengembangan strategi yang dapat diimplementasikan untuk meningkatkan kualitas dan kepuasan pelanggan.

## SMART(Specific, Measurable, Achievable, Relevant)
### Specific(mengurangi kesalahan dalam menentukan produk Ramen baru dalam perusahaan)
* Peminat Ramen yang beragam membuat perusahaan sulit menentukan produk ramen apa yang cocok untuk produksi karena produk Big Ramen hanya memiliki 4 macam Ramen.
* Data yang diperoleh melimpah dalam menentukan produksi Ramen apa yang akan dibuat, Tim Big Ramen perlu menemukan cara efektif untuk menganalisis informasi tersebut, mengungkap pola dan tren konsumen yang relevan, serta mengembangkan strategi.
### Measurable(Goals)
* Menemukan solusi efektif dalam identifikasi peluang inovasi produk dengan melihat kepuasan peminat Ramen dalam berbagai negara dan brand berdasarkan Rating Produk yang mencapai nilai rating 4.5 sampai 5
* Meningkatkan proses analisis data, dan membuat produk baru yang unik berdasarkan ulasan/Review dari berbagai Brand yang diasumsikan dalam review ini, nilai yang terbanyak dalam ulasan menjadi pertimbangan dalam pembuatan varian ramen baru
### Achievable (Strategi dalam menemukan varian baru Ramen)
* Merancang analisa Tim Big Ramen dengan menggunakan sumber yang tersedia, seperti data ulasan dan rating pelanggan.
* Memberikan hasil output yang akan digunakan tim produksi untuk membuat produk baru Ramen.
### Relevant
* Meningkatkan varian baru dalam Ramen yang unik dan memberikan produk baru dalam bentuk yang akan ditentukan berdasarkan ulasan dan rating yang paling bagus dalam berbagai negara dan brand tertentu yang mana akan menjadi kunci pertumbuhan perusahaan Big Ramen.
### Time Bound
* Menetapkan jangka waktu yang jelas, yaitu 3 bulan untuk mencapai peningkatan dalam inovasi produk ramen, dan 2 bulan untuk produksi Ramen baru guna menambah varian yang sebelumnya 4 menjadi 5 macam. Diharapkan setelah mengimplementasikan strategi penggunaan data ulasan dan rating pelanggan.

## Problem Statement

Peningkatan produksi Ramen yang masih sedikit yaitu 4 macam saja dan perusahaan ingin menambah varian baru menjadi 5 varian, mengembangkan varian Ramen ini bukan hanya untuk menambah 1 macam saja tetapi untuk memproduksi varian Ramen unik berdasarkan nilai ulasan dan Rating dari Brand pesaing dengan memanfaatkan waktu selama 5 bulan dalam menganalisa Produk Ramen apa saja dan 2 bulan dalam memproduksi Ramen baru demi menciptakan pengalaman makanan yang unik dan memuaskan bagi pelanggan mereka.

---

## Penjabaran Masalah Menggunakan 5W+1H
    - Apa saja brand Ramen di berbagai negara?
    - Negara mana saja dengan rata-rata % rating terbaik?
    - Bagaimana nilai Rating didalam negara?
    - Bagaimana Review dalam setiap negara tentang Ramen?
    - Bagaimana peringkat ulasan dan Rating yang diterima di suatu Brand atau negara?apakah ada perbedaan-
      yang signifikan dalam rating dari gaya kemasan/Style?
    - Kapan Hasil output akan bisa di distribusikan ke tim Produksi?
  
Pertanyaan-pertanyaan/penjabaran masalah di atas dapat dijawab dengan data visualisasi dan analisis statistik.

---

## Data Source 

Dataset yang digunakan : [Kaggle.com](https://www.kaggle.com/datasets/residentmario/ramen-ratings?resource=download). Dataset ini digunakan karena team Develope percaya bahwa dengan menggabungkan penelitian pasar yang cermat dan kreativitas, mereka dapat menghasilkan produk ramen cup yang tidak hanya memuaskan selera, tetapi juga memenuhi harapan pelanggan yang semakin tinggi karena dataset ini di kumpulkan dari berbagai macam negara dengan minat rasa Ramen dan bentuk kemasan yang berbeda, dan akan menjadi acuan dalam pembetukan Ramen Baru untuk perusahaan Big Ramen.

---

## Notebook Instructions
1. Melakukan data cleaning dan preprocessing pada notebook
2. Notebook mengikuti format berikut:
  1. Perkenalan
      > Bab pengenalan .

  2. Identifikasi Masalah
      > Bab ini  menyantumkan **topik permasalahan**, **problem statement**, **latar belakang**, serta **penjabaran masalah** yang ingin dianalisis menggunakan metode statistik dan data Visualisasi.

  3. Data Loading 
      > Bagian ini berisi proses *data loading* dan eksplorasi data sederhana. mencantumkan query SQL data yang di-load jika menggunakan dari BigQuery atau server SQL lainnya. Menampilkan datanya.

  4. Data Cleaning
      > Bagian ini berisi proses penyiapan data berupa data cleaning sebelum dilakukan *explorasi data* lebih lanjut. Proses cleaning dapat berupa memberi nama baru untuk setiap kolom, mengisi missing values, menghapus kolom yang tidak dipakai, dan lain sebagainya.

  5. Analisis dan perhitungan
      > Bagian ini berisi proses analisis, penjelasan, perhitungan statistik deskriptif, inferensial, serta pembuatan visualisasi data. Untuk visualisasi data wajib memberikan insight di tiap visualisasinya.

  6. Pengambilan Kesimpulan
      > Pada bab terakhir ini, **Berisi** kesimpulan yang mencerminkan solusi/rekomendasi/jawaban atas permasalahan yang diangkat serta menarik benang merah dari seluruh analisis dan perhitungan secara singkat, jelas, dan padat.

3. Notebook disimpan dengan judul h8dsft_Milestone1_bagus_adji.ipynb.

---

## Push Project

- Untuk Anlisa yang sudah dibuat dalam notebook ini terdapat Dashboard  [Tableau.com](https://public.tableau.com/app/profile/bagus.adji.kusuma/viz/DataRamen/DataRatingdanReviewRamenberbagaiNegara?publish=yes):
  * file bernama `data_Ramen1.csv` adalah data yang sudah di clean dan siap digunakan untuk Analisa.
  * file bernama `README.txt` berisi URL Dashboard.
  * file bernama `h8dsft_Milestone1_bagus_adji.ipynb` berisi semua analisa yang sudah dibuat dari loading data hingga Analisa terkait produk Ramen
  * bentuk isi repository dengan Analisa yang sudah buat.
    ```
    ├── h8dsft_Milestone1_bagus_adji.ipynb
    ├── data_Ramen1.csv
    ├── ramen_ratings_before_clean.csv
    └── README.md
    └── README.txt
    └── bigramen.png
    ```
---
## Result

Dalam analisis ini, dataset yang terkait dengan permainan League of Legends, khususnya pada fase 10 menit pertama dari pertandingan Ranked Diamond, telah melalui beberapa tahap penting untuk meningkatkan hasil model. Setelah melakukan eksplorasi data, penanganan nilai yang hilang, penanganan outliers, serta scaling dan PCA, berbagai model telah diuji dan dievaluasi menggunakan metrik F1-Score. Model SVM menunjukkan performa yang paling baik dalam hal F1-Score setelah proses tuning, sehingga dipilih sebagai model terbaik. Skor menunjukkan bahwa model tersebut memiliki kinerja yang cukup seimbang, sekitar 71%-73% secara keseluruhan.

## Conclusion & Business Impact
Business Impact pada Riot sebagai Developers Game:

1. Peningkatan Keseimbangan Permainan: Dengan menggunakan model yang telah dioptimalkan, DevOps Riot dapat memperoleh wawasan yang lebih baik tentang keseimbangan permainan di 10 menit pertama pada peringkat Diamond. Hal ini dapat membantu dalam menyesuaikan mekanika permainan atau mengubah parameter tertentu untuk memastikan bahwa pertandingan lebih seimbang dan adil antara Blue Team dan Red Team.
2. Optimasi Pengalaman Pemain: Dengan mengidentifikasi dan mengatasi ketidakseimbangan di fase awal permainan, Riot dapat meningkatkan pengalaman permainan bagi pemain di tier Diamond. Ini dapat mengurangi frustrasi yang disebabkan oleh ketidakseimbangan dan meningkatkan kepuasan pemain, yang pada gilirannya dapat meningkatkan retensi dan keterlibatan pemain.
3. Strategi Pengembangan Berbasis Data: Analisis yang dilakukan dengan metrik F1-Score menyediakan basis yang solid untuk pengambilan keputusan berbasis data. Riot dapat menggunakan informasi ini untuk menginformasikan strategi pengembangan dan pembaruan game, serta membuat penyesuaian yang diperlukan untuk meningkatkan kualitas dan keseimbangan permainan.
4. Kinerja Model yang Terukur: Dengan memilih model SVM berdasarkan F1-Score, Riot dapat menggunakan pendekatan yang terbukti efektif untuk menganalisis dan memprediksi keseimbangan permainan. Ini memastikan bahwa model yang digunakan untuk analisis memiliki performa yang optimal dan dapat diandalkan dalam konteks yang dinamis dari permainan MOBA.

Secara keseluruhan, hasil dari analisis ini memberikan alat yang berharga bagi DevOps Riot untuk membuat penyesuaian yang meningkatkan keseimbangan dan kualitas permainan, dengan tujuan akhirnya adalah melihat apakah permainan tersebut memberikan hasil kemenangan yang tepat bagi setiap team yang bermain pada 10 menit pertama pada Rank Diamond agar menghindari kesalahan sistem atau mungkin kecurangan dari setiap pemainnya

## Try App [HERE](https://huggingface.co/spaces/Bagusaja/Machine_Learning_concept_Milestone_2)
### Notes
- Saat menjalankan link diatas harap pastikan **restart Space** pada Hugging Face kemudian tunggu hingga App muncul, mungkin membutuhkan waktu untuk load appnya.
- Dalam App terdapat Bar kiri dimana berisi EDA(Exploratory Data Analyst) dan Bardown kedua berisi Prediction.
- Laman Prediction silahkan sesuaikan atribut pada gameplay yang sudah anda mainkan misalnya, dan lakukan **predict** dipaling bawah laman page untuk melihat hasilnya.
- Terakhir Enjoy The App
