# Bug Report: Duplikasi prospek ketika mengirim data dengan waktu bersamaan pada database
<br>**Bug ID** : B-001</br>
<br>**Summary** : Duplikasi prospek ketika mengirim data dengan waktu bersamaan pada database</br>
<br>**Reporter** : M Ilham Makarim</br>
<br>**Step To Reproduce** 
1. Persiapkan Whatsapp dari mobile phone dengan nomor yang sama
2. Persiapkan Whatsapp dari website dengan nomor yang sama
3. Kirim pesan dengan nomor telepon yang sama dalam waktu bersamaan</br>

<br>**Test Data** : 08818670699</br>
<br>**Actual Result** : Prospek terduplikasi ketika mengirim secara bersamaan dengan nomor 08818670699 ada 2 di database</br>
<br>**Expected Result** : Prospek tidak terduplikasi ketika mengirim secara bersamaan hanya satu nomor 08818670699 yang di database</br>
<br>**Severity** : High</br>
<br>**Priority** : High</br>
<br>**Evidence** : Video/Screenshot</br>
<br>**Note** :
1. lakukan unit testing dahulu sebelum deploy ke staging
2. pastikan ketika kirim dalam waktu bersamaan baik dari 2 atau lebih pesan yang masuk ke database hanya 1 nomor</br>
