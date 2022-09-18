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