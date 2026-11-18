# Analisis Data Penumpang *Subway* New York City per Jam, Januari–November 2026

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fxrdhan/analisis-penumpang-subway-nyc-2026/blob/main/Analisis_Penumpang_Subway_NYC_2026.ipynb)

Tugas kelompok mata kuliah **Data Sains dan Analisis**: pengumpulan data, *pre-processing*, penelaahan data
(*exploratory data analysis*), dan persiapan data untuk pemodelan dengan *dataset* MTA Subway Hourly Ridership.

| Nama | NIM |
|---|---|
| Muhammad Raffi Ibrahim | 101032300020 |
| Zacky Yusup Hakim | 101032300183 |
| Firdaus Arif Ramadhani | 101032300131 |

## Isi folder

| Berkas | Isi |
|---|---|
| `Analisis_Penumpang_Subway_NYC_2026.ipynb` | *Notebook* yang sudah dijalankan di Google Colab, lengkap dengan keluarannya |
| `Analisis_Penumpang_Subway_NYC_2026.py` | Sumber *notebook* dalam format *percent* (jupytext), isinya sama dengan sel-sel *notebook* |
| `laporan/` | Laporan formal (DOCX dan PDF) yang seluruh angkanya diambil dari keluaran *notebook* |

## Data

- Sumber: [MTA Subway Hourly Ridership: Beginning 2025](https://data.ny.gov/d/5wq4-mkjj), diambil lewat SODA API.
- Versi data: `Last-Modified` = `Wed, 18 Nov 2026 15:33:05 GMT`.
- Periode: 1 Januari 2026 pukul 00.00 sampai 11 November 2026 pukul 23.00 (jam terakhir pada versi tersebut),
  17.584.367 baris.

## Menjalankan *notebook*

Buka *notebook* di Google Colab lewat tombol **Open in Colab** di atas, lalu pilih **Runtime → Run all**. Colab membuka *notebook* langsung dari repositori ini; perubahan disimpan kembali ke repositori melalui **File → Save a copy in GitHub**. Seluruh sel selesai
dalam sekitar 20 menit dan tidak memerlukan berkas lain. *Notebook* hanya menerima data dari versi di atas; setelah MTA
menerbitkan pembaruan mingguan berikutnya, ikuti petunjuk di bagian 3.1 *notebook* untuk beralih ke versi baru.
