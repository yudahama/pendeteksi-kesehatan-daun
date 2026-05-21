# pendeteksi-kesehatan-daun
Nama Tim:

Marga Siregar

Anggota Tim:
1. Afgan Valent Abdino
2. Hafizh Ibnu Abbas
3. Muhammad Fakhri Khairi
4. Nugraha Selo
5. Yuda Yana

Kelas: XI RPL II

Deskripsi Produk

LeafVision adalah aplikasi pendeteksi kondisi daun tanaman menggunakan teknologi Artifical Intelegence (AI). sistem ini mampu mengedentifikaasi apakah daun termasuk sehat atau sakit hanya melalui gambar kamera atau upload foto.

aplikasi ini di buat untuk membantu petani.pelajar,maupun masyarakat umum dalam medeteksi penyakit tamanan lebih cepat sehingga penanganan dapat di lakukan sejak dini 

#USE CASE

permasalahan yang ingin diselesaikan:

sulit membedakan daun sehat dan daun sakit secara manual 

kurangnya pengetahuan masyarakat tentang ciri penyakit pada tanaman

proses pengecekan tanaman membutuhkan waktu dan tenaga.

Solusi:

pengguna cukup untuk mengapload gambar daun

sistem AI akan menganalisis gambar secara otomatis.

hasil klasifikasi ditampilkan sebagai daun sehat atau daun sakit 


#ARSITEKTUR MODEL
pada proyek ini kami menggunakan model AI YOLOV11n untuk melakukan deteksi objek pada gamaber daun 

Alasan memilih YOLOv11n

ringan cocok dijalakan di laptop biasa maupun perangkat edge 

cepat proses deteksi real time 

efisien tetap memiliki akurasi yang baik dengan ukuran model kecil.

mudah diintegrasikan medukung deployment ke streamlit maupun web app lainya 


#ALUR SISTEM
1. pengguna mengupload gambar daun.
2. sistem memproses gamnbar menggunakan model YOLOv11n.
3. model mendeteksi kondisi daun.
4. hasil klasifikasi ditampilkan kepada pengguna.

   

#AKSESIBILITAS
streamlit
github  


#CARA MENJALAKAN PROJECT 

bash 
pip install -r requirements.txt streamlit run app.py


#TEKNOLOGI YANG DIGUNAKAN 

YOLOv11n
streamlit
openCV
ultralytics YOLO 

#PENUTUP 

dengan adanya aplikasi leafvision diharapkan proses identifikasi kesehatan tanaman menjadi lebih cepat,dan mudah di gunakan oleh siapa saja  
