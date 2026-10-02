# flowdocs

Skill pembaca alur kode yang menghasilkan dokumentasi HTML tentang cara kerja, arsitektur, dan aliran data aplikasi dalam bahasa yang mudah dipahami orang non-IT.

## Hasil akhir

Satu berkas **`panduan-aplikasi.html`** yang bisa dibuka langsung di browser tanpa server, instalasi, atau koneksi internet untuk membaca isinya.

Dokumen mencakup:

- Tujuan aplikasi, fitur, dan hak akses.
- Panduan penggunaan sesuai menu dan tombol yang ditemukan.
- Diagram arsitektur, tugas komponen, dan perjalanan data.
- Data, privasi, layanan pendukung, dan kebutuhan operasional.
- Status pengujian, batasan, kendala, dan langkah berikutnya.

Dokumen menggunakan bahasa Indonesia yang mudah dipahami, daftar isi yang bisa diklik, tampilan responsif, diagram tertanam, dan gaya cetak.

## Cara memasang

### Replit

Unduh `SKILL.md`, lalu tambahkan lewat pengaturan workspace → **Knowledge → Skills** agar tersedia di percakapan lain.

### Agen yang mendukung SKILL.md

Letakkan berkas pada:

```text
.agents/skills/panduan-aplikasi-non-it/SKILL.md
```

Ikuti mekanisme pemuatan skill pada agen yang digunakan. Ketersediaan lintas percakapan bergantung pada platform.

## Cara menggunakan

Berikan akses ke proyek atau berkas kode, lalu minta:

> Pakai skill panduan-aplikasi-non-it untuk membaca aplikasi ini dan menghasilkan panduan HTML bagi pembaca non-IT, termasuk arsitektur dan aliran datanya.

Nama repo adalah **flowdocs**; nama pemicu skill tetap **panduan-aplikasi-non-it**.

## Prinsip

- Dokumentasi berdasarkan kode dan bukti yang diperiksa, bukan asumsi.
- Fitur yang terlihat di kode tidak otomatis dianggap sudah teruji.
- Arsitektur digambar sesuai implementasi yang ditemukan, bukan pola generik.
- Rahasia dan data pribadi yang tidak diperlukan tidak disalin ke dokumen.
- Pemeriksaan tidak boleh mengubah data produksi atau melakukan tindakan nyata tanpa persetujuan.

## Isi repo

| Berkas | Isi |
|---|---|
| `SKILL.md` | Instruksi lengkap untuk menghasilkan dokumentasi. |
| `README.md` | Ringkasan, pemasangan, dan contoh penggunaan. |

Repo ini berisi instruksi skill, bukan aplikasi yang dijalankan atau dokumentasi untuk proyek tertentu.