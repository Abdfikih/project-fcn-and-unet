# Perbandingan Kode FCN dan U-Net
Sebagai Tugas Akhir UAS Mata Kuliah Pemrosesan Sinyal Multimedia. 
## Pengantar
Dalam dunia pengolahan citra dan segmentasi, FCN dan U-Net adalah dua arsitektur neural network yang populer. Keduanya sering digunakan dalam tugas-tugas seperti segmentasi objek pada citra medis dan pengenalan pola.

## FCN (Fully Convolutional Network)
FCN adalah salah satu dari pendekatan awal yang diperkenalkan untuk memungkinkan penggunaan Convolutional Neural Networks (CNNs) dalam tugas segmentasi piksel demi piksel. Karakteristik utama dari FCN adalah:
- **Konvolusi Penuh**: FCN menggunakan lapisan konvolusi penuh (fully convolutional) untuk menghasilkan peta segmentasi dari input gambar.
- **Upsampling**: FCN menggunakan operasi upsampling untuk memperbesar resolusi dari feature maps yang dihasilkan oleh lapisan konvolusi.

## U-Net
U-Net adalah arsitektur neural network yang dirancang khusus untuk tugas segmentasi citra biomedis. Dibandingkan dengan FCN, U-Net memiliki beberapa perbedaan kunci, antara lain:
- **Struktur Encoder-Decoder**: U-Net memiliki struktur encoder-decoder yang memungkinkan informasi spasial untuk dipertahankan melalui serangkaian konvolusi dan upsampling.
- **Shortcut Connections**: U-Net menggunakan shortcut connections antara lapisan encoder dan decoder untuk mengatasi masalah informasi yang hilang selama proses upsampling.

## Perbandingan
Berikut adalah perbandingan singkat antara FCN dan U-Net:
- **FCN**: Cocok untuk tugas segmentasi piksel demi piksel umum pada citra.
- **U-Net**: Lebih efektif untuk segmentasi citra medis dan tugas yang membutuhkan pemeliharaan detail spasial.

## Kesimpulan
Pemilihan antara FCN dan U-Net tergantung pada tugas segmentasi yang dihadapi dan jenis citra yang dianalisis. Keduanya menawarkan pendekatan yang kuat dalam pengolahan citra dan segmentasi, dengan masing-masing memiliki kelebihan dan kelemahan tersendiri.

