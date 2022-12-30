# Administrasi Sistem ( Instalasi DNS Server )
## Aryo Ridho Suryanggi
## Made Apiawan Anarky
## Muhammad Harun Al Rasyid

### pertama kita buka virtual box kemudian masukan username dan password debian kita agar bisa masuk ke root
![2](https://user-images.githubusercontent.com/74999852/203224753-f3f9b558-104d-4b07-a078-b280e1353d21.jpg)
### kemudian ketikan perintah seperti gambar di bawah ini
![3](https://user-images.githubusercontent.com/74999852/203224811-21beb2ce-6a4b-42a2-857d-4fff642d836f.jpg)
### masukan ip, subnetmask dan gateway nya
![4](https://user-images.githubusercontent.com/74999852/203224873-8ff018ad-5aaf-45e8-9915-24d981a2d31e.jpg)
### kemudian kita menginstal bind9 dengan menggunakan perintah seperti dibawah ini
![5](https://user-images.githubusercontent.com/74999852/203225025-523b9614-b628-44e9-8556-76cdb288c9ce.jpg)
### jika sudah ketikan perintah seperti gambar di bawah ini
![6](https://user-images.githubusercontent.com/74999852/203225082-f7becf97-b990-46f7-b02a-b97e90b6a707.jpg)
### kemudian kita ketikan ls untuk melihat folder nya
![7](https://user-images.githubusercontent.com/74999852/203225182-db7560e2-5f27-4462-8fbc-90b66bb800c8.jpg)
### ketikan perintah seperti dibawah ini
![8](https://user-images.githubusercontent.com/74999852/203225242-0301cdd8-35c6-431f-b6ed-c9a22f88076d.jpg)
### isi seperti gambar di bawah ini
![9 isi seperti contoh di atas](https://user-images.githubusercontent.com/74999852/203225332-b7999ce1-a8ee-4971-a2ef-46f1584c896e.jpg)
### jika sudah ketikan lagi perintah seperti dibawah ini
![10](https://user-images.githubusercontent.com/74999852/203225399-822c97f9-b982-4a2b-83cc-3225b14a76cd.jpg)
### ubah local host menjadi link yang sudah kita buat sebelum nya
![11 ubah localhost menjadi link yg telah kita buat sebelumnya](https://user-images.githubusercontent.com/74999852/203225500-5b5a2f73-8c88-430f-ad92-647206a0ecc7.jpg)
### jika sudah tinggal kita cocokan ip seperti gambar di bawah ini
![12 jika sudah di ubah tinggal cocokan ip kalian saja seperti pada gambar](https://user-images.githubusercontent.com/74999852/203225604-412a9f52-6f40-48e9-8621-dcd326d3e906.jpg)
### kemudian ketikan perintah seperti gambar di bawah ini
![13](https://user-images.githubusercontent.com/74999852/203225689-573d56ae-117f-4d82-a2ab-82f3db336429.jpg)
### setelah itu kita cocokan lagi ip nya sama seperti sebelum nya
![14 sama seperti tdi localhostnya kita ganti](https://user-images.githubusercontent.com/74999852/203225744-3124047e-6bea-4307-8336-0b9d0f3f91f5.jpg)
### kita ketikan cd
![15](https://user-images.githubusercontent.com/74999852/203225777-df2d9679-9aab-4c2b-9412-188c018331b1.jpg)
### kemudian ls
![16](https://user-images.githubusercontent.com/74999852/203225818-79c685e2-31d0-43fd-b826-14c907c11fd0.jpg)
### dan ketikan lagi perintah seperti gambar dibawah ini
![17](https://user-images.githubusercontent.com/74999852/203225879-e991835d-b742-4d0c-9fc0-84212377d821.jpg)
### masukan ip dan link yang sudah kita buat tadi
![18 isi seperti gambar](https://user-images.githubusercontent.com/74999852/203225965-a73caa4f-fcf0-4bde-82a1-e073bfa6b378.jpg)
### kemudian ketikan perintah di bawah ini untuk ke restart
![19](https://user-images.githubusercontent.com/74999852/203226061-66f3618a-359e-4f8d-8eaa-f886a5abe770.jpg)
### ketikan perintah seperti gambar di bawah ini jika hasil nya seperti ini maka DNS server kita sudah berhasil
![20 ketikan perintah yg telah di garis bawahi jika hasilnya sama seperti digambar artinya DNS server kita sudah berhasil](https://user-images.githubusercontent.com/74999852/203226224-f4041512-11da-4e80-a950-9e5225749604.jpg)
### setelah itu kita konfigurasi ke windows dengan mengetikan control panel-network and internet
![21 kemudian kita cinfigurasikan ke windows kita pertama buka control panel pilih (network and internet)](https://user-images.githubusercontent.com/74999852/203226440-9ca5fe26-6cf2-4b79-aae4-871bcb75763b.jpg)
### pilih network and sharing center
![22](https://user-images.githubusercontent.com/74999852/203226504-451d8d1c-f6a1-47a8-af1c-a52a221fc2d4.jpg)
### pilih change adapter settings
![23](https://user-images.githubusercontent.com/74999852/203226568-344ada73-7b0b-4ff8-bf98-7ccba4e11be8.jpg)
### pilih virtual host only network
![24](https://user-images.githubusercontent.com/74999852/203226628-9f30a58f-f18f-4e94-8610-760b3c37e393.jpg)
### klik properties
![25](https://user-images.githubusercontent.com/74999852/203226686-ff4f2b44-896f-40b0-a0a1-9b1be16d5bd6.jpg)
### pilih yang internet protokol version 4
![26](https://user-images.githubusercontent.com/74999852/203226770-0449fec7-cf50-49be-ad97-991301b5d489.jpg)
### isi seperti gambar di bawah ini menggunakan ip yang sudah kita buat di debian
![27 isi bagian dilingkari seperti di gambar dengan ip debian dan ip google com](https://user-images.githubusercontent.com/74999852/203226866-08c8c8c8-f519-47c3-8fbd-f070fb7f7412.jpg)
### setelah itu buka cmd di windows kemudian ping ip yang sudah kita bikin di debian dan ketikan nama web nya juga jika hasil nya seperti gambar di bawah ini maka DNS sudah sukses
![28 setelah itu kita coba ping melalui cmd di window, jika hasilnya sama seperti di gambar maka telah selesai pembuatan DNS server ini](https://user-images.githubusercontent.com/74999852/203227063-8f43771f-005b-4df1-8107-dfd43285f928.jpg)
