# 🤖 Portofolio Proyek AI: Kontrol Game dengan Face Detection
Oleh: **KKSBYB** | Kelas: **Master**

Proyek ini memanfaatkan teknologi **Artificial Intelligence (AI) & Computer Vision** menggunakan **PictoBlox**. Program ini mendeteksi pergerakan wajah pengguna secara *real-time* melalui webcam untuk mengendalikan karakter di dalam game tanpa keyboard atau mouse.

---

## 🔗 Tautan Penting Proyek
*   🌐 **Mainkan di Web:** [Buka Proyek via PictoBlox Cloud](https://pictoblox.ai/p/LUYbEHAdBibGrQeLdN4T) *(Ganti dengan link share dari aplikasi PictoBlox jika ada)*
*   💾 **Unduh File Asli:** [Klik untuk Download File .sb3](https://github.com/KKSBY/testPorto/raw/main/Facedetection-karsten.sb3)

---

## 📺 Tonton Video Demo Proyek
Karena proyek ini berbasis AI dan membutuhkan akses kamera, Anda bisa melihat bagaimana sistem *Face Detection* ini merespons gerakan wajah secara langsung melalui video demo berikut:

[![Tonton Video Demo](https://youtube.com)](https://youtu.be/EeIZk9ztox4)
*Klik gambar di atas atau [Klik Link Ini](https://youtu.be/EeIZk9ztox4) untuk menonton di YouTube.*



---

## 📝 Deskripsi & Fitur AI
Program ini mengaktifkan kamera laptop dan menganalisis koordinat wajah pengguna. Pergerakan wajah ke kanan, kiri, atas, atau bawah akan langsung dibaca sebagai perintah input untuk menggerakkan objek di layar.

### Fitur Utama:
*   **Real-time Face Tracking:** Menggunakan ekstensi AI PictoBlox untuk melacak posisi wajah tanpa delay.
*   **Hands-free Control:** Pengalaman interaktif baru di mana pengguna mengontrol game murni menggunakan gerakan kepala.

### Blok Kode Utama yang Digunakan:
1.  **Ekstensi Face Detection:** Memanggil fungsi library AI lewat blok `turn on video`.
2.  **Tracking Koordinat:** Mengambil data sumbu X dan Y wajah menggunakan blok `get [x/y position] of face`.
3.  **Looping Terus-Menerus:** Menggunakan blok `forever` agar AI selalu mendeteksi wajah selama program aktif.

---

## 🛠️ Cara Menjalankan Proyek Secara Manual
Jika Anda ingin melihat susunan blok kode AI atau mencoba program ini di komputer Anda:
1.  Unduh file `.sb3` melalui tombol **Unduh File Asli** di atas.
2.  Jalankan aplikasi **PictoBlox** di laptop Anda.
3.  Pilih menu **File** > **Load from your computer**, lalu pilih file `.sb3` yang sudah diunduh.
4.  Pastikan webcam laptop aktif, lalu klik ikon **Bendera Hijau** untuk memulai.
