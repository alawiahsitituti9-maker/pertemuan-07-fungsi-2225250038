# Pertemuan 07 — Fungsi Python

**Mata Kuliah:** Algoritma dan Pemrograman  
**Nama       :** siti tuti alawiah  
**NIM        :** 2225250038  
**Kelas      :** 3f

## 1. Tujuan

Mempelajari penggunaan fungsi, parameter, argumen, return value,
dan scope variabel dalam Python.

Program dibuat agar kode lebih terstruktur, mudah dibaca,
dapat digunakan kembali, dan mudah diuji.

## 2. Struktur Folder

```text
pertemuan-07-fungsi-NIM/
├── README.md
├── .gitignore
├── latihan/
│   ├── 01_salam.py
│   ├── 02_luas_persegi_panjang.py
│   ├── 03_jumlah_n.py
│   ├── 04_statistik_sederhana.py
│   └── 05_scope.py
└── praktik/
    └── utilitas_matematika.py
```

## 3. Daftar Latihan

1. `01_salam.py`: fungsi salam dengan parameter nama dan kelas.
2. `02_luas_persegi_panjang.py`: menghitung luas menggunakan return.
3. `03_jumlah_n.py`: menghitung jumlah bilangan 1 sampai n.
4. `04_statistik_sederhana.py`: mencari minimum, maksimum,
   dan rata-rata data.
5. `05_scope.py`: mempelajari local scope dan global scope.
6. `utilitas_matematika.py`: program menu untuk perhitungan matematika.

## 4. Struktur Fungsi Praktik

| Fungsi | Parameter | Kegunaan |
|---|---|---|
| `luas_persegi_panjang(p, l)` | p, l | Menghitung luas persegi panjang |
| `luas_segitiga(a, t)` | a, t | Menghitung luas segitiga |
| `jumlah_n(n)` | n | Menjumlahkan bilangan 1 sampai n |
| `faktorial(n)` | n | Menghitung faktorial |
| `tampilkan_menu()` | Tidak ada | Menampilkan menu program |
| `main()` | Tidak ada | Mengatur alur program |

Fungsi perhitungan menggunakan `return` agar hasil dapat
digunakan kembali oleh bagian program lain.

## 5. Cara Menjalankan

Pastikan Python sudah terpasang di komputer dan folder proyek
sudah dibuka melalui VS Code.

Jalankan setiap latihan menggunakan terminal:

```bash
python latihan/01_salam.py
python latihan/02_luas_persegi_panjang.py
python latihan/03_jumlah_n.py
python latihan/04_statistik_sederhana.py
python latihan/05_scope.py
```

Jalankan program praktik:

```bash
python praktik/utilitas_matematika.py
```

Pada beberapa sistem operasi, gunakan `python3` sebagai
pengganti `python` jika diperlukan.

## 6. Hasil Pengujian

| Program | Input | Hasil yang Diharapkan |
|---|---|---|
| Luas persegi panjang | 8 dan 5 | 40 |
| Luas segitiga | 10 dan 6 | 30.0 |
| Jumlah bilangan | n = 10 | 55 |
| Faktorial | n = 5 | 120 |
| Faktorial | n = 0 | 1 |
| Statistik | [70, 80, 65, 90, 75] | Min = 65, maks = 90, rata-rata = 76.0 |

Hasil aktual dan status pengujian diisi setelah program dijalankan.

## 7. Konsep yang Dipelajari

- `def` digunakan untuk mendefinisikan fungsi.
- Parameter menerima data, sedangkan argumen adalah nilai
  yang diberikan ketika fungsi dipanggil.
- `return` mengembalikan nilai dari fungsi.
- Local scope membatasi akses variabel di dalam fungsi.
- Pengujian membantu memastikan hasil program sesuai harapan.

## 8. Refleksi

Penggunaan fungsi membuat program lebih terstruktur karena
setiap fungsi memiliki tugas yang jelas. Rumus tidak perlu
ditulis berulang kali. Parameter memungkinkan fungsi digunakan
untuk input berbeda, sedangkan return memungkinkan hasil
perhitungan dipakai kembali.

## 9. Sumber

Bahan Ajar Pertemuan 07 — Fungsi, Parameter, Return Value,
dan Scope dalam Python di VS Code dan Pengumpulan melalui GitHub.

## 10. Repositori GitHub

URL repositori: Isi URL GitHub Kamu