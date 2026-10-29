# DESIGN.md

Arah desain untuk situs wisata Banda Aceh. Ditulis sebelum membangun UI, bukan setelahnya.

## Identitas

Banda Aceh bukan kota pantai tropis biasa. Ia kota yang pernah kehilangan hampir segalanya pada 26 Desember 2004, lalu berdiri lagi. Situs ini harus terasa seperti **jurnal perjalanan yang tenang**, bukan brosur promo. Tenang, hangat, dan jujur.

Nada: seperti catatan perjalanan seorang kawan yang pernah tinggal di sana. Bukan hype.

## Palet

| Peran | Warna | Alasan |
| --- | --- | --- |
| Latar | `#f7f1e6` kertas gading | Menghindari putih steril, terasa seperti buku catatan perjalanan |
| Tinta | `#1c1b18` | Kontras tinggi untuk teks, lebih hangat dari hitam murni |
| Utama | `#0f3d38` hijau laut dalam | Warna laut Aceh dan atap masjid, dipakai untuk blok besar |
| Sekunder | `#bf4b26` terakota | Warna genting dan rempah, dipakai untuk aksen dan CTA |
| Ketiga | `#d9a13b` kunyit | Aksen kecil, dipakai hemat |
| Netral | `#efe5d3`, `#fffdf8` | Pemisah bidang dan kartu |

Alasan: tiga warna inti (hijau laut, terakota, kunyit) diambil dari lanskap dan dapur Aceh, bukan dari palet AI biru-ungu. Netral tidak dihitung.

## Tipografi

- **Fraunces** untuk judul. Serif dengan sumbu optical size, terasa seperti majalah perjalanan cetak, bukan sans-serif startup.
- **Plus Jakarta Sans** untuk teks. Huruf buatan Jakarta, cocok dengan konteks Indonesia dan lebih netral daripada Inter.

Alasan: pasangan serif display dan sans humanis memberi karakter editorial, bukan template SaaS.

## Komposisi

- Hero terbelah: teks di kiri, fotografi di kanan, dengan satu foto kecil menumpuk. Tidak ada statistik palsu.
- Destinasi disusun sebagai daftar editorial bergantian kiri-kanan, bukan grid kartu seragam. Dua entri memakai panel warna sebagai pengganti foto karena foto yang tepat tidak tersedia. Ini disengaja dan jujur.
- Bagian kuliner memakai kartu warna penuh, karena foto makanan Aceh yang akurat tidak tersedia di Pexels.
- Bagian jejak 2004 memakai latar hijau laut gelap, satu-satunya bagian gelap, untuk memberi bobot emosional.
- Sudut tajam sampai 4px. Tidak ada pil di semua elemen.

## Gerak

MOTION 2: hanya fade dan naik 16px saat masuk viewport, plus transisi hover halus. Menghormati `prefers-reduced-motion`.

## Yang sengaja tidak dipakai

- Statistik karangan, testimoni, logo "dipercaya oleh".
- Badge pil di atas setiap judul, ikon sparkle, gradien biru-ungu.
- Grid kartu seragam untuk semua bagian.
- Tema gelap default. Situs ini terang karena kontennya tentang kota di siang hari.

## Sumber

Semua foto dari Pexels, lisensi bebas pakai. Fakta sejarah ditulis tanpa angka yang tidak bisa diverifikasi.
