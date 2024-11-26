# Praktikum5

Nama : Fauzan Giri Wardana
NIM : 312410535
Kelas : TI.24.A.5
Mata kuliah : Bahasa Pemrograman

# program input nilai
Flowchart

![Flowchart](https://github.com/user-attachments/assets/f159040e-aae1-4dc2-b05f-9e577b027dba)

# Penjelasan Program

1. Judul Program

<img width="184" alt="program input nilai" src="https://github.com/user-attachments/assets/df0ec51c-c96f-48e9-983d-6f4cad29855a">
Baris ini mencetak judul program dan garis pemisah untuk memberikan konteks kepada pengguna.

2. Kelas Student

<img width="275" alt="class" src="https://github.com/user-attachments/assets/f410862e-480b-4c99-abda-ce6b619f8bcc">

Kelas Student: Kelas ini digunakan untuk merepresentasikan seorang mahasiswa
__init__ Method: Ini adalah konstruktor yang dipanggil saat objek Student dibuat. Ini menerima NIM, nama, nilai tugas, UTS, dan UAS sebagai parameter. Nilai akhir dihitung dengan memanggil metode calculate_final_grade.

<img width="398" alt="Screenshot def 2024-11-26 150332" src="https://github.com/user-attachments/assets/047e7b84-09a0-422a-a7fc-51cc19a68d37">

calculate_final_grade Method: Metode ini menghitung nilai akhir berdasarkan bobot yang ditentukan untuk tugas, UTS, dan UAS, kemudian membulatkannya hingga dua desimal.

3.fungsi display_menu

<img width="404" alt="Screenshot display 2024-11-26 150402" src="https://github.com/user-attachments/assets/14554909-457b-40be-9c5f-39aecf55fda8">

Fungsi ini menampilkan menu pilihan kepada pengguna untuk melihat, menambah, mengubah, menghapus, atau mencari data mahasiswa.

4.Fungsi display_students

<img width="576" alt="Display student" src="https://github.com/user-attachments/assets/67718f7c-c7de-4161-9ead-6c1d756d9878">

Fungsi ini menampilkan daftar mahasiswa dalam format tabel. Jika tidak ada mahasiswa, akan menampilkan pesan "TIDAK ADA DATA".

5. Fungsi find_student_index

<img width="272" alt="Student Index 2024-11-26 152248" src="https://github.com/user-attachments/assets/7c458884-faef-4b1a-a62c-b08332fe5a1f">

Fungsi ini mencari indeks mahasiswa berdasarkan NIM. Jika ditemukan, mengembalikan indeksnya; jika tidak, mengembalikan None

6. Fungsi main

<img width="197" alt="Def Main" src="https://github.com/user-attachments/assets/fc3e7bed-eb0c-47cd-a134-937fcf0b5755">

Fungsi main adalah titik masuk program. Ini menginisialisasi daftar mahasiswa dan memasuki loop untuk menerima input dari pengguna.

Menangani Pilihan Pengguna
Tambah Mahasiswa ('t'):

Meminta input NIM, nama, dan nilai, kemudian menambahkan objek Student ke dalam daftar students.
Lihat Mahasiswa ('l'):

Memanggil fungsi display_students untuk menampilkan daftar mahasiswa.
Ubah Mahasiswa ('u'):

Menampilkan daftar mahasiswa, meminta NIM mahasiswa yang ingin diubah, dan jika ditemukan, meminta input baru dan memperbarui data mahasiswa.
Hapus Mahasiswa ('h'):

Menampilkan daftar mahasiswa, meminta NIM mahasiswa yang ingin dihapus, dan jika ditemukan, menghapus data mahasiswa dari daftar.
Cari Mahasiswa ('c'):

Meminta NIM mahasiswa yang dicari dan menampilkan detailnya jika ditemukan.
Keluar ('k'):

Menghentikan loop dan keluar dari program.
Pilihan Tidak Valid:

Jika pilihan tidak dikenali, menampilkan pesan bahwa pilihan tidak valid.

7. Menjalankan Program

<img width="182" alt="If Name Main" src="https://github.com/user-attachments/assets/a94003b5-6af8-4712-b197-d0c55b18b594">

Baris ini memastikan bahwa fungsi main hanya akan dijalankan jika file ini dieksekusi sebagai program utama, bukan jika diimpor sebagai modul.

# hasil perogram
1. Menjalankan Program Setelah menjalankan program, Anda akan melihat output awal seperti ini:

<img width="116" alt="Program input" src="https://github.com/user-attachments/assets/1010ef99-9ace-4a92-a2e9-de132188cc47">

2. Menampilkan Menu Program akan menampilkan menu pilihan:

<img width="269" alt="Menampilkan Menu" src="https://github.com/user-attachments/assets/f1f158aa-bc11-41ca-84ba-df6b0d3dbdd5">

3. Menambah Mahasiswa Jika Anda memilih untuk menambah mahasiswa dengan memasukkan 'T', program akan meminta Anda untuk memasukkan data:

<img width="304" alt="Hasil run" src="https://github.com/user-attachments/assets/c29c0d0e-3d90-4ff3-a58c-d879b09c7a38">

4. Melihat Daftar Mahasiswa Jika Anda memilih 'L', program akan menampilkan daftar mahasiswa:

<img width="390" alt="Daftar Nilai" src="https://github.com/user-attachments/assets/40d1912f-127e-40d7-83d0-2d327c790e24">

5. Mengubah Data Mahasiswa Jika Anda memilih 'U' dan memasukkan NIM mahasiswa yang ingin diubah:

<img width="257" alt="Data ubah" src="https://github.com/user-attachments/assets/c35ec82e-01d4-4667-a699-966c38ec7ab1">



















