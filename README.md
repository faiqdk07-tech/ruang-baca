# Ruang Baca

Web latihan Literasi UTBK (Bahasa Indonesia dan Bahasa Inggris).

## Cara menambah paket
1. Buat paket di artefak Ruang Baca (aplikasi Claude), buka paketnya di rak, lalu tekan **Unduh JSON**.
2. Di repo ini, buka folder `data/paket/` → **Add file → Upload files** → pilih file JSON tadi → **Commit changes**.
3. Buka web di GitHub Pages. Paket baru muncul otomatis di rak.

Web membaca isi folder `data/paket/` lewat GitHub API. Kalau suatu saat paket tidak muncul (misalnya karena batas permintaan GitHub API), tambahkan nama filenya ke `data/index.json`, contoh:

```json
["LBIND-261106-abc.json", "LBE-261106-xyz.json"]
```

## Mengaktifkan GitHub Pages
Settings → Pages → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → Save.

## Catatan
- Halaman **Tambah paket** hanya tampil di versi artefak Claude, karena pembuatan soal membutuhkan koneksi ke Claude.
- Progres di versi GitHub tersimpan di browser yang dipakai, tidak tersinkron dengan versi artefak.
