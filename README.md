# Data Cleansing dan Data Enrichment

## Identitas

**Nama:** M. Arif Setya Utama  

---

## Deskripsi Project

Project ini merupakan penerapan Data Cleansing dan Data Enrichment
pada dataset Employee Management Data.

Dataset terdiri dari 40 data karyawan dengan informasi mengenai
Employee ID, Full Name, Department, Designation, Hire Date,
dan Annual Salary (USD).

---

## Dataset

Dataset yang digunakan adalah:

**Employee Management Data**

Jumlah data awal:
- 40 baris
- 6 atribut

Atribut awal:
1. Employee ID
2. Full Name
3. Department
4. Designation
5. Hire Date
6. Annual Salary (USD)

---

## Data Cleansing

Tahapan Data Cleansing yang dilakukan meliputi:

1. Pemeriksaan struktur dataset
2. Pemeriksaan missing value
3. Pemeriksaan data duplikat
4. Pemeriksaan duplikasi Employee ID
5. Pembersihan data teks
6. Konversi tipe data Hire Date
7. Konversi tipe data Annual Salary
8. Pemeriksaan outlier Annual Salary
9. Penghapusan kolom yang tidak diperlukan

### Hasil Data Cleansing

Setelah proses Data Cleansing diperoleh:

- Jumlah baris: 40
- Jumlah kolom sebelum enrichment: 6
- Missing value: 0
- Duplicate data: 0
- Duplicate Employee ID: 0
- Outlier Annual Salary: 0

---

## Data Enrichment

Data Enrichment dilakukan dengan menambahkan beberapa atribut baru,
yaitu:

1. Hire Year
2. Years of Service
3. Service Category
4. Monthly Salary (USD)

Dengan demikian dataset akhir memiliki:

- 40 baris
- 10 kolom

---

## Analisis

Analisis dilakukan berdasarkan:

- Jumlah karyawan berdasarkan Department
- Rata-rata Annual Salary berdasarkan Department
- Distribusi kategori masa kerja
- Hubungan Years of Service dengan Annual Salary

### Jumlah Karyawan Berdasarkan Department

Setiap department memiliki 4 karyawan.

### Rata-rata Annual Salary

| Department | Rata-rata Salary (USD) |
|---|---:|
| Information Technology | 63,250 |
| Quality Assurance | 58,750 |
| Finance | 58,250 |
| Sales | 56,250 |
| Production | 56,000 |
| Research and Development | 54,500 |
| Operations | 52,500 |
| Marketing | 51,250 |
| Customer Service | 50,750 |
| Human Resources | 50,000 |

---

## Kesimpulan

Dataset Employee Management Data telah melalui proses Data
Cleansing dan Data Enrichment.

Hasil akhir menunjukkan bahwa dataset memiliki 40 data dan
10 atribut, tanpa missing value, duplicate data, maupun
duplicate Employee ID.

Data enrichment menghasilkan informasi tambahan berupa Hire Year,
Years of Service, Service Category, dan Monthly Salary (USD).

Dataset hasil pengolahan dapat digunakan untuk analisis lebih lanjut
mengenai data karyawan, department, gaji, dan masa kerja.
