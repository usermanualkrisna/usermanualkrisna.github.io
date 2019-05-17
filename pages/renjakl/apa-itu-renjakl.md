---
layout: post
aplikasi: renjakl
permalink: apa-itu-renjakl
---

Renja K/L adalah sebuah dokumen yang menjelaskan Rencana Kerja K/L selama satu tahun ke depan.

Renja K/L dibuat K/L, mengacu kepada RPJMN & RKP, dan disetujui oleh Bappenas serta Kemenkeu.

Renja K/L diacu oleh RKA K/L.

*NB: bagian pengelolaan K/L dan bagan-bagan di manual ini diambil dari [dokumen Bappenas berikut](/assets/dokumen/renjakl/manual-renja-2019-bappenas.pdf).*

#### Proses Penyusunan

Berikut proses penyusunan Renja K/L dilihat dari kaca mata aplikasi Krisna.

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/57908674-cb2ce000-78aa-11e9-9b21-b791924b4023.png"
%}

Terlihat bahwa intinya adalah:

1. K/L melakukan input/edit sampai tenggat waktu ditutup. (state `RENJAKL`)
2. Bappaneas-Kemenkeu menelaah, K/L memperbaharui jika dibutuhkan, sampai tenggat waktu ditutup. (state `APPROVAL` & `DJA ONLY`) 
3. Status RenjaKL jadi 'Approved' dan dijadikan referensi RKA K/L.

#### State (Tahapan)

`RENJAKL` : aplikasi sedang dalam proses input data oleh Kementerian/Lembaga 

`APPROVAL` : aplikasi sedang dalam tahapan Penelaahan oleh Direktorat Bappenas dan DJA. Kementerian/Lembaga dibatasi dalam penggunaan fitur-fitur input data.

`DJA ONLY` : penelaahan hanya dapat dilakukan oleh DJA.

#### Struktur Data

{% include image.html
    img="https://user-images.githubusercontent.com/2253841/57835918-ca804500-77e9-11e9-9042-5530b3089b91.png"
%}

