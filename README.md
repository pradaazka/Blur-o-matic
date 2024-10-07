# Blur O Matic - Materi 12 (Repository pattern and WorkManager)

## Mata Kuliah : Praktik Pemrograman Mobile 2

![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Android Studio](https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white)

## Deskripsi

Codelab ini berfokus pada menambahkan WorkManager ke aplikasi, membuat pekerja untuk membersihkan file sementara yang dibuat ketika memburamkan gambar, memburamkan gambar, dan menyimpan salinan akhir gambar yang dapat Anda lihat saat mengklik tombol See File. Anda juga akan mempelajari cara memantau status pekerjaan latar belakang dan mengupdate UI aplikasi sebagaimana mestinya.

## Link Latihan Codelab

**Background Work with WorkManager** <br>
https://developer.android.com/codelabs/basic-android-kotlin-compose-workmanager

**Advanced WorkManager and Testing** <br>
https://developer.android.com/codelabs/basic-android-kotlin-compose-verify-background-work

> [!NOTE]
> Pada versi Android 10 kebawah memerlukan izin `WRITE_EXTERNAL_STORAGE` di file `AndroidManifest.xml` agar bisa menyimpan file gambar yang diblur.
> 
> Sebelum menjalankan worker izinkan akses penyimpanan terlebih dahulu agar tidak terjadi error.

## Screenshot
<div style="display: flex; gap: 16px">
    <img src="https://developer.android.com/static/codelabs/basic-android-kotlin-compose-workmanager/img/2bdb6fdc2567e96_856.png" width="250px" />
    <img src="https://developer.android.com/static/codelabs/basic-android-kotlin-compose-workmanager/img/10c653bb5b84c4b2_856.png" width="250px" />
</div>
