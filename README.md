<h1 align="center">Welcome to Wilayah Indonesia 👋</h1>
<p>
  <a href="https://github.com/mocfaisal/wilayah2/blob/main/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/mocfaisal" target="_blank">
    <img alt="Twitter: mocfaisal" src="https://img.shields.io/twitter/follow/mocfaisal.svg?style=social" />
  </a>
</p>

> Kode Relasi Wilayah Indonesia Badan Pusat Statistik (BPS) dengan Kementerian Dalam Negeri Republik Indonesia (Kemendagri)

> Kode Wilayah yang direlasikan adalah Kode Wilayah Kerja Statistik pada tahun 2020 Semester 2 dengan Kode Wilayah Adminitstrasi pada tahun 2020.


## Features

```
- Relasi antar table : Provinsi, Kabupaten, Kecamatan, Kelurahan/Desa.
- Struktur table sama : id, kode_bps, nama_bps, kode_dagri, nama_dagri.
```
***
## Data Wilayah

| id_prov | Nama                 | Kabupaten | Kota | Kabupaten/Kota | Kecamatan | Kelurahan | Desa   | Kelurahan/Desa |
| ------- | -------------------- | --------- | ---- | -------------- | --------- | --------- | ------ | -------------- |
| 1       | ACEH                 | 18        | 5    | 23             | 288       | -         | 6.463  | 6.463          |
| 2       | SUMATERA UTARA       | 25        | 8    | 33             | 449       | 692       | 5.315  | 6.007          |
| 3       | SUMATERA BARAT       | 12        | 7    | 19             | 179       | 230       | 928    | 1.158          |
| 4       | RIAU                 | 10        | 2    | 12             | 169       | 268       | 1.590  | 1.858          |
| 5       | JAMBI                | 9         | 2    | 11             | 141       | 161       | 1.368  | 1.529          |
| 6       | SUMATERA SELATAN     | 13        | 4    | 17             | 241       | 386       | 2.853  | 3.239          |
| 7       | BENGKULU             | 9         | 1    | 10             | 129       | 172       | 1.340  | 1.512          |
| 8       | LAMPUNG              | 13        | 2    | 15             | 228       | 204       | 2.422  | 2.626          |
| 9       | KEP. BANGKA BELITUNG | 6         | 1    | 7              | 47        | 82        | 309    | 391            |
| 10      | KEP. RIAU            | 5         | 2    | 7              | 75        | 141       | 270    | 411            |
| 11      | DKI JAKARTA          | 1         | 5    | 6              | 44        | 267       | -      | 267            |
| 12      | JAWA BARAT           | 18        | 9    | 27             | 627       | 645       | 5.312  | 5.957          |
| 13      | JAWA TENGAH          | 29        | 6    | 35             | 576       | 753       | 7.809  | 8.562          |
| 14      | DI YOGYAKARTA        | 4         | 1    | 5              | 78        | 46        | 392    | 438            |
| 15      | JAWA TIMUR           | 29        | 9    | 38             | 666       | 775       | 7.721  | 8.496          |
| 16      | BANTEN               | 4         | 4    | 8              | 155       | 313       | 1.238  | 1.551          |
| 17      | BALI                 | 8         | 1    | 9              | 57        | 80        | 636    | 716            |
| 18      | NUSA TENGGARA BARAT  | 8         | 2    | 10             | 117       | 145       | 995    | 1.140          |
| 19      | NUSA TENGGARA TIMUR  | 21        | 1    | 22             | 309       | 326       | 2.995  | 3.321          |
| 20      | KALIMANTAN BARAT     | 12        | 2    | 14             | 151       | 95        | 1.753  | 1.848          |
| 21      | KALIMANTAN TENGAH    | 13        | 1    | 14             | 136       | 138       | 1.432  | 1.570          |
| 22      | KALIMANTAN SELATAN   | 11        | 2    | 13             | 153       | 141       | 1.855  | 1.996          |
| 23      | KALIMANTAN TIMUR     | 7         | 3    | 10             | 103       | 197       | 840    | 1.037          |
| 24      | KALIMANTAN UTARA     | 4         | 1    | 5              | 53        | 35        | 424    | 459            |
| 25      | SULAWESI UTARA       | 11        | 4    | 15             | 171       | 331       | 1.502  | 1.833          |
| 26      | SULAWESI TENGAH      | 12        | 1    | 13             | 175       | 175       | 1.831  | 2.006          |
| 27      | SULAWESI SELATAN     | 21        | 3    | 24             | 311       | 785       | 2.245  | 3.030          |
| 28      | SULAWESI TENGGARA    | 15        | 2    | 17             | 219       | 369       | 1.890  | 2.259          |
| 29      | GORONTALO            | 5         | 1    | 6              | 77        | 72        | 657    | 729            |
| 30      | SULAWESI BARAT       | 6         | -    | 6              | 69        | 73        | 575    | 648            |
| 31      | MALUKU               | 9         | 2    | 11             | 118       | 33        | 1.197  | 1.230          |
| 32      | MALUKU UTARA         | 8         | 2    | 10             | 115       | 118       | 1.051  | 1.169          |
| 33      | PAPUA BARAT          | 12        | 1    | 13             | 218       | 95        | 1.733  | 1.828          |
| 34      | PAPUA                | 28        | 1    | 29             | 552       | 95        | 5.178  | 5.273          |
| Total   | Total                | 416       | 98   | 514            | 7.196     | 8.438     | 74.119 | 82.557         |

***
## Usage

```sh
- Create Database
- Import (.sql.zip) file to database with phpMyAdmin
```

## Author

👤 **Mochammad Faisal**

* Twitter: [@mocfaisal](https://twitter.com/mocfaisal)
* Github: [@mocfaisal](https://github.com/mocfaisal)
* LinkedIn: [@mocfaisal](https://linkedin.com/in/mocfaisal)

## Referensi
- Kode dan Data Relasi Wilayah Indonesia [Badan Pusat Statistik](https://sig.bps.go.id/bridging-kode/index)
- Penetapan Nama, Kode Dan Jumlah Desa Seluruh Indonesia Tahun 2020 ([Kepmendagri No. 146.1-4717 - 2020](http://binapemdes.kemendagri.go.id/produkhukum/detil/keputusan-menteri-dalam-negeri-nomor-1461-4717-tahun-2020))

***
## Know Bugs
- [x] Fix Kelurahan Mukti Lincir, kode dagri belum ada. Fixed ([Kepmendagri No. 146.1-4717 - 2020](http://binapemdes.kemendagri.go.id/produkhukum/detil/keputusan-menteri-dalam-negeri-nomor-1461-4717-tahun-2020))

***
## Show your support

Give a ⭐️ if this project helped you!