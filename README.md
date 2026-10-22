# Media Pembelajaran Kimia: Laju Reaksi (SMA/MA Kelas XI)

Situs statis tanpa proses build. Semua halaman berupa satu file HTML mandiri.

## Isi
| File | Alamat setelah deploy | Keterangan |
|------|-----------------------|------------|
| `index.html` | `/` | Subbab 1: Konsep Laju Reaksi dan Teori Tumbukan |
| `peta-konsep.html` | `/peta-konsep` | Peta konsep laju reaksi (interaktif, tampilan potret) |
| `vercel.json` | - | Konfigurasi Vercel (alamat tanpa `.html`) |

## Menjalankan di komputer
Buka `index.html` atau `peta-konsep.html` langsung di peramban. Tidak perlu instalasi apa pun.

## Deploy ke Vercel lewat GitHub
1. Buat repositori baru di GitHub, lalu unggah semua file di folder ini ke branch `main`. Pastikan `index.html` berada di akar repositori, bukan di dalam subfolder.
2. Buka vercel.com, login dengan akun GitHub, klik **Add New > Project**, pilih repositori tadi, lalu **Import**.
3. Framework Preset: **Other**. Kosongkan Build Command dan Output Directory. Root Directory: `./`.
4. Klik **Deploy**. Alamat situs berbentuk `https://nama-proyek.vercel.app`.
5. Setiap `git push` ke `main` memperbarui situs secara otomatis.

## Catatan
Grafik dan gambar bersifat ilustratif untuk membantu memahami konsep, bukan data eksperimen.
