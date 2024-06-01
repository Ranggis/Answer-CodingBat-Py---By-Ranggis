# CodingBat Solutions

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)

## Deskripsi

**CodingBat Solutions** adalah repositori yang berisi solusi untuk latihan-latihan coding di platform CodingBat. Repositori ini mencakup solusi untuk berbagai kategori seperti String, List, Logic, dan lainnya. Tujuannya adalah untuk membantu pemula belajar pemrograman dan memberikan referensi solusi bagi mereka yang sedang memecahkan masalah di CodingBat.

## Struktur Direktori

Repositori ini diorganisir berdasarkan kategori soal di CodingBat:

```
CodingBat-Solutions/
│
├── String-1/
│   ├── hello_name.py
│   ├── make_abba.py
│   └── ...
│
├── List-1/
│   ├── first_last6.py
│   ├── common_end.py
│   └── ...
│
├── Logic-1/
│   ├── cigar_party.py
│   ├── date_fashion.py
│   └── ...
│
└── README.md
```

## Penggunaan

1. Clone repositori ini:

    ```bash
    git clone https://github.com/username/CodingBat-Solutions.git
    ```

2. Masuk ke direktori proyek:

    ```bash
    cd CodingBat-Solutions
    ```

3. Pilih kategori soal yang ingin Anda pelajari dan buka file Python yang sesuai untuk melihat solusi.

### Contoh Solusi

#### String-1: hello_name

```python
def hello_name(name):
    return "Hello " + name + "!"
```

#### List-1: first_last6

```python
def first_last6(nums):
    return nums[0] == 6 or nums[-1] == 6
```

#### Logic-1: cigar_party

```python
def cigar_party(cigars, is_weekend):
    if is_weekend:
        return cigars >= 40
    else:
        return 40 <= cigars <= 60
```

## Kontribusi

Kami menyambut kontribusi dari siapa saja. Jika Anda ingin berkontribusi, silakan fork repositori ini dan buat pull request. Untuk masalah atau permintaan fitur, silakan buka [issue](https://github.com/username/CodingBat-Solutions/issues).

1. Fork repositori ini
2. Buat branch fitur Anda (`git checkout -b fitur/AmazingFeature`)
3. Commit perubahan Anda (`git commit -m 'Menambahkan beberapa solusi baru'`)
4. Push ke branch (`git push origin fitur/AmazingFeature`)
5. Buat Pull Request

## Lisensi

Proyek ini dilisensikan di bawah lisensi MIT - lihat file [LICENSE](LICENSE) untuk detailnya.


---

Terima kasih telah menggunakan **CodingBat Solutions**! Kami berharap repositori ini dapat membantu Anda dalam perjalanan belajar pemrograman Anda.

---
