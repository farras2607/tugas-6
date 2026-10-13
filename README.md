VI. Tugas

Eksekusi seluruh profile yang ada :
a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut : echo “Profile dari /etc/profile”

1a<img width="498" height="186" alt="image" src="https://github.com/user-attachments/assets/591da46e-b520-44be-bcc7-8c35f9109723" />

b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :

1b<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/fd26b020-b5d7-468e-9e1e-484068299ba6" />

Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap file tersebut, cantumkan instruksi echo, misalnya pada /home/ mahasiswa/.bash_profile : echo “Profile dari .bash_profile” Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang bersangkutan.

c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut:

1c<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/35ec5cc4-9152-4011-b2ea-7a900a3d59ab" />

Prompt String (PS)
a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/b66b81e3-2ac3-406b-afab-d8cbd385f2fe" />

b. Eksperimen hasil PS1 :

3. Logout
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/13d0950e-239a-416f-92e7-f1b885d09c67" />

3 tugas 6
Bash script a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing : p1.sh #! /bin/bash
4 a 1
p2.sh #! /bin/bash

4 a 2
p3.sh #! /bin/bash

4 a 3
b. Jalankan script tersebut sebagai berikut : 4b1

4b2 42b3 4b4
Jobs a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.
5 tugas 6
b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di background sebagai berikut :

5b
c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background

5c
d. Stop program background dengan utilitas kill

5d
History a. Ganti nilai HISTSIZE dari 1000 menjadi 20
6a1
b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang terakhir dilakukan

6b
c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer

6c
d. Ulangi instruksi pada history bufer nomor 150

6d
e. Ulangi instruksi dengan prefix “ls”

6e
