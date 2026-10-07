# Power BI Dashboard — Online Retail

Dashboard interaktif menggunakan Power BI Desktop — analisis revenue & transaksi 
dataset Online Retail (UK-based e-commerce), lanjutan dari EDA Python di 
[python-data-analysis](https://github.com/MichaelChan07/python-data-analysis).

## Isi Dashboard
- **KPI Card** — Total Revenue (10.64M), Total Transactions (22K)
- **Bar Chart** — Total Revenue & Total Transactions by Country
- **Line Chart** — Tren Total Revenue per bulan (pola musiman, puncak di Q4)
- **Donut Chart** — Total Revenue by Description (Total Revenue 1.15 M)
- **Slicer** — Filter interaktif berdasarkan Country

## Data Cleaning (Power Query)
- Filter transaksi cancelled (InvoiceNo berawalan "C")
- Perbaikan tipe data InvoiceNo (Number → Text) untuk menangani entri non-transaksi 
  seperti "Adjust bad debt"
- Kolom kalkulasi: Revenue = Quantity × UnitPrice

## Insight Utama
UK mendominasi total revenue — bisnis ini sangat bergantung pada 1 pasar, 
berisiko tinggi kalau ada gangguan di sana. Perlu strategi ekspansi pasar lain.

## Tools
Power BI Desktop, Power Query, DAX
