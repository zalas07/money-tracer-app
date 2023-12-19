# money-tracer-app
## Overview
> dikutip dari Dicoding Academy Platform

*Money Tracer App** merupakan salaha satu project dari platform Dicoding academy yang mengharuskan setiap peserta dalam menyelesaikan project tersebut menggunakan bantuan *Google Cloud Platform*. project ini memiliki skenario yang dimana suatu perusahaan mengharuskan seorang cloud engineer untuk memigrasikan system aplikasi ke Google cloud. dimana aplikasi tersebut, terdiri dari 2 spesifikasi yaitu:
- **Frontend Web** yang di tulis menggunakan bahasa pemrograman *PHP* dengan framework *Codelgniter* versi **3.1.10**
- **Backend API** di tulis menggunakan *NodeJs*
fitur utama dari aplikasi ini, adalah mencatat pemasukan dan pengeluaran Pengguna juga bisa mengunggah gambar berisi lampiran untuk setiap pencatatan, contohnya seperti struk belanja, slip gaji, dll. Gambar tersebut disimpan di object storage dan URL-nya akan disimpan di database. Bentuk data yang disimpan telah ditentukan sehingga memiliki skema yang konsisten.

Money Tracker App ini digarap oleh tim yang beranggotakan banyak pihak, mulai dari Manajer Proyek, Developer, Cloud Architect, hingga Cloud Engineer (dalam kasus ini adalah Anda). Beruntungnya, source code dan rancangan arsitektur cloud dari Money Tracker App sudah selesai digarap dan siap untuk Anda eksekusi. 
dan untuk arsitektur yang di rancang di perlihatkan pada gambar di bawah ini:
![Google Cloud Architecture](https://github.com/zalas07/money-tracer-app/blob/main/arsitektur%20google.jpeg)

## Kriteria

1. Membuat Project baru
  Untuk memisahkan environment pada Google Cloud, juga memudahkan proses review, buatlah project baru dengan project ID dan project name sesuai ketentuan format   submission-mgce-namapeserta.
2. Memberikan hak akses ke *Reviewer*
   Usai membuat project baru, tugas kita perlu memberikan hak akses yang sesuai kepada Tim Reviewer  agar tim bisa memeriksa hasil kerja secara mendetail.
3. Mendeploy Money Tracert App
   Setelah memahami semua resource yang di berikan, selanjutnya kita perlu men-deploy Money Tracker App ke lingkungan Google Cloud menggunaka source code (Front-End dan Back-End) tersebut dan kita perlu memastikan implementasinya sesuai dengan rancangan arsitektur cloud yang di berikan.


## Dokumentasi penngerjaan Proyek Money Tracert

1. setting up *App Engine Enviroment* di Google Cloud
  ![Setting up App Engine](https://github.com/zalas07/money-tracer-app/blob/main/app%20engine.png)
2. membuat database untuk penyimpanan relational data dari aplikasi yang sudah di deploy sebelumnya
   ![setting up database *MYSQL*](https://github.com/zalas07/money-tracer-app/blob/main/cloud%20SQL1.png)
3. menyiapkan storage bucket untuk keperluan penyimpanan *unsctructure file* dari aplikasi yang di deploy
   ![Setting up Cloud Storage Bucket](https://github.com/zalas07/money-tracer-app/blob/main/storage%20bucket2.png)
4. Update *lifecyle management* dari cloud storage
   ![lifecycle management cloud storage](https://github.com/zalas07/money-tracer-app/blob/main/lifecycle%20management.png)
 
   



