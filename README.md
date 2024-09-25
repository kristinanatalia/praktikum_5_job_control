Laporan Praktikum SISTEM OPERASI Job control
Nama : Kristina Natalia Hutauruk
NIM: 09011282328120
Kelas: SK3C

1. Eksekusi seluruh profile yang ada :
a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut :
echo "Profile dari /etc/profile"

b. Asumsi nama anda stD02001, maka edit semua profile yang ada
Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap
file tersebut, cantumkan instruksi echo, misalnya pada /home/ mahasiswa/.bash_profile :
echo "Profile dari .bash_profile"

![Picture 1](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%201.png)
![Picture 1.1](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%201.1.png)

c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut:
Jelaskan perbedaan kedua utilitas :
**su mahasiswa**: Perintah ini hanya mengganti identitas pengguna menjadi mahasiswa, tetapi tidak memuat lingkungan (environment) pengguna tersebut.
**su - mahasiswa**: Perintah ini tidak hanya mengganti identitas pengguna menjadi mahasiswa, tetapi juga memuat lingkungan pengguna mahasiswa secara penuh.

![Picture 1.2](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%201.2.png)
 
2. Prompt String (PS)
![Picture 2](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%202.png)

3. Logout
Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout
Echo "Terima kasih atas sesi yang diberikan"
Sleep 5
Clear
![Picture 3](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%203.png)
 
4. Bash script
a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing :
![Picture 4.1](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%204.1.png)
![Picture 4.2](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%204.2.png)
![Picture 4.3](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%204.3.png)
![Picture 4.4](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%204.4.png)

b. Jalankan script
![Picture 4.5](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%204.5.png)
![Picture 4.6](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%204.6.png)

5. Jobs
a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh,
setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.
b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di background
c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke
background
d. Stop program background dengan utilitas kill
![Picture 5](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%205.png)

6. History
![Picture 6](https://github.com/kristinanatalia/praktikum_5_job_control/blob/main/picture%206.png)

