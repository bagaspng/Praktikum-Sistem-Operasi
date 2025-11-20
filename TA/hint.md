# 🧩 TA 5 – Steganografi Pesan Rahasia (Modul Sistem Operasi)

## 📁 Struktur Direktori
Secret/ <br/>
├── image/ # berisi gambar sumber dan hasil reply.png<br/>
├── extract/ # hasil ekstraksi & decoding pesan<br/>
└── reply/ # pesan balasan dan hasil encoding<br/>

## 💡 Petunjuk Umum
+ Ekstrak pesan di antara marker
  + `` ----LABKOM-SECRET---``
+ Jika pesan terlihat acak, coba cek apakah itu Base64 atau ROT13.
  + Pesan dalam *image* formatnya adalah base64  

> [!CAUTION]
> Pastikan hati-hati dalam menggunakan command agar CLI anda tidak *collaps* 
  
> [!TIP]
> Gunakan xxd -l 32 untuk melihat byte awal gambar dan xxd -s -64 untuk memeriksa bagian akhir.



