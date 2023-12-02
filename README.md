# *Credit Risk Prediction* 
Rakamin Academy - ID/X Partners Data Scientist Project Based Internship Program

---
## *Introduction*
Project ini dibuat sebagai tugas akhir dari program virtual project based internship yang diselenggarakan  oleh Rakamin Academy yang berkerjasama dengan ID/X Partners.
Pada project ini, Saya sebagai data scientist diminta untuk membangun model yang dapat memprediksi credit risk menggunakan dataset yang disediakan oleh company yang terdiri dari data pinjaman yang diterima dan yang ditolak. 
Selain itu Saya juga perlu mempersiapkan media visual untuk mempresentasikan solusi ke klien. 


## 📂 *Stage 0 : Problem Research*
## Business Understanding
- Perusahaan pinjaman (Lending Company) memiliki masalah pada produk pinjaman yang ditandai dengan meningkatnya credit risk dibandingkan dengan tahun sebelumnya.
- Perusahan harus memutuskan untuk menyetujui atau menolak aplikasi pinjaman berdasarkan profil pemohon.
- Perusahaan harus memperhitungkan secara kuantitatif risiko kerugian akibat gagal bayar atau pelunasan awal.
  
## Business Objective
### Problem Statement
Secara kuantitatif terdapat dua risiko yang disebabkan oleh pemohon, yaitu :
- *Good Risk* jika pemohon kemungkinan besar akan melunasi pinjaman, maka menolak pemohon akan merugikan perusahaan.
- *Bad Risk* jika pemohon kemungkinan tidak akan melunasi pinjaman, maka menyetujui pemohon akan merugikan perusahaan.

### Objectives
- Mengidentifikasi pola risiko buruk yang menujukkan bahwa pemohon cenderung tidak melunasi pinjaman.
- Melakukan tindakan terhadap hasil yang didapat seperti menolak pinjaman, mengurangi jumlah pinjaman, atau menetapkan suku bunga yang lebih tinggi.
- Menetapkan algoritma machine learning untuk membangun model prediktif.
- Memprediksi aplikasi pinjaman yang akan dianggap sebagai risiko buruk.
- Mengambil keputusan otomatis untuk menyetujui atau menolak aplikasi pinjaman

### Goals
- Membuat machine learning yang dapat memprediksi risiko dari setiap pemohon
- Diharapkan model dapat menurunkan credit risk pada perusahaan

## Analytical Approach
- Penerapan loan credit risk modelling diperlukan sebagai bagian dari evaluasi persetujuan kredit.
- Cara kerja loan credit risk modelling dengan  menggunakan data historis peminjam dan status pinjaman saat ini untuk membuat model pembelajaran mesin yang memprediksi risiko kredit pemohon di masa depan.
- Loan credit risk modelling dapat menjadi  alat bagi perusahaan untuk memutuskan apakah akan menerima atau menolak pinjaman kredit. Perusahaan dapat menggunakan model atau sistem penilaian selain model ini  untuk membantu menilai risiko kredit perusahaan.
---

## 📂 *Stage 1 : Data Processing*
![image](https://github.com/sseiraa/Final-Project_Id.x-Partners/assets/146892136/a51d8520-dd54-4426-8fa3-06e8feb1983b)
---
## 📂 *Stage 2 : Exploratory Data Analysis*
### Dataset
- memiliki 75 colums dan 466.285 rows
- tidak ada data duplikat maupun data yang hilang
- terdapat 4 tipe data yaitu int64, float64, datetime64 dan object
- terdapat 53 fitur untuk data numerikal dan 17 fitur untuk data kategorikal

### Insight
![image](https://github.com/sseiraa/Final-Project_Id.x-Partners/assets/146892136/9aaddc5e-a172-4f62-94f5-482945e3c125)
![image](https://github.com/sseiraa/Final-Project_Id.x-Partners/assets/146892136/62d4cad0-a72e-4c2a-8265-633c8d309bdf)
---

## 📂 *Stage 3 : Modelling and Evaluation*
### Classification Model
![image](https://github.com/sseiraa/Final-Project_Id.x-Partners/assets/146892136/03c55f92-2379-450b-9fbe-b5bd3e2c9c0e)

### Final Model - Random Forest
![image](https://github.com/sseiraa/Final-Project_Id.x-Partners/assets/146892136/0eb85e20-1cfa-4803-a5a4-ce90ab8a9264)
![image](https://github.com/sseiraa/Final-Project_Id.x-Partners/assets/146892136/7750bbd8-7bdd-43fc-ba7c-fecf5bea456e)

### Alasan pemilihan model :
- perbedaan akurasi pada saat dilakukan pelatihan dan pengujian sangat kecil dibandingkan dengan yang lain.
- Random forest memilki generalisasi yang lebih baik dibandingkan model lainnya.
---

## 📂 *Stage 4 : Business Insight and Recommendation*
### Business Insight
Berdasarkan total loss suffered by the company
![image](https://github.com/sseiraa/Final-Project_Id.x-Partners/assets/146892136/4d1964ec-8255-4f9d-be52-baa0a2c58367)

### Business Recommendation
#### Business recommendation for machine learning
Perusahaan dapat melihat ciri - ciri terpenting seperti bulan pembayaran terakhir, jumlah pembayaran terakhir, dan lain sebagainya untuk mengidentifikasi apakah pemohon memiliki kemungkinan menguntungkan atau merugikan.


#### Business recommendation from insight
Perusahaan dapat mengambil keputusan mutlak seperti menolak pinjaman, mengurangi jumlah pinjaman dan lain sebagainya untuk menghindari dan mengurangi total kerugian yang diderita oleh persahaan

---
