![Screenshot 2023-10-11 144451](https://github.com/askenas/PrakPemin-A_Tugas4/assets/134838656/2497bea7-2e69-4b49-95b3-915a141f4ab4)# PrakPemin-A_Tugas4
1. GET
Untuk menambahkan endpoint dengan method GET pada aplikasi kita, kita dapat
mengunjungi file web.php pada folder routes. Kemudian tambahkan baris ini pada akhir
file![Screenshot 2023-10-11 143602](https://github.com/askenas/PrakPemin-A_Tugas4/assets/134838656/87b85bf3-09fe-4bba-ae48-378fe64477bb)
Setelah itu coba jalankan aplikasi dengan command,
![Screenshot 2023-10-11 143700](https://github.com/askenas/PrakPemin-A_Tugas4/assets/134838656/7b2f1c63-1cd8-4a64-a52c-4604b85b8253)
Setelah itu coba jalankan aplikasi dengan command,
![Screenshot 2023-10-11 143906](https://github.com/askenas/PrakPemin-A_Tugas4/assets/134838656/2010d7f8-8d6f-4091-af54-7276e72f64e7)
3. Migrasi Database
a. Sebelum melakukan migrasi database pastikan server database aktif kemudian
pastikan sudah membuat database dengan nama lumenapi![Screenshot 2023-10-11 144451](https://github.com/askenas/PrakPemin-A_Tugas4/assets/134838656/85464e74-e3d5-4443-94fd-1a74fdf36434)

b. Kemudian ubah konfigurasi database pada file .env menjadi seperti ini![Screenshot 2023-10-11 144850](https://github.com/askenas/PrakPemin-A_Tugas4/assets/134838656/864db766-9980-48de-8b69-9ff69824bea8)
c. Setelah mengubah konfigurasi pada file .env, kita juga perlu menghidupkan
beberapa library bawaan dari lumen dengan membuka file app.php pada folder
bootstrap dan mengubah baris ini,![Screenshot 2023-10-11 145004](https://github.com/askenas/PrakPemin-A_Tugas4/assets/134838656/cacecd15-1e3d-454f-8342-baa9ebe4e70f)
Setelah itu jalankan command berikut untuk membuat file migration,![Screenshot 2023-10-11 144850](https://github.com/askenas/PrakPemin-A_Tugas4/assets/134838656/0d8df88b-b5b5-4e36-a217-30ad4ed44a57)
Setelah itu jalankan command berikut untuk membuat file migration,
![Screenshot 2023-10-11 145339](https://github.com/askenas/PrakPemin-A_Tugas4/assets/134838656/1cabc6bc-3b2a-40ae-894b-8ce136378895)
Ubah fungsi up pada file migrasi create_products_table
![Screenshot 2023-10-11 145309](https://github.com/askenas/PrakPemin-A_Tugas4/assets/134838656/8523c440-316e-47b2-8a9f-a981714c87ab)
Kemudian jalankan command,
![Screenshot 2023-10-11 150820](https://github.com/askenas/PrakPemin-A_Tugas4/assets/134838656/e5e7ec04-b369-4c86-81f8-4d388865a9a1)











