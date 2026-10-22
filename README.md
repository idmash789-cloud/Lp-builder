# LP Studio — Premium LP Builder

Aplikasi landing page builder berbasis **HTML, CSS, JavaScript murni**, tanpa instalasi dependencies atau backend. Buka `index.html` di browser atau deploy melalui GitHub Pages.

## Fitur

- Prompt Generator 7 langkah (Framework, Tone, Produk, Target, Detail, Desain, Platform) dengan dropdown berkelompok; copy prompt dan buka chat.z.ai.
- Empat lapisan harga, elemen opsional, target Scalev/Lynk.id/WordPress/Shopify/Copy HTML.
- Editor langsung pada preview, drag/drop urutan, tambah/hapus/gandakan section, undo/redo, warna section, gambar, gallery, video, tombol dan link.
- 18 template dengan filter kategori dan modal preview.
- Countdown, notifikasi penjualan yang dapat dikustomisasi, Meta Pixel ID dan event per CTA.
- Autosave di localStorage, responsive editor, ekspor dan salin HTML statis.

## Menjalankan

1. Unduh ZIP lalu ekstrak.
2. Buka `index.html` menggunakan Chrome/Edge.
3. Edit konten, lalu klik **Ekspor HTML**.

## GitHub Pages

Upload `index.html` dan `README.md` ke root repository. Buka **Settings → Pages → Build and deployment → Deploy from a branch**, lalu pilih `main` dan `/ (root)`.

## Catatan penting

- Tidak terhubung ke API AI. **Generate Prompt** merangkai brief; tombol chat.z.ai menyalin prompt dan membuka layanan eksternal untuk ditempel.
- Preview template adalah komposisi demo bawaan, bukan template dari pihak ketiga.
- Pixel hanya aktif di HTML ekspor jika browser pengunjung sudah mencatat `localStorage.lp_tracking_consent = 'yes'`; integrasikan banner persetujuan cookie Anda sendiri sebelum tracking. Hindari mengirim event Purchase dari tombol CTA tanpa transaksi benar-benar selesai.
- Timer adalah timer sesi, bukan deadline promosi global. Atur tenggat promosi dengan akurat dan hindari kesan urgensi palsu.
- Notifikasi penjualan hanyalah pesan statis yang dapat dikustomisasi, **bukan** transaksi nyata. Hubungkan ke data nyata sebelum menggunakan teks yang mengklaim pembelian.
- Tidak semua platform mengizinkan memasukkan satu dokumen HTML lengkap atau JavaScript di editor. Untuk hasil penuh, hosting HTML mandiri lebih andal.
- Data tersimpan hanya di browser lokal (localStorage), bukan sinkronisasi cloud.
