# Dashboard Penjualan: Studi Kasus HCI dan Visualisasi Data

Implementasi kode dari materi **Human–Computer Interaction (HCI) dan Visualisasi Data**
(Informatics Practitioner Lecture Series 2026, Arafat Febriandirza, BRIN).

Studi kasus: **Budi**, analis data, membutuhkan dashboard penjualan yang cepat dan mudah dipahami sebelum rapat.

**Nama:** _isi nama_  |  **NIM:** _isi NIM_  |  **Mata kuliah:** Interaksi Manusia dan Komputer

## Buka di Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USERNAME/NAMA_REPO/blob/main/hci_dashboard_visualisasi_data.ipynb)

> Ganti `USERNAME` dan `NAMA_REPO` dengan milikmu.

## Isi Repository
| File | Keterangan |
|---|---|
| `hci_dashboard_visualisasi_data.ipynb` | Notebook utama (analisis + dashboard interaktif) |
| `data_penjualan.csv` | Dataset penjualan sintetis (4.000 transaksi, 5 kota) |
| `hasil_ringkasan_kota.csv` | Ringkasan penjualan per kota dan kategori |
| `hasil_skor_sus.csv` | Skor System Usability Scale (data simulasi) |
| `dashboard_penjualan.html` | Dashboard interaktif, buka langsung di browser |
| `grafik_pemilihan_jenis.png` | Line, bar, scatter, dan pie sesuai tujuan analisis |
| `grafik_jujur_vs_menyesatkan.png` | Perbandingan visualisasi jujur dan menyesatkan |
| `grafik_gestalt_sorot_kota.png` | Penerapan Gestalt dan warna ramah buta warna |
| `grafik_sus.png` | Hasil evaluasi kegunaan |
| `requirements.txt` | Library yang dibutuhkan |

## Konsep yang Diimplementasikan
1. Persona, skenario, functional dan non-functional requirements
2. Pemilihan grafik sesuai tujuan analisis
3. Etika visualisasi (sumbu mulai dari 0)
4. Kontras WCAG, palet ramah buta warna, prinsip Gestalt
5. Dashboard *overview → zoom and filter → details on demand*
6. 10 heuristik kegunaan Nielsen dalam kode
7. Evaluasi kegunaan dengan SUS

## Cara Menjalankan Lokal
```bash
pip install -r requirements.txt
jupyter notebook hci_dashboard_visualisasi_data.ipynb
```
