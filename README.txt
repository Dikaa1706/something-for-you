OUR LITTLE WORLD — WEBSITE KENANGAN ROMANTIS

CARA MENJALANKAN
1. Ekstrak file ZIP (jika kamu mengunduh versi ZIP).
2. Buka foldernya, lalu klik dua kali index.html. Website akan dibuka di browser.
3. Koneksi internet dibutuhkan untuk Google Fonts, foto contoh online, dan pemutar video resmi YouTube.

CARA MENGGANTI FOTO DENGAN FOTO KALIAN
1. Buat folder bernama images di folder yang sama dengan index.html.
2. Salin foto kalian ke folder images, misalnya:
   images/kenangan-1.jpg
   images/kenangan-2.jpg
   images/kenangan-3.jpg
3. Buka index.html memakai VS Code atau editor teks.
4. Cari elemen <img src="https://images.unsplash.com/..." ... /> dan ganti URL di dalam src dengan nama file lokal, contoh:
   src="images/kenangan-1.jpg"
5. Ulangi untuk foto lainnya. Ganti juga teks <figcaption> agar cocok dengan kenangan kalian.

BAGIAN YANG BISA DISESUAIKAN
- Nama/teks pembuka: cari bagian dengan id="home".
- Galeri dan caption: cari id="kenangan".
- Tanggal serta cerita hubungan: cari id="timeline".
- Surat cinta: cari id="letterPaper".
- Pemutar lagu: bagian id="musik" memakai video resmi Westlife di YouTube; tidak ada file lagu berhak cipta yang disertakan.

CATATAN
- Foto yang disediakan adalah foto contoh dari Unsplash dan memerlukan internet.
- Pemutar lagu menggunakan embed YouTube resmi. Jika video tidak bisa diputar, buka tautan resminya:
  https://www.youtube.com/watch?v=ulOb9gIGGd0
- Website ini satu halaman dan seluruh CSS serta JavaScript sudah berada di index.html.
