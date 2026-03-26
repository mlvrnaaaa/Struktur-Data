#  Sistem sederhana pengelolaan nilai mahasiswa menggunakan array
# 1. Penjelasan Konsep Array

Pada program menggunakan array untuk menyimpan nilai mahasiswa.

data = []

Array berfungsi sebagai tempat untuk menyimpan banyak nilai dalam satu variabel. Dalam program ini, array data digunakan untuk menampung 10 nilai mahasiswa yang diinput oleh pengguna.

Cara kerja array dalam program:
Data dimasukkan ke dalam array menggunakan [data.append(n)] 
Data diproses menggunakan perulangan [for n in data]

Fungsi array di program ini:
- Menyimpan nilai mahasiswa
- Mempermudah pencarian nilai tertinggi dan terendah
- Menghitung rata-rata
- Menentukan jumlah mahasiswa yang lulus

Maka array sangat penting karena memungkinkan pengolahan banyak data secara efisien dalam satu struktur.

# 2. Hasil Eksekusi
- Input Nilai

  <img width="657" height="171" alt="image" src="https://github.com/user-attachments/assets/30a1c48f-aef4-485b-a600-d7c3e602bee1" />

- Output Nilai

   <img width="648" height="116" alt="image" src="https://github.com/user-attachments/assets/45a48341-ef4c-4d1f-8cc5-b52d0d7e36ad" />

- Grafik Nilai

   <img width="640" height="480" alt="grafik nilai 2" src="https://github.com/user-attachments/assets/5469dea9-37e3-493f-b3a6-dd87e4867642" />

- Grafik Kelulusan

   <img width="640" height="480" alt="grafik lulus 2" src="https://github.com/user-attachments/assets/2b7c8855-a793-4b42-a687-f1958476292b" />


# 3. Analisis Kompleksitas

| No | Bagian Program     | Kode Terkait                | Penjelasan                                                            | Kompleksitas |
| -- | ------------------ | --------------------------- | --------------------------------------------------------------------- | ------------ |
| 1  | Input nilai        | `for i in range(jumlah)`    | Menginput nilai sebanyak n kali (sesuai jumlah mahasiswa)             | O(n)         |
| 2  | Validasi input     | `while True` + `try-except` | Validasi dilakukan sampai input benar (diasumsikan konstan)           | O(1)         |
| 3  | Proses data        | `for n in data`             | Loop untuk mencari nilai tertinggi, terendah, total, dan jumlah lulus | O(n)         |
| 4  | Hitung rata-rata   | `total / len(data)`         | Operasi matematika sederhana                                          | O(1)         |
| 5  | Hitung tidak lulus | `len(data) - lulus`         | Operasi sederhana                                                     | O(1)         |
| 6  | Menampilkan hasil  | `print()`                   | Menampilkan output ke layar                                           | O(1)         |
| 7  | Menampilkan grafik | `plt.bar()`                 | Menampilkan grafik dengan data tetap (tidak tergantung n besar)       | O(1)         |


**Kesimpulan :**
- Kompleksitas total program adalah: O(n)
- Karena proses utama (input & pengolahan data) dilakukan dengan perulangan sebanyak jumlah data

# 4. Refleksi Pembelajaran

Dari pembuatan program ini, saya memperoleh beberapa pembelajaran penting, yaitu:

**1. Pemahaman array (list)**
- Digunakan untuk menyimpan banyak data dalam satu variabel

**2. Penggunaan perulangan (loop)**
- Mempermudah pengolahan data secara berulang

**3. Penggunaan percabangan (if)**
- Untuk menentukan nilai tertinggi, terendah, dan kelulusan

**4. Penggunaan fungsi (function)**
- Membuat program lebih terstruktur dan mudah dipahami

**5. Validasi input**
- Menghindari kesalahan input dari pengguna

**6. Visualisasi data**
- Menggunakan grafik untuk mempermudah interpretasi data

**Kesimpulan :**
Program ini membantu meningkatkan pemahaman dasar pemrograman seperti struktur data, logika, dan pembuatan program yang terorganisir serta mudah dikembangkan.
     
   

  
  

