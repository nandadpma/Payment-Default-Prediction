# Payment_Default_Prediction

Apa problem yang mau diselesaikan dari dataset tsb?
  Kemungkinan nasabah yang gagal bayar pada pembayaran bulan berikutnya

Sebagai siapa kalian pada dataset tersebut?
  Sebagai Data Scient Kita bertanggung jawab dalam memprediksi nasabah mana saja yang kemungkinan gagal bayar pada pembayaran bulan berikutnya

Apa goal yang mau dicapai?
  Memprediksi nasabah mana saja yang akan mendapatkan pinjaman dan nasabah mana saja yang kemungkinan akan gagal bayar, mengurangi jumlah nasabah yang gagal bayar.

Apa Objective yang sesuai dengan goal tsb?
  Membuat sistem yang dapat mengenali nasabah yang kemungkinan tidak akan gagal bayar di bulan berikutnya

Apa business metrics yang cocok untuk mengukur ketercapaian Objective tsb?
  Payment Default Rate (menghitung rasio dari nasabah yang kemungkinan gagal bayar di bulan berikutnya)


Background
1. Sebuah bank yang mendapatkan sebesar 22% nasabah kartu kredit gagal bayar pada pembayaran bulan berikutnya.
2. Kegagalan bayar menyebabkan menurunnya keuntungan bank, dan bank harus mengeluarkan cost lebih untuk melakukan penagihan
3. Kami ingin membuat machine learning yang dapat memprediksi nasabah mana yang akan gagal bayar pada pembayaran bulan berikutnya
4. Goals kami adalah menurunkan default rate dikisaran 5% - 10% agar keuntungan bank meningkat dan cost untuk melakukan penagihan dapat dikurangi

Hasil Pengamatan EDA
1. Terdapat outlier pada semua kolom bill amt dan pay amt dan datanya memiliki kerapatan yang cukup rapat
2. Distribusi data tidak berdistribusi secara normal atau nilai mean lebih besar dibanding mediannya
3. Tidak terdapat perbedaan distribusi data yang signifikan pada feature sex, age dan education
4. Perbandingan data antara kelas Default dan tidak default cukup timpang yaitu 22:78 persen

Bussiness Insight yang didapat
1. Pengguna Credit Card terbanyak didominasi oleh wanita namun nasabah yang default didominasi oleh pria
2. Status Pernikahan tidak mempengaruhi default payment pada pembayaran bulan berikutnya
3. Nasabah dengan latar belakang pendidikan university dan high school menjadi nasabah dengan kemungkinan default payment terbesar
4. Default rate untuk nasabah yang akan mengalami pembayaran bulan berikutnya memiliki persentase sebesar 22.12 % dimana angka tersebut sangat tinggi jika dibandingkan
5. angka default rate perbankan yang wajar (5%-10%). Perlu menyeleksi lebih ketat lagi calon nasabah yang akan mendapat approval kartu kreditnya kedepan untuk mengurangi risiko kerugian kredit yang diterima bank























