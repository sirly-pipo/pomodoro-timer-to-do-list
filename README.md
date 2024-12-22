# pomodoro-timer-to-do-list
# Website Pendukung Belajar

Website ini merupakan aplikasi berbasis web yang terdiri dari dua fitur utama, yaitu Pomodoro Timer, To-Do List dan motivasi singkat, yang bertujuan untuk membantu pengguna dalam mengelola waktu belajar dan tugas.

## Fitur Utama

1. Pomodoro Timer:
   - Mengatur waktu belajar dan waktu istirahat dengan menggunakan teknik Pomodoro.
   - Menyediakan opsi untuk mengatur durasi waktu belajar dan istirahat.
   - Menampilkan waktu yang tersisa dalam format MM:SS.
   - Memberikan suara alarm ketika waktu selesai.
   - Memulai timer secara otomatis setelah satu sesi selesai (berpindah antara belajar dan istirahat).

2. To-Do List:
   - Menambahkan dan menghapus tugas yang perlu dilakukan.
   - Menandai tugas sebagai selesai dengan mengklik tugas.
   - Menyimpan data tugas secara lokal di browser menggunakan `localStorage`, sehingga tugas yang telah ditambahkan tetap ada meskipun halaman di-refresh.

3. Motivasi
   - Menampilkan motivasi acak setiap kali timer dihentikan, untuk menjaga semangat belajar.
  
## Struktur File

- `index.html`: Halaman utama dari website yang berisi fitur Pomodoro Timer dan To-Do List.
- `belajar.css`: File CSS untuk styling halaman 
- `alarm.mpeg`: Suara alarm yang diputar saat timer selesai.

## Penggunaan

1. Pomodoro Timer:
   - Tentukan waktu belajar dan waktu istirahat di input yang tersedia.
   - Klik "Mulai Timer" untuk memulai sesi belajar atau istirahat.
   - Klik "Stop Timer" untuk menghentikan timer.

2. To-Do List:
   - Masukkan tugas yang ingin ditambahkan di input "Tambah tugas baru".
   - Klik "Tambah" untuk menambahkan tugas ke daftar.
   - Klik tugas untuk menandainya sebagai selesai.
   - Klik tombol "Hapus" di samping tugas untuk menghapusnya dari daftar.


