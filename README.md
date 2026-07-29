# tugas-wek4-day3
tugas peraktek
## Pertanyaan Refleksi

1. **Kenapa font-size di hero section kamu buat berbeda satuannya dibanding bagian lain?**
   * **Jawab:** Karena *hero section* dirancang untuk menjadi elemen visual utama yang langsung memenuhi layar pengguna saat pertama kali dibuka. Dengan menggunakan satuan `vw` (viewport width), ukuran font pada judul utama dapat berubah secara dinamis dan otomatis mengikuti lebar layar browser tanpa perlu menulis banyak *media queries*. Sebaliknya, bagian artikel di bawahnya menggunakan satuan `rem` agar ukuran teksnya tetap stabil, konsisten dengan pengaturan root, serta nyaman dibaca di berbagai perangkat.

2. **Apa yang akan terjadi pada tampilan kutipan jika satuan em pada padding-nya diganti menjadi px? Jelaskan secara singkat.**
   * **Jawab:** Jika satuan `em` diganti menjadi `px`, padding pada kutipan akan menjadi statis (kaku). Padding tidak akan ikut membesar atau mengecil jika kita mengubah ukuran font (`font-size`) dari komponen kutipan tersebut. Penggunaan `em` memastikan proporsi ruang kosong (padding) di dalam kutipan tetap seimbang dan serasi secara otomatis dengan ukuran teksnya sendiri.
