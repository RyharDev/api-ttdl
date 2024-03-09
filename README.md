## Deskripsi 
Ini adalah API sisi server untuk mengunduh video Tiktok. Ini memungkinkan pengguna mengunduh video dari Tiktok dengan memberikan URL video tersebut.


## Instalasi
1. Kloning repositori:
   ```
   git clone https://github.com/RyharDev/api-ttdl
   ```
2. Buka file
   ```
   cd api-ttdl
   ```   
3. Instal dependensi:
   ```
   npm install
   ```

## Penggunaan
1. Mulai server:
   ```
   node index.js
   ```
2. Akses titik akhir API menggunakan format berikut:
   ```
   GET /tiktok/api.php?url=[URL_TIKTOK]
   ```
   Ganti `[URL_TIKTOK]` dengan URL sebenarnya dari video Tiktok yang ingin Anda unduh.
   
   
## DEMO
[RyharDev Tiktok Downloader](https://ryhardev-tiktok-downloader.onrender.com/)

## Tanggapan
API akan merespons dengan objek JSON yang berisi URL unduhan dan informasi relevan lainnya tentang video tersebut.

Contoh tanggapan:
```
{
  "audio": [
    "https://www.tikwm.com/video/music/6990916139345808666.mp3"
  ],
  "video": [
    "https://www.tikwm.com/video/media/play/6990916139345808666.mp4"
  ]
}
```

## Penanganan Kesalahan
Jika ada kesalahan pada URL atau video tidak tersedia untuk diunduh, API akan merespons dengan kesalahan server.

## Lisensi
Proyek ini dilisensikan di bawah [Lisensi MIT](https://opensource.org/licenses/MIT).
