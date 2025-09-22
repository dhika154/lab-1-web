#  1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
JAWABAN:
<img width="1920" height="1080" alt="Screenshot 2025-09-22 200636" src="https://github.com/user-attachments/assets/9305a31b-2bf9-4e1f-991a-f307eb16f1e8" />
Penjelasan : sudah di lakukan dan kode tidak error

# 2. Apa perbedaan dari tag (p) dengan tag (br), berikan penjelasannya!
JAWABAN:
# TAG (P)
<img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/c2daaead-eaa8-442d-a629-b9bc36ddfc75" />

PENJELASAN: Pengertian Tag (p)(p) adalah singkatan dari paragraph (paragraf).
Digunakan untuk menampilkan teks dalam bentuk paragraf pada halaman web.
Setiap kali kita membuat (p)...(/p), browser otomatis akan memberikan jarak (spasi) sebelum dan sesudah paragraf agar teks lebih rapi terbaca.

# TAG (BR)
<img width="1920" height="1080" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/48ffe97a-430d-418b-8ca1-de478bcafeb4" />

PENJELASAN: 
Pengertian Tag (br)(br) adalah singkatan dari break (line break).
Digunakan untuk memecah baris atau pindah ke baris baru tanpa harus membuat paragraf baru seperti (p).
Tag ini tidak memiliki penutup (self-closing tag).

# 3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!

JAWABAN:
<img width="1920" height="1080" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/42d6d4f8-fb55-42a8-9b6f-9fc18588c158" />

PENJELASAN: alt → Tampil kalau gambar gagal dimuat + dibaca screen reader (aksesibilitas).
title → Tooltip yang muncul ketika kursor diarahkan ke gambar (informasi tambahan).
Jadi, gambar logo kampus yang saya tambahkan muncul normal, Kalau misalnya file gambar diganti dengan nama yang salah, maka teks alt akan muncul menggantikan gambar

# 4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

 JAWABAN:
 
<img width="1920" height="1080" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/814409f2-663e-464f-bc26-2c3264f43124" />

PENJELASAN: Penjelasan: Sebaiknya hanya salah satu (width atau height) yang diisi.
→ Kalau kedua-duanya diisi tapi ukurannya tidak sesuai dengan rasio asli gambar, maka gambar akan terdistorsi (melebar atau memanjang tidak proporsional).
→ Jika hanya isi width saja, maka tinggi (height) akan menyesuaikan otomatis (proporsional), begitu juga sebaliknya.

# 5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
 JAWABAN:
 KODE:
 <img width="675" height="117" alt="Screenshot 2025-09-22 211344" src="https://github.com/user-attachments/assets/35e90a4c-711c-43b7-ac8e-4f270abddf97" />

 HASIL:

<img width="1920" height="1080" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/425c228a-e2bd-4a27-9913-2326644191d9" />

PENJELASAN: Atribut target digunakan untuk menentukan di mana link akan dibuka ketika diklik.

1. _self

Default (kalau target tidak ditulis, maka dianggap _self).
Membuka link di halaman/tab yang sama.
Cocok kalau kamu ingin mengganti halaman yang sedang dibuka.

2. _blank
Membuka link di tab baru atau jendela baru.
Berguna kalau ingin pengunjung tetap berada di halaman webmu, tapi bisa melihat link eksternal di tab lain.

3. _parent

Digunakan saat halaman berada di dalam frame/iframe.
Link akan terbuka di frame induk (parent frame).
Kalau tidak ada iframe, maka hasilnya sama dengan _self.

4. _top

Digunakan juga pada halaman yang ada di dalam frame/iframe.
Membuka link di jendela penuh (top-level window), artinya keluar dari semua frame.
Kalau tidak ada iframe, hasilnya sama dengan _self.


Kesimpulan Singkat

_self → buka link di halaman/tab yang sama (default).
_blank → buka link di tab/jendela baru.
_parent → buka link di frame induk (kalau ada iframe).
_top → buka link di jendela penuh, keluar dari semua frame (kalau ada iframe).
