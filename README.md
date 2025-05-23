# Update 2025
Ini skrip python yang mengupdate skrip devbernardi untuk format baru e-statement Bank BCA tahun 2025. Hasil skrip ini sebuah file Excel, bukan CSV.

original: https://github.com/devbernardi/Estatement-BCA-pdf-to-CSV-or-Excel

## Tentang SECURED PDF 
Sejak October 2024, PDF e-statement yang bisa didapat dari BCA adalah SECURED PDF. Seharusnya skrip ini tidak ada masalah, tapi jika ada kendala silahkan mengunlock PDFnya dulu. Misalnya dengan membuka PDF di Google Chrome > Print > Save as PDF.   

UPDATED DESCRIPTION
---

# Konverter PDF E-Statement

Skrip Python ini mengonversi e-statement PDF dari Bank Central Asia (BCA) menjadi format CSV. Skrip ini mengekstrak detail transaksi seperti tanggal, deskripsi, jumlah debet/kredit, dan saldo berjalan dari laporan PDF.

## Fitur

- Mengonversi e-statement BCA dari PDF ke format CSV.
- Mengekstrak detail transaksi termasuk tanggal, deskripsi, jumlah debet/kredit, dan saldo berjalan.
- Menangani beberapa file PDF dalam satu direktori atau memproses satu file PDF.
- Memverifikasi keakuratan data yang dikonversi dengan membandingkan saldo akhir dengan saldo yang disediakan.

## Instalasi

1. Klon repositori:

```bash
git clone https://github.com/RavioliPopcorn/Estatement-BCA-pdf-to-CSV-or-Excel
```

2. Arahkan ke direktori proyek:
```bash
cd konverter-pdf-e-statement
```
3. Instal dependensi yang diperlukan:
```bash
pip install -r requirements.txt
```
## Penggunaan
Memproses File PDF

Satu File
Untuk memproses satu file PDF, jalankan perintah berikut:

```bash
python main.py /path/ke/file/pdf_anda.pdf
```
Ganti /path/ke/file/pdf_anda.pdf dengan path aktual ke file PDF Anda.

## Beberapa File dalam Satu Direktori
Untuk memproses beberapa file PDF dalam satu direktori, gunakan opsi -dir atau --directory diikuti dengan path direktori:

```bash
python main.py --directory /path/ke/direktori/anda
```
Ganti /path/ke/direktori/anda dengan path aktual ke direktori yang berisi file PDF.

## Lisensi
MIT License

Copyright (c) 2024 devbernardi
