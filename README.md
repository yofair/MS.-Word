# Bahan Ajar Interaktif Ms. Word - Kelas XI SMK

Bahan ajar interaktif satu halaman (`index.html`) tanpa dependensi, berjalan di Chrome dan browser modern lain, responsif di HP maupun laptop.

## Isi (9 slide)
1. Identitas siswa (nama dan kelas)
2. Tujuan pembelajaran
3. Materi 1: antarmuka dan format teks
4. Materi 2: tabel, gambar, header-footer, daftar isi, mail merge
5. Studi kasus interaktif
6. Kuis 5 soal pilihan ganda dengan skor otomatis dan feedback
7. Refleksi
8. Hasil respons siswa (cetak/simpan PDF, unduh .txt)
9. Penutup dengan tombol kembali ke slide pertama

Siswa tidak dapat lanjut sebelum mengisi data atau menjawab yang diwajibkan. Respons disimpan di `localStorage` browser (kunci `wordSMK11_v1`), sehingga tetap ada setelah halaman dimuat ulang pada perangkat yang sama.

## Menjalankan secara lokal
Buka `index.html` langsung di Chrome.

## Deploy ke GitHub Pages
1. Buat repository baru di GitHub, lalu unggah `index.html`, `README.md`, dan `.nojekyll` (file `.nojekyll` bersifat tersembunyi, pastikan ikut terunggah).
2. Buka **Settings > Pages**.
3. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu satu sampai dua menit. Alamatnya: `https://<username>.github.io/<nama-repo>/`

## Catatan
- Data tersimpan per perangkat dan browser; guru tidak menerima data secara otomatis. Siswa dapat menyerahkan hasil lewat tombol **Cetak / Simpan PDF** atau **Unduh .txt**.
- Mode penyamaran (incognito) menghapus data setelah jendela ditutup.

&copy; Yoga Fauzi Irawan, S. Kom., Gr.
