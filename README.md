
# Kelompok 3 Manajemen Basis Data A

Anggota :





- Adryan Putra Pratama ( 1207050004)
- Ammar Taradifa (1207050013)
- Arba Adhy Pamungkas (1207050016)




## Customer App

Merupakan Aplikasi CRUD customer sederhana menggunakan:

**Client:** Express JS 

**Server:** NodeJS, Docker Cassandra


## Cara Install

    1. Pertama clone atau download repository ini
    2. Buka terminal, lalu ketik npm install untuk mendownload module 

## Cara Running 

    1. Buka terminal dan docker
    2. Pertama Jalan kan : docker compose -f docker-compose.yml up -d
    3. Akses cassandra dengan : docker-compose exec cassandra bash 
    4. Masuk ke shell cassandra : cqlsh 


    1. Buka terminal baru untuk nodeJS nya
    2. Ketikan : npm start


    
## Screenshots

#### Tampilan Awal

![1](https://user-images.githubusercontent.com/49550093/209433512-8028f524-b8f8-4d52-8a0f-a31c0dbf1de8.png)

#### Inisialisasi Database

![2](https://user-images.githubusercontent.com/49550093/209433638-f9dbf003-6afd-4322-855e-60726485c745.png)


#### Data Tabel

![3](https://user-images.githubusercontent.com/49550093/209433677-3a33d4e6-37aa-45a7-b854-a07633f77168.png)


#### Tambah Data

![4](https://user-images.githubusercontent.com/49550093/209433711-9b161c79-2965-4d2d-a839-68d92868f408.png)


#### Hasil Tambah Data

![5](https://user-images.githubusercontent.com/49550093/209433797-598258d3-d271-42ca-bc93-250632129e63.png)

#### Edit Data

![6](https://user-images.githubusercontent.com/49550093/209433826-df7d6bec-1a06-4c2e-a168-f1df6e53857a.png)
