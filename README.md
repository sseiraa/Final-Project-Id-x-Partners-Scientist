# **Credit Risk Prediction** 
Rakamin Academy - ID/X Partners Data Scientist Project Based Internship Program

---
## **Introduction**
Project ini dibuat sebagai tugas akhir dari program virtual project based internship yang diselenggarakan  oleh Rakamin Academy yang berkerjasama dengan ID/X Partners.
Pada project ini, Saya sebagai data scientist diminta untuk membangun model yang dapat memprediksi credit risk menggunakan dataset yang disediakan oleh company yang terdiri dari data pinjaman yang diterima dan yang ditolak. 
Selain itu Saya juga perlu mempersiapkan media visual untuk mempresentasikan solusi ke klien. 


## 📂 **Stage 0 : Problem Research**
## Business Undersding
- Perusahaan pinjaman (Lending Company) memiliki masalah pada produk pinjaman yang ditandai dengan meningkatnya credit risk dibandingkan dengan tahun sebelumnya.
- Perusahan harus memutuskan untuk menyetujui atau menolak aplikasi pinjaman berdasarkan profil pemohon.
- Perusahaan harus memperhitungkan secara kuantitatif risiko kerugian akibat gagal bayar atau pelunasan awal.
  
## Business Objective
### Problem Statement
Secara kuantitatif terdapat dua risiko yang disebabkan oleh pemohon, yaitu :
- **Good Risk** jika pemohon kemungkinan besar akan melunasi pinjaman, maka menolak pemohon akan merugikan perusahaan.
- **Bad Risk** jika pemohon kemungkinan tidak akan melunasi pinjaman, maka menyetujui pemohon akan merugikan perusahaan.

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

## 📂 **Stage 1 : Exploratory Data Analysis**
### Dataset
|index|Unnamed: 0|id|member\_id|loan\_amnt|funded\_amnt|funded\_amnt\_inv|term|int\_rate|installment|grade|sub\_grade|emp\_title|emp\_length|home\_ownership|annual\_inc|verification\_status|issue\_d|loan\_status|pymnt\_plan|url|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|0|0|1077501|1296599|5000|5000|4975\.0| 36 months|10\.65|162\.87|B|B2|NaN|10+ years|RENT|24000\.0|Verified|Dec-11|Fully Paid|n|https://www\.lendingclub\.com/browse/loanDetail\.action?loan\_id=1077501|
|1|1|1077430|1314167|2500|2500|2500\.0| 60 months|15\.27|59\.83|C|C4|Ryder|\< 1 year|RENT|30000\.0|Source Verified|Dec-11|Charged Off|n|https://www\.lendingclub\.com/browse/loanDetail\.action?loan\_id=1077430|
|2|2|1077175|1313524|2400|2400|2400\.0| 36 months|15\.96|84\.33|C|C5|NaN|10+ years|RENT|12252\.0|Not Verified|Dec-11|Fully Paid|n|https://www\.lendingclub\.com/browse/loanDetail\.action?loan\_id=1077175|
|3|3|1076863|1277178|10000|10000|10000\.0| 36 months|13\.49|339\.31|C|C1|AIR RESOURCES BOARD|10+ years|RENT|49200\.0|Source Verified|Dec-11|Fully Paid|n|https://www\.lendingclub\.com/browse/loanDetail\.action?loan\_id=1076863|
|4|4|1075358|1311748|3000|3000|3000\.0| 60 months|12\.69|67\.79|B|B5|University Medical Group|1 year|RENT|80000\.0|Source Verified|Dec-11|Current|n|https://www\.lendingclub\.com/browse/loanDetail\.action?loan\_id=1075358|

