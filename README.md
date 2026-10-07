# Keselamatan Sekolah 2026

Laman laporan akademik dan pembentangan dalam Bahasa Melayu.

Disediakan oleh: **Izzah Sofiyah binti Mohd Murtadha**.

**Sarjana Muda Sains Pentadbiran dan Pembangunan Tanah dengan Kepujian, Universiti Teknologi Malaysia**.
Pembentang slaid: **Izzah Sofiyah binti Mohd Murtadha**.

## Laman dan pembentangan

- Laman: https://drmurtadha.github.io/sekolah-selamat/
- Pembentangan: https://drmurtadha.github.io/sekolah-selamat/slaid/index.html
- 9 halaman laporan, satu halaman pengenalan slaid dan dek 17 slaid.
- 25 jadual HTML dan tiga carta. Jadual sentiasa tersedia walaupun Chart.js tidak dimuatkan.
- Laporan dipindahkan daripada lampiran Markdown yang dibekalkan; bukan pengesahan bebas tentang ketepatan kes atau undang-undang.
- Nama mangsa diganti dengan Mangsa Kes A dan Mangsa Kes B. URL sumber dikekalkan.
- Baris persembahan diraja tidak dipaparkan pada laman awam.
- Kandungan laporan mengekalkan konteks asal UTM mengikut arahan fail baharu. Slaid kekal sebagai cadangan umum seperti yang diminta sebelumnya.
- Lima visual dalam slaid ialah ilustrasi fotografi AI, bukan foto individu atau kejadian sebenar.

## Teknologi

HTML, CSS dan JavaScript statik. Tiada langkah binaan, Node, framework atau Jekyll diperlukan. `.nojekyll` disertakan. Chart.js dimuatkan daripada jsDelivr; data carta dalam JSON setempat. Tiada analitik, kuki, penjejakan atau borang.

## Struktur

```text
index.html
kes.html
punca.html
sosioekonomi.html
jenayah.html
persekitaran.html
analisis.html
cadangan.html
rumusan.html
slaid.html
assets/css/style.css
assets/js/main.js
assets/js/charts.js
data/pendapatan.json
data/jenayah.json
slaid/index.html
slaid/slides.md
slaid/style.css
slaid/app.js
slaid/assets/ (lima imej dan catatan prompt)
README.md
SEMAKAN.md
.nojekyll
```

## Pengehosan GitHub Pages

1. Gunakan repositori baharu `drMurtadha/sekolah-selamat`.
2. Letakkan semua kandungan folder laman pada akar repositori, bukan dalam folder tambahan.
3. Commit dan push fail ke cabang `main`.
4. Buka Settings → Pages.
5. Pilih Deploy from a branch.
6. Pilih `main` dan `/ (root)`, kemudian Save.
7. Tunggu penerbitan selesai, kemudian buka https://drmurtadha.github.io/sekolah-selamat/.

## Menyunting

Sunting fail HTML halaman berkaitan secara terus. Sunting data JSON bersama jadual HTML apabila data berubah. `slaid/index.html` ialah dek lengkap dengan gaya dan skrip terbenam; folder `slaid/assets/` mesti dikekalkan untuk gambar. `slaid/slides.md` menyimpan kandungan dan nota pembentang sebagai rujukan editorial. Tiada proses binaan automatik dijalankan.

Slaid: anak panah kiri/kanan untuk navigasi, F skrin penuh, N nota, O semua slaid. Nota muncul pada skrin yang sama. Cetak / PDF mencetak slaid.

## Sumber dan batasan

Sumber ialah Lampiran dalam `Arahan_ChatGPT_Laman_Web_Laporan_Keselamatan_Sekolah_2026.md` yang dibekalkan pengguna. Semua pautan asal terdapat di halaman Rumusan. Nilai Malaysia bagi median pendapatan 2019 tiada dalam sumber dan disimpan sebagai `null`.

Teks sumber menyebut lima cadangan teknologi dalam ringkasan tetapi menyenaraikan T1 hingga T6. Kedua-duanya dikekalkan bagi mematuhi arahan mengekalkan kandungan. Batasan sampel dua kes dan siasatan belum selesai turut dikekalkan.

## Penafian

Laman ini disusun daripada laporan media dan data terbuka kerajaan sehingga 7 Oktober 2026. Ia bukan statistik rasmi PDRM atau KPM. Kedua-dua kes masih dalam siasatan; sila semak status terkini sebelum memetik.
