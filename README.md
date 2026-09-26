Velocity Child Theme Paket Toko Online Toko 11
=================
[toko11.velocitydeveloper.com](https://toko11.velocitydeveloper.com/)

Child Theme for the Velocity System WordPress theme.

### Required
Theme Velocity versi 2.7.0 keatas, [Download](https://github.com/VelocityDeveloper/velocity/releases)

### Required Plugins
**VD Store**, [Download](https://github.com/Velocity-Developer/vd-store/releases) — produk `store_product`,
kategori `store_product_cat`, merek `brand`. Sejak 1.1.0 tema tidak lagi memakai plugin Velocity Toko
maupun Kirki.

Integrasi VD Store ada di `inc/vd-store.php`, `css/vd-store.css`, dan template override di folder
`vd-store/` (arsip, kategori, merek, detail produk). Bar atas (warna tema): kontak, profil, keranjang, pencarian produk.

### Beranda
Beranda = `index.php` (Settings > Reading: tulisan terbaru): slider selebar konten di atas sidebar, judul situs, 12 produk terbaru (kartu tanpa tombol keranjang) +
tombol "Produk lainnya" ke arsip produk, artikel terbaru.

### Widget
Shortcode untuk widget Teks (susunan demo, dibaca installer lewat `velocity_tema_widget_sidebar()` dan
`velocity_tema_widget_footer()`):

- Sidebar: `[toko11_kategori]`, `[toko11_produk_terbaru jumlah="5"]`, `[toko11_ekspedisi]`, `[toko11_sosmed facebook="…" twitter="…" instagram="…" youtube=""]`, `[toko11_kontak]`
- Footer: tidak ada widget (demo hanya baris hak cipta)
- Lainnya: `[toko11_cari_produk]`, `[toko11_bank]`, `[toko11_testimoni jumlah="5"]`, `[toko11_info_terbaru]`, `[toko11_best_seller jumlah="5"]`, `[toko11_facebook url="…"]`

### Halaman
Template **Velocity Toko Pricelist** (`page-pricelist.php`): tabel semua produk + tombol Cetak.
Halaman Katalog & Profil Saya VD Store (`page_catalog`/`page_profile`, `[wp_store_catalog]`/`[wp_store_profile]`) selalu tanpa sidebar.

### Customizer
Appearance > Customize > **Velocity Toko 11**: Warna (utama, sekunder), Popup Sambutan (aktif/nonaktif +
isi HTML, tampil sekali sehari per pengunjung), Font (judul & teks), Slider Home (5 slot gambar).
Logo & gambar header: Site Identity / Header Image. Latar website: Background tema induk. Warna teks/link:
Theme Colors tema induk.

### Usage
Simply download the zip and upload the zip (velocity-toko11.zip) under your WordPress dashboard at Appearance > Themes. Or extract and upload via FTP at wp-content/themes/.
