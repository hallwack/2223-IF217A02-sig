# Judul

## Deskripsi Masalah

- Penumpang baru belum mengetahui jalur mana saja yang dilalui oleh bus
- Penumpang baru belum mengetahui halte yang terdekat dari posisi
- \*Penumpang tidak mengetahui bus sudah sampai mana
- \*Penumpang tidak mengetahui kapan bus selanjutnya tiba

## Deskripsi Solusi

- Membuat aplikasi yang menyajikan informasi lengkap mengenai trayek bus
- Menyediakan pencarian halte terdekat dari penumpang ketika membuka aplikasi
- \*Menyediakan fitur dimana penumpang dapat mengetahui posisi bus sekarang

## Use Case

- Pengguna dapat mengetahui jalur mana saja yang dilalui oleh bus
- Pengguna dapat mengetahui halte terdekat ketika membuka aplikasi dengan menghidupkan GPS
- \*Pengguna dapat mengetahui posisi bus
- \*Pengguna dapat mengetahui kapan bus selanjutnya tiba

## Struktur Data

### Halte

| Nama Atribut | Tipe Data | Contoh                                                                      |
| ------------ | --------- | --------------------------------------------------------------------------- |
| UUID         | string    | ooj73849r734mf34r3                                                          |
| Nama halte   | string    | Alun-alun Bandung                                                           |
| Tipe Halte   | integer   | 1                                                                           |
| 🌏 Koordinat | poin      | [106.03794 -6.39284693]                                                     |
| 🌏 Area      | polygon   | [[106.03794 -6.39284693], [106.03794 -6.39284693], [106.03794 -6.39284693]] |

### Bus

| Nama Atribut         | Tipe Date | Contoh             |
| -------------------- | --------- | ------------------ |
| UUID                 | string    | ooj73849r734mf34r3 |
| Kode Bus             | string    | TMP-001            |
| Trayek Keberangkatan | string    | Alun-alun Bandung  |
| Trayek Tujuan        | string    | Cibiru             |

### User

| Nama Atribut | Tipe Data | Contoh             |
| ------------ | --------- | ------------------ |
| UUID         | string    | ooj73849r734mf34r3 |
| Nama user    | string    | Raihan Adam        |

## Mockup

### Rute
<img width="1440" alt="Rute" src="https://user-images.githubusercontent.com/56082780/198896011-f79ce407-5ab2-4a97-9c5e-279b1e87cd5e.png">

### Halte
<img width="1440" alt="Halte" src="https://user-images.githubusercontent.com/56082780/198896032-8b4b329d-993e-4f37-9486-437a9010b4f9.png">
