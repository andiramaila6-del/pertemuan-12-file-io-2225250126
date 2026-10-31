# Pertemuan 12 - File I/O dan Error Handling

**Nama:** Maila Andira Putri
**NIM:** 2225250126
**Kelas:** 3A

## 1. Tujuan
Membuat program Python untuk membaca, memvalidasi,
mengolah, dan menulis data nilai mahasiswa menggunakan file.

## 2. Struktur Program
- data/nilai.txt: Menyimpan data nilai awal.
- data/hasil_rekap.txt: Menyimpan hasil rekap nilai.
- tugas/rekap_nilai_file.py: Program utama.
- latihan/: Berisi enam latihan file I/O dan error handling.

## 3. Format File Input
Data menggunakan format NIM,nilai.

Contoh:
A001,85
A002,78
A003,92
A004,abc
A005,74
A006,88

## 4. Cara Menjalankan
Jalankan perintah berikut melalui terminal:

python3 tugas/rekap_nilai_file.py

## 5. Error yang Ditangani
- FileNotFoundError: Menangani file input yang tidak ditemukan.
- ValueError: Menangani data nilai yang tidak sesuai format angka.
- Baris kosong: Dilewati agar tidak mengganggu proses.

## 6. Hasil Pengujian

| Pengujian | Hasil |
|---|---|
| Semua data valid | Berhasil diproses |
| File tidak ditemukan | Pesan error ditampilkan |
| Nilai tidak valid | Baris dilewati |
| Baris kosong | Dilewati |
| Nilai 60 | Dihitung lulus |

## 7. Hasil Rekap
- Jumlah data valid: 5
- Rata-rata: 83.40
- Nilai minimum: 74.00
- Nilai maksimum: 92.00
- Jumlah lulus: 5

## 8. Refleksi
Melalui tugas ini, saya belajar membaca dan menulis file menggunakan Python serta menangani kesalahan dengan try-except. Saya juga memahami penggunaan strip(), split(), dan float() untuk memproses data. Dengan adanya error handling, program tetap dapat memproses data lainnya meskipun terdapat satu baris yang tidak valid.