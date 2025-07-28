
# Banner Promosi Komunitas "Nyampah Bersama"

(preview.jpg)

Banner promosi interaktif untuk Komunitas "Nyampah Bersama" dengan fitur drag & drop horizontal dan manajemen konten dinamis melalui JSON.

## Fitur Utama

✨ **Responsif Mobile-First**  
📱 Tampilan optimal di perangkat mobile  
👆 Elemen yang mudah diakses dengan jari  

🔄 **Manajemen Konten Dinamis**  
📝 Ubah konten melalui file JSON tanpa coding  
➕ Tambah/hapus kegiatan dengan mudah  

🎨 **Interaktif & Menarik**  
↔️ Card horizontal dengan drag & drop  
🎚️ Indikator posisi dan animasi halus  
🌈 Skema warna hijau yang ramah lingkungan  

📊 **Statistik Komunitas**  
👥 Menampilkan jumlah anggota  
🗓️ Jumlah kegiatan  
🗑️ Sampah terkelola  

## Teknologi

- HTML5
- CSS3 (Flexbox, Grid, Animasi)
- JavaScript (ES6)
- Font Awesome Icons
- Google Fonts

## Cara Menggunakan

1. **Clone repositori**:
```bash
git clone https://github.com/username/nyampah-bersama-banner.git
cd nyampah-bersama-banner
```

2. **Edit konten**:
   - Buka file `data.json`
   - Ubah informasi komunitas, kegiatan, statistik, dll.

3. **Tambahkan gambar**:
   - Ganti URL gambar di file `data.json` dengan URL gambar Anda
   - Atau simpan gambar di folder `/images` dan gunakan path relatif

4. **Buka di browser**:
   - Buka file `index.html` di browser

## Struktur File

```
nyampah-bersama-banner/
├── index.html          # File utama aplikasi
├── data.json           # File konfigurasi konten
├── images/             # Folder untuk menyimpan gambar
│   ├── activity1.jpg
│   ├── activity2.jpg
│   └── ...
├── README.md           # Dokumentasi ini
└── preview.jpg         # Preview tampilan
```

## Konfigurasi JSON

Edit file `data.json` untuk mengelola konten:

```json
{
  "community": {
    "name": "Nyampah Bersama",
    "slogan": "Komunitas Peduli Lingkungan dan Pengelolaan Sampah",
    "description": "Bergabunglah dengan komunitas kami...",
    "stats": {
      "members": 1450,
      "events": 92,
      "wasteManaged": 14.2
    },
    "socialMedia": {
      "whatsapp": "https://wa.me/...",
      "instagram": "https://instagram.com/...",
      "facebook": "https://facebook.com/...",
      "youtube": "https://youtube.com/..."
    }
  },
  "activities": [
    {
      "id": 1,
      "title": "Jumat Bersih-Bersih",
      "description": "Aksi bersih-bersih pantai...",
      "date": "Setiap Jumat, 07:00 - 09:00",
      "location": "Pantai Kuta, Bali",
      "image": "images/activity1.jpg"
    },
    // Tambahkan kegiatan lainnya di sini
  ],
  "callToActions": [
    {
      "text": "Daftar Sekarang",
      "icon": "user-plus",
      "url": "#daftar",
      "type": "primary"
    }
    // Tambahkan tombol aksi lainnya
  ]
}
```

## Cara Deploy ke GitHub Pages

1. Buat repositori baru di GitHub
2. Upload semua file ke repositori
3. Buka Settings > Pages
4. Pada bagian "Build and deployment":
   - Source: Deploy from a branch
   - Branch: main (atau master)
   - Folder: / (root)
5. Klik Save
6. Tunggu beberapa menit, aplikasi akan live di:
   `https://username.github.io/repository-name`

## Kontribusi

Kontribusi diterima! Berikut cara berkontribusi:

1. Fork repositori
2. Buat branch baru (`git checkout -b fitur-baru`)
3. Commit perubahan Anda (`git commit -am 'Tambahkan fitur baru'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buat Pull Request

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

**Komunitas Nyampah Bersama**  
Bersama menjaga lingkungan, menciptakan masa depan yang lebih hijau! ♻️

