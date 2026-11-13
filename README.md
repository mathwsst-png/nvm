# NVM-X

Cara pakai (pilih salah satu):

1. **Langsung**: salin isi `nvmx-main.lua` ke executor, lalu execute.
2. **Lewat loader**: upload semua file ke repository GitHub kamu (branch `main`), buka file `nvmx`,
   ganti `repository = "GANTI-PEMILIK/GANTI-REPO"` dengan `"akunmu/namarepo"`, lalu jalankan:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/AKUNMU/NAMAREPO/refs/heads/main/nvmx"))()
```

Loader mengecek commit `main` terbaru lalu mengunduh `nvmx-main.lua` dari commit itu.

- Tekan **Insert** untuk menampilkan / menyembunyikan menu; tombol kecil **NVM-X** muncul saat menu disembunyikan.
- `nvmx-diagnose.lua` dan `nvmx-world-source.lua` hanya membaca data dan menyalin laporan diagnosis.
- Menu memakai UI NVM-X buatan sendiri (tanpa unduhan WindUI).
- Data konfigurasi disimpan di folder `NVMX/` pada workspace executor.

Fitur yang dihapus: Auto Drop, Pabrik, Titik Drop, dan notifikasi Discord.
