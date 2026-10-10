# SimplexCalc

Kalkulator untuk mempercepat proses pengerjaan manual algoritma **programa linear** menggunakan **Metode Simpleks** dan **Big-M**. Dilengkapi kalkulator matriks aljabar yang matematis, sehingga kesalahan hitung dapat dicegah dan Anda bisa fokus pada pemahaman logika iterasi.

## Fitur

| Tab | Fungsi |
| --- | --- |
| **Kalkulator** | Hitung ekspresi matematika biasa maupun aljabar Big-M (mis. `5-2M`, `3/4:M`). |
| **Rasio** | Mencari baris kunci (pivot ratio) secara otomatis dari tabel solusi dibagi kolom. |
| **Iterasi** | Operasi baris elementer: `Baris Baru = Baris Lama - (K x Baris Kunci)`. |

Semua modul mendukung dua format keluaran:

- **Pecahan** - hasil ditampilkan sebagai bilangan pecahan (contoh `3/4`)
- **Desimal** - hasil ditampilkan sebagai desimal (contoh `0.75`)

## Teknologi

- HTML, CSS, JavaScript (vanilla)
- [Tailwind CSS](https://tailwindcss.com) via CDN
- [Lucide Icons](https://lucide.dev) untuk ikon
- Font: Inter & JetBrains Mono (Google Fonts)

## Menjalankan

Tidak ada build step. Cukup buka `index.html` di browser, atau jalankan server statis:

```bash
python -m http.server 8000
```

## Catatan

Aplikasi ini adalah alat bantu hitung, **bukan** penyelesai otomatis. Fokusnya adalah:

1. Menghitung setiap langkah iterasi dengan benar.
2. Membantu Anda memeriksa kembali perhitungan manual di kertas.

Logika optimasi (penentuan entering/leaving variable) tetap dilakukan manual, sehingga aplikasi ini aman digunakan sebagai alat verifikasi.

## Author

**Rafi** - [LinkedIn](https://www.linkedin.com/in/rafi-sanjaya-43803a30b/) - [Instagram](https://www.instagram.com/mhmmdrfisn)

---

Dibuat sebagai bagian dari portofolio project.