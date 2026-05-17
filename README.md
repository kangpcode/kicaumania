# The Kicau Gank

![Screenshot](screenshot.png)

Aplikasi web interaktif yang menggunakan pelacakan tangan bertenaga AI untuk memicu animasi kucing menari. Dibuat dengan MediaPipe Hands dan pemrosesan video chroma-key.

## Fitur

- **Pelacakan Tangan AI**: Mendeteksi hingga 4 tangan secara simultan menggunakan MediaPipe
- **Animasi Interaktif**: Video kucing menari aktif saat 2+ tangan terdeteksi
- **Pemrosesan Chroma-Key**: Penghapusan layar hijau real-time untuk overlay yang mulus
- **Diagnostik Langsung**: Tampilan log bergaya terminal untuk status sistem
- **Dukungan Video Kustom**: Unggah file MP4 Anda sendiri untuk animasi
- **Desain Responsif**: Berfungsi di desktop dan perangkat mobile
- **Resolusi 1920x1080**: Output kamera Full HD

## Teknologi

- **HTML5** - Struktur
- **Tailwind CSS** - Styling (via CDN)
- **MediaPipe Hands** - Pelacakan tangan AI
- **JavaScript** - Logika dan interaktivitas

## Instalasi

1. Clone atau download repository ini
2. Buka `index.html` di browser modern
3. Izinkan akses kamera saat diminta
4. Tunjukkan 2 tangan atau lebih untuk mengaktifkan kucing menari!

## Penggunaan

- **Deteksi Tangan**: Sistem melacak tangan Anda menggunakan webcam
- **Aktivasi**: Tunjukkan 2+ tangan untuk memicu animasi kucing
- **Video Kustom**: Klik tombol "MP4" untuk mengunggah video layar hijau Anda sendiri
- **Kontrol Audio**: Gunakan tombol mute untuk mengaktifkan/menonaktifkan audio
- **Log**: Pantau aktivitas sistem di panel terminal

## Struktur Proyek

```
kicaumania/
├── index.html          # File aplikasi utama
├── kicaumaniav1.mp4    # Video kucing menari default
├── screenshot.png      # Screenshot aplikasi
├── README.md           # File ini
└── LICENSE.md          # File lisensi
```

## Screenshot

![Demo](demo.png)

*Tampilan aplikasi saat mendeteksi 2 tangan atau lebih*

## Persyaratan Browser

- Browser modern dengan JavaScript aktif
- Akses webcam
- Dukungan WebGL (untuk MediaPipe)

## Penulis

**kangpcode (Dhafa Nazula Permadi)**

## Lisensi

Lihat [LICENSE.md](LICENSE.md) untuk detail.

## Kredit

- MediaPipe oleh Google
- Tailwind CSS
- Mixkit untuk aset video sampel

---

© 2026 kangpcode (Dhafa Nazula Permadi). Hak Cipta Dilindungi.
