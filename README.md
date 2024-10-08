# Tugas Simulasi UTS
Jadi saya memiliki table Mata Kuliah yang dimana memiliki atribute antara lain Kode MK, sks, Nama MK, dan Semester Aja. Berikut adalah step CRUD dalam table Mata Kuliah :
## create table
ini adalah table Mata Kuliah yang berisi sebagai berikut

![Screenshot 2024-10-08 132504](https://github.com/user-attachments/assets/399c0c7c-9a08-4c3d-8e78-c6480a3c5b78)


## Tampilan Table Mata Kuliah
berikut adalah hasil table Mata Kuliah yang sudah kita buat

![Screenshot 2024-10-08 132543](https://github.com/user-attachments/assets/bc74024f-7608-41a3-b86e-630253bd5b21)

## Koneksi Database
step selanjutnya kita melakukan kodingan untuk menyambungkan netbeans ke postgre, berikut kodingannya

![Screenshot 2024-10-08 132620](https://github.com/user-attachments/assets/31f0be0e-779b-45a7-b5f9-2bbdece5317c)
## Label
selanjutnya kita membuat tampilan, pertama kita menambahkan label dari menu palette ke form kita

![Screenshot 2024-10-08 132658](https://github.com/user-attachments/assets/6212ca22-519c-44d9-a21a-3c0f91b6e3df)
## Text Field
Step selanjutnya kita menambahkan text field untuk tempat kita mengisi data

![Screenshot 2024-10-08 132801](https://github.com/user-attachments/assets/14bcf0d3-e1ed-42e5-811f-78780dc44acc)

## Button
selanjutnya kita tambahkan button dengan nama insert, update, dan delete untuk mengolah data

![Screenshot 2024-10-08 132822](https://github.com/user-attachments/assets/61c0a55b-a765-49f2-88b5-20df836769fe)

## table
selanjutnya kita menambahkan jtable untuk menampilkan data kita

![Screenshot 2024-10-08 132842](https://github.com/user-attachments/assets/991f527a-aa12-4c67-a3ae-8a5aa1dcfb22)

## Kodingan Insert
berikut untuk kodingan dalam button insert untuk menambahkan data kita dalam table dengan memanggil method insertDb

![Screenshot 2024-10-08 132905](https://github.com/user-attachments/assets/fade49e0-3b83-4e99-9c36-83ba13f019f1)

dan berikut isi kodingan dalam method insertDb

![Screenshot 2024-10-08 132926](https://github.com/user-attachments/assets/10b8c903-7d67-4578-b71c-714859ae88cd)

## kodingan Update
berikut untuk kodingan dalam button update untuk mengubah data kita dalam table dengan memanggil method updateDb
![Screenshot 2024-10-08 132944](https://github.com/user-attachments/assets/2b069140-edbc-47af-bd46-4ace6b82a1a3)

dan berikut isi kodingan dalam method updateDb

![Screenshot 2024-10-08 132944](https://github.com/user-attachments/assets/2b069140-edbc-47af-bd46-4ace6b82a1a3)

## Kodingan Delete
berikut untuk kodingan dalam button delete untuk menghapus data kita dalam table dengan memanggil method deleteDb

![Screenshot 2024-10-08 133003](https://github.com/user-attachments/assets/8954085a-0b7b-4b21-916b-3a8537acbb5c)

dan berikut isi kodingan dalam method deleteDb

![Screenshot 2024-10-08 133020](https://github.com/user-attachments/assets/624dde95-4684-4575-8d10-ecfffebe4de0)
## Menampilkan Data
selanjutnya kita membuat method show table untuk menampilkan data di dalam table dan dengan bantuan memanggil method selectDb

![Screenshot 2024-10-08 133035](https://github.com/user-attachments/assets/05ab3373-7980-4bfd-a33a-9022f297986d)
dan berikut isi kodingan dalam method selectDb

![Screenshot 2024-10-08 133100](https://github.com/user-attachments/assets/f88fc057-e086-458e-95e9-174af9b662cf)

## Hasil Tampilan
dan berikut hasil dari tampilannya

![Sebelum Insert](https://github.com/user-attachments/assets/4359a7cb-b857-41bb-9209-3844c655cd42)

## Praktek

## Tampilan Insert
kita akan mencoba memasukkan data dalam tabel

**sebelum**
![Sebelum Insert](https://github.com/user-attachments/assets/4359a7cb-b857-41bb-9209-3844c655cd42)
**sesudah**
![sesudah insert](https://github.com/user-attachments/assets/a30a35db-9461-486b-b571-02b2291bb19f)

## Tampilan Update
Kita akan mencoba mengubah data dalam table dari laskar pelangi menjadi jendral soedirman

**sebelum**
![sesudah insert](https://github.com/user-attachments/assets/a30a35db-9461-486b-b571-02b2291bb19f)
**sesudah**
![sesudah update dan sebelum delete](https://github.com/user-attachments/assets/c83c479f-82cb-45da-a39c-b945f3942351)

## Tampilan Delete
kita akan mencoba menghapus data yang ada dalam table

**sebelum**
![sesudah update dan sebelum delete](https://github.com/user-attachments/assets/c83c479f-82cb-45da-a39c-b945f3942351)
**sesudah**
![sesudah delete](https://github.com/user-attachments/assets/6f6d7444-130f-4ec7-8767-ddbdffdf69e8)

Semoga langkah-langkah yang saya berikan dan dapat dipahami sekian terimakasih
Semangat UTS kawan - kawan
