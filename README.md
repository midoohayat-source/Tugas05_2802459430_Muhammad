# Tugas05 — Transfer Learning untuk Klasifikasi Citra dengan Data Terbatas

**Nama:** Muhammad
**NIM:** 280245930
**Mata Kuliah:** Advanced CNNs and Transfer Learning

## Dataset
Oxford-IIIT Pet — subset 10 kelas (5 ras kucing + 5 ras anjing), ~2.000 citra, split stratified 70/15/15.

## Hasil Eksperimen

| Condition | Trainable Params | Test Acc | Test Macro F1 |
|---|---|---|---|
| B1 (scratch) | 11.181.642 | 0.3800 | 0.3656 |
| B2 (feature extraction) | 5.130 | 0.9867 | 0.9867 |
| B3 (fine-tune layer4) | 8.398.858 | 0.9733 | 0.9736 |
| B4 (B3 + augmentasi) | 8.398.858 | 0.9733 | 0.9731 |

## Cara Menjalankan
1. Buka notebook di Google Colab
2. Runtime → Change runtime type → T4 GPU
3. Runtime → Run all

## Struktur
- `Tugas05_280245930__muhammad_.ipynb` — notebook eksperimen
- `Laporan_Tugas05_280245930_Muhammad.docx` — laporan analisis
