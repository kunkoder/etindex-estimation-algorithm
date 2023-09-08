# :bulb: ETindex Estimation Algorithm

Repository ini berisi projek perhitungan evapotranspirasi aktual menggunakan algoritma etindex estimation algorithm. Yang mana algoritma ini menghitung nilai evapotranspirasi berdasarkan suhu udara, kecepatan angin, kelembaban, dan durasi sinar matahari.

## :package: Prasyarat

Sebelum memulai, pastikan telah terinstall beberapa tools:
* Text editor
* Web browser
* Python
* Jupyter Lab

## :cd: Menginstall Aplikasi

Untuk menginstall aplikasi ini, ikuti langkah berikut:

```bash
# clone this repository
git clone https://github.com/kunkoder/etindex-estimation-algorithm.git

# change working directory
cd etindex-estimation-algorithm
```

## :open_file_folder: Struktur Projek

```text
├── dataset
│   ├── climate
│   ├── landsat
│   ├── shape
│   └── srtm
├── output
│   ├── climate
│   ├── landsat
│   └── srtm
└── processing.ipynb
```

## :eyes: Preview

**Evapotranspirasi Aktual**<br>
![alt text](https://raw.githubusercontent.com/kunkoder/etindex-estimation-algorithm/main/images/actual-evapotranspiration.png)

**Suhu Udara dan Elevasi**<br>
![alt text](https://raw.githubusercontent.com/kunkoder/etindex-estimation-algorithm/main/images/thermal-elevation.png)

**Sebaran Vegetasi**<br>
![alt text](https://raw.githubusercontent.com/kunkoder/etindex-estimation-algorithm/main/images/vegetation-distribution.png)

## :balance_scale: Lisensi

[MIT License](https://github.com/kunkoder/espeka/blob/main/LICENSE)
