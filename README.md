# Payment_Default_Prediction

Dataset : [JANATA BANK Payment Default Prediction](https://www.kaggle.com/datasets/reverie5/av-janata-hack-payment-default-prediction)

## Bussiness Understanding

**Background**
> Bank Janata Taiwan pada tahun 2005 memiliki problem dimana sebanyak 22,12 % dari keseluruhan customernya default payment. Hal ini tentu dapat menurunkan revenue Bank Janata jika tidak ditangani dengan baik.

**Sebagai siapa kalian pada dataset tersebut?**
> Kami sebagai Data Scientist pada divisi Credit Analyst akan membantu Team Bisnis untuk memberikan solusi terhadap masalah yang dihadapi Bank Janata

**Goals**
  1.  Menurunkan Default Rate
  2.  Meningkatkan Revenue
  3.  Menurunkan Kerugian (Loss)

**Objective**
> Memprediksi user mana saja yang akan default, kemudian memberikan **Treatment** khusus pada user tersebut sehingga diharapkan agar tidak default pada bulan tersebut

**Business Metrics**
  1.  Default Rate
  2.  Revenue
  3.  Loss

**Bussiness Insight yang didapat**
1. Pengguna Credit Card terbanyak didominasi oleh wanita namun nasabah yang default didominasi oleh pria
2. Status Pernikahan tidak mempengaruhi default payment pada pembayaran bulan berikutnya
3. Nasabah dengan latar belakang pendidikan university dan high school menjadi nasabah dengan kemungkinan default payment terbesar
4. Default rate untuk nasabah yang akan mengalami pembayaran bulan berikutnya memiliki persentase sebesar 22.12 % dimana angka tersebut sangat tinggi jika dibandingkan
5. angka default rate perbankan yang wajar (5%-10%). Perlu menyeleksi lebih ketat lagi calon nasabah yang akan mendapat approval kartu kreditnya kedepan untuk mengurangi risiko kerugian kredit yang diterima bank

**Data Pre-processing**
1. Tidak ditemukan data yang null
2. Tidak ditemukan data yang duplicate
3. Membuat Feature baru untuk memperkuat prediksi model yang akan dibuat (Age Group, Membership, Minimum Amount (1-5), Pending amount(1-5)
4. Melakukan feature encoding pada beberapa data kategorikal (Age_Group, Limit_Segment)

**Modeling**
1. Split data Train dan Test dengan ratio 70:30 (14900:6100)
2. Metric utama yang akan digunakan dalam mengevaluasi performa model adalah precision
3. Menerapkan beberapa algoritma seperti Decision Tree, kNN, Logistic Regression, Random Forest, XGboost, AdaBoostpada untuk membuat model yang kemudian akan dibandingkan performanya
4. Berdasarkan hasil perbandingan tiap model, Model AdaBoost dan Random Forest memiliki nilai precision yang tinggi dibandingkan model lain.






















