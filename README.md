# Mareta Love Website

Website bucin khusus Mareta, siap diunggah ke GitHub dan diimpor ke Vercel.

## Deploy ke Vercel

1. Unggah **isi folder ini** ke repository GitHub tersendiri. Pastikan `vercel.json` dan folder `dist` berada di akar repository.
2. Import repository di Vercel.
3. Project Name: `mareta-love` (huruf kecil).
4. Framework Preset: **Other**. Root Directory: `./`.
5. Build Command: kosong. Output Directory: **dist**.
6. Klik Deploy.

Tidak perlu Node.js, instalasi paket, API key, atau variabel environment untuk deployment.

## Isi

- Surat cinta, amplop animasi, dan tombol peluk virtual.
- Enam teka-teki absurd. Setiap pilihan punya balasan sendiri; tidak ada jawaban yang menghukum pemain.
- Dua belas gombalan bergantian, hujan hati, serta paket cinta penutup.
- Tabungan sayang tersimpan hanya di browser perangkat tersebut.
- Bunyi kecil opsional; awalnya mati. Ini nada sintetis, bukan lagu latar.
- Tampilan responsif dan dukungan preferensi mengurangi animasi.

## Mengubah isi

Surat ada di `dist/index.html`. Teka-teki dan gombalan ada di `dist/app.js`. Warna serta animasi ada di `dist/styles.css`.

Font Google bersifat tambahan; font cadangan tetap tersedia jika koneksi gagal. Tidak ada pengumpulan data atau pengiriman jawaban ke server. Setelah dideploy, siapa pun yang memiliki alamat website dapat membukanya.
