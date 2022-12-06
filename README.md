# DETEKSI MATA PRIA DAN WANITA
## ✨ KELOMPOK 4 A2-20✨

Anggota Kelompok:
1. 2009106033 - Muhammad Arsy Dewantara
2. 2009106027 - Indah Wulan Lestari
3. 2009106039 - Mira Sartika Lengkong

## Table of Content
- [Jobs Desk](#jobs-desk)
- [Pendeteksi Mata Pria dan Wanita](#pendeteksi-mata-pria-dan-wanita)
- [Datasets](#dataset)
- [Tahapan Pengerjaan](#tahapan-pengerjaan)
    - [Data Collecting](#data-collecting)
    - [Data Preprocessing](#data-preprocessing)
    - [Data Analysis dan Visualization](#data-analysis-dan-visualization)
    - [Data Modelling](#data-modelling)

## Jobs Desk
- Muhammad Arsy Dewantara : Ketua Kelompok, Split Data, Load data, Modelling Epoch, dan Save Model
- Indah Wulan Lestari : Perbandingan Epoch, Evaluasi, Predict Data, Dokumentasi README
- Mira Sartika Lengkong : Data Augmented, Data Analysis & Data Visualization


## Pendeteksi Mata Pria dan Wanita
Saat ini semakin banyak orang yang terkadang penampilannya tidak sesuai dengan jenis kelaminnya. maka dari itu projek pendeteksi mata ini dapat digunakna untuk mengetahui jenis kelamin seseorang apakah ia pria atau wanita.

## Dataset
Pada dataset yang kami gunakan hanya terdapat dua macam yaitu mata pria dan wanita, yang terbagi menjadi data train, test, dan validation.

Dataset ini terdiri dari 16.500 gambar pria dan wanita
Seluruh gambar berukuran 53 x 53 pixels yang terbagi menjadi:
- 10675 gambar pada data train
- 1684 gambar pada data test
- 4141 gambar pada data validation

Dataset yang kami ambil merupakan salah satu data yang kami temukan di Kaggle.

URL : https://www.kaggle.com/datasets/pavelbiz/eyes-rtte?select=maleeyes

## Tahapan Pengerjaan:
#### Data Collecting
> Data collecting kami berdasarkan dengan kumpulan data yang terdapat pada kaggle. 

### Data Preprocessing
> Pada data preprocessing membuat data gambar Augmentasi dan load data

### Data Analysis dan Visualization
> Mengvisualisasi hasil prediksi dengan menampilkan visualisasi data dari class nya masing-masing.

### Data Modelling
>  Membuat model Sequential dan Visualisasi : Accuracy & Loss Model.
>  Evaluasi Model.
>  Save Model
