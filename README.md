# Situs developer (GitHub Pages)

Halaman publik untuk Play Console dan AdMob: kebijakan privasi dan `app-ads.txt`.

## Sebelum dipasang
Ganti semua placeholder:
- nama developer: sudah diisi **Xprofile**;
- email kontak: sudah diisi xprofile.support@gmail.com (ganti di `privasi.html` dan `index.html` bila nanti memakai email khusus game);
- `pub-0000000000000000` di `app-ads.txt` → ID penayang dari AdMob (Akun → Informasi akun → ID penayang).

## Memasang
1. Buat repo GitHub bernama **`<username>.github.io`** (harus persis begini supaya `app-ads.txt` ada di root domain).
2. Unggah `index.html`, `privasi.html`, `app-ads.txt` ke root repo itu.
3. Settings → Pages → Deploy from branch → `main` / root. Tunggu 1–2 menit.
4. Cek:
   - `https://<username>.github.io/privasi.html` → URL kebijakan privasi di Play Console;
   - `https://<username>.github.io/app-ads.txt` → harus tampil satu baris;
   - `https://<username>.github.io` → URL "Situs" di halaman toko Play (AdMob membaca `app-ads.txt` dari sini).

Isi kebijakan mengikuti kode per 10 Nov 2026: kamera diproses di HP, AdMob, Play Games, tanpa analitik pihak ketiga. Perbarui bila ada layanan baru (mis. pembelian dalam aplikasi). Ini bukan nasihat hukum.
