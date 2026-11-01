# AGKI PGRI — Wartam, S.Pd.

Situs tulisan tentang lomba AGKI (Anugerah Guru Kreatif dan Inovatif) Wartam, S.Pd.,
SMP Negeri 4 Majenang. Alamat: https://pgri.wartam.web.id/

## Isi

- `index.html` — halaman pertama: tampilan Spanduk AGKI Wartam (satu berkas,
  foto + logo tertanam; bagian Profil, Portofolio, Karya Inovasi, dan Medsos
  berada di bawahnya). Halaman-halaman berikutnya ditambahkan di sini kemudian.
- `caddy-agki-pgri.conf` — contoh blok situs Caddy untuk VPS.
- `DEPLOY-VPS.txt` — langkah DNS, pull, dan Caddy di VPS.

## Pola

Sama seperti KELANA: GitHub adalah acuan. Ubah berkas di sini, commit + push,
lalu di VPS `git pull` dan muat ulang Caddy. Jangan mengedit berkas langsung
di folder jalan VPS.
