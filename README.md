# Unity LostBird

Ini adalah proyek sederhana yang dibuat menggunakan Unity untuk mengimplementasikan gameplay serupa dengan game populer "Flappy Bird". Proyek ini mencakup beberapa skrip untuk menangani parallax, objek pipa, kontrol pemain, spawn otomatis, dan manajemen game.

## 🎮 Fitur
- **Player Control:** Pemain dapat melompat dengan tombol `Space` atau klik mouse.
- **Parallax Effect:** Latar belakang bergerak untuk memberikan efek paralaks.
- **Obstacle Spawning:** Pipa dihasilkan secara otomatis dengan jarak yang bervariasi.
- **Game Manager:** Mengelola kondisi permainan seperti skor, game over, dan tombol play.
- **Score System:** Poin bertambah saat pemain melewati pipa.

## 📂 Struktur Skrip
### 1. **Parallax.cs**
Mengelola efek paralaks pada latar belakang.  
**Fitur Utama:**
- Menggerakkan tekstur latar belakang secara horizontal sesuai kecepatan animasi.

### 2. **Pipes.cs**
Mengelola perilaku pipa sebagai rintangan.  
**Fitur Utama:**
- Bergerak ke kiri dengan kecepatan konstan.
- Mengatur posisi pipa atas dan bawah dengan jarak tertentu.
- Menghapus pipa saat keluar dari layar.

### 3. **Player.cs**
Mengontrol karakter utama (burung).  
**Fitur Utama:**
- Melompat dengan kekuatan tertentu.
- Menerapkan gravitasi.
- Memutar burung berdasarkan arah gerakan.
- Mengelola animasi burung.
- Menangani tabrakan dengan rintangan atau zona skor.

### 4. **Spawner.cs**
Mengelola spawn otomatis untuk pipa.  
**Fitur Utama:**
- Menghasilkan pipa secara periodik dengan ketinggian acak.
- Mengatur jarak vertikal antar pipa.

### 5. **GameManager.cs**
Mengelola alur permainan.  
**Fitur Utama:**
- Memulai dan menghentikan permainan.
- Menampilkan skor.
- Mengelola kondisi `Game Over`.

## 🛠️ Cara Menggunakan
1. **Persiapan:**
   - Pastikan Anda memiliki Unity terinstal di komputer Anda.
   - Clone repository ini atau salin file proyek ke dalam direktori Unity Anda.

2. **Menambahkan Skrip ke Game:**
   - **Parallax.cs:** Tambahkan ke objek latar belakang dengan `MeshRenderer`.
   - **Pipes.cs:** Tambahkan ke prefab pipa.
   - **Player.cs:** Tambahkan ke karakter utama dengan komponen `SpriteRenderer`.
   - **Spawner.cs:** Tambahkan ke objek spawner untuk pipa.
   - **GameManager.cs:** Tambahkan ke objek yang mengelola elemen UI (seperti skor dan tombol).

3. **Jalankan Game:**
   - Tekan tombol `Play` di Unity Editor untuk memulai permainan.
   - Kontrol burung menggunakan tombol `Space` atau klik mouse.


## 📧 Kontak
[dimasajiprimadiansyah@gmail.com](mailto:dimasajiprimadiansyah@gmail.com).


