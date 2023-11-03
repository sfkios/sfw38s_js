# Changelog

> **Note**
> Pastikan untuk selalu menggunakan SFW38s versi terbaru

Semua perubahan penting pada SFW38s akan didokumentasikan dalam file ini

## [3.0.0] - [Telegram](https://t.me/sfkios/452)

### Keamanan

- Menyembunyikan data pembeli yang seharusnya tidak ditampilkan pada domain/history
  - Produk cek

### Perbaikan

- Perbaikan tombol kembali main.php dan &lt;input&gt; ID Pelanggan
  - Produk dengan Template Token PLN
- Perbaikan Tombol Muat Lainnya
  - Jika tombol diklik 2 kali atau lebih

### Fitur

- Tombol bagikan produk menggunakan [Web Share API](https://w3c.github.io/web-share/demos/share-files.html)
  - [Demo](https://t.me/sfkios/453?single)
- Membuat tombol salin semakin mudah
  - [Demo](https://t.me/sfkios/468)
  - > &lt;input type=&quot;hidden&quot; id=&quot;sf_norek&quot; value=&quot;123456&quot;&gt; 
&lt;a class=&quot;copy&quot; data-id=&quot;#sf_norek&quot; data-name=&quot;No. Rekening disalin&quot; href=&quot;#&quot;&gt;&lt;svg xmlns=&quot;http://www.w3.org/2000/svg&quot; width=&quot;24&quot; height=&quot;24&quot; viewBox=&quot;0 0 24 24&quot;&gt;&lt;g fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot; stroke-width=&quot;2&quot;&gt;&lt;rect width=&quot;14&quot; height=&quot;14&quot; x=&quot;8&quot; y=&quot;8&quot; rx=&quot;2&quot; ry=&quot;2&quot;/&gt;&lt;path d=&quot;M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2&quot;/&gt;&lt;/g&gt;&lt;/svg&gt;&lt;/a&gt; ❌🤯 
  - > &lt;iconify-icon class=&quot;sfcopy&quot; icon=&quot;lucide:copy&quot; data-clipboard-text=&quot;123456&quot; data-clipboard-notif=&quot;No. Rekening disalin&quot;&gt;&lt;/iconify-icon&gt; ✅😍
```html
<iconify-icon class="sfcopy" icon="lucide:copy" data-clipboard-text="123456" data-clipboard-notif="No. Rekening disalin"></iconify-icon>
```
- Ikon &lt;svg&gt; digantikan [&lt;iconify-icon&gt;](https://iconify.design/)
  - &lt;iconify-icon&gt; bawaan menggunakan [Lucide](https://icon-sets.iconify.design/lucide/), dapat diubah, terdapat 150K+ ikon 😱
- Gambar produk pada domain/produk/*

### Ketergantungan

- [jquery@3.7.1](https://www.jsdelivr.com/package/npm/jquery)
- [bootstrap@3.4.1](https://www.jsdelivr.com/package/npm/bootstrap)
- [vanilla-lazyload@17.8.5](https://www.jsdelivr.com/package/npm/vanilla-lazyload)
- [swiper@10.3.1](https://www.jsdelivr.com/package/npm/swiper)
- [iconify-icon@1.0.8](https://www.jsdelivr.com/package/npm/iconify-icon)
- [clipboard@2.0.11](https://www.jsdelivr.com/package/npm/clipboard)
- [jquery-mask-plugin@1.14.16](https://www.jsdelivr.com/package/npm/jquery-mask-plugin)

## [↓3.0.0]

Versi SFW38s ↓3.0.0 tidak lagi didukung
