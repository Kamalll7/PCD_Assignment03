# PCD_Assignment03

Tugas Pengolahan Citra Digital (Wahyono, Ph.D.) tentang implementasi metode segmentasi citra dan pemrosesan morfologi (morphological processing) tanpa menggunakan pustaka instan.

Nama: Ucok Kamal NIM: 25/566250/PA/23896

Colab: https://colab.research.google.com/drive/1Z6TJsG9uPhGNelmh4MelII2faMNF0olm?usp=sharing

## Metode

- Otsu Thresholding & Local Adaptive Thresholding
- Binary Dilation & Binary Erosion
- Morphological Opening & Closing
- Morphological Edge Detection (Boundary Extraction)
- Hit-and-Miss Transform
- Binary Thinning & Thickening
- Skeletonization

## Citra Uji

Empat citra dari `skimage.data` : horse, cell, coins, dan page. Setiap citra diuji terhadap kasus gangguan noise latar, lubang internal objek, perbaikan koin, serta penyambungan karakter teks yang terputus, dan dievaluasi secara kuantitatif.

## Evaluasi

Perbandingan dilakukan terhadap citra acuan (ground truth) menggunakan tiga metrik:

- Pixel Accuracy
- Intersection over Union (IoU)
- Dice Coefficient (F1-Score)

## Struktur Repository

├── PCD_Assignment03.ipynb
└── report/
    └── Laporan_PCD_Assignment_3.pdf

Notebook berisi seluruh implementasi, eksperimen, visualisasi, dan hasil evaluasi.
