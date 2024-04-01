# Laporan Resmi Modul 1 Jaringan Komputer

Lapres Modul 1 Jaringan Komputer - **IT-03**

## Authors

| Nama                                                | NRP        |
| --------------------------------------------------- | ---------- |
| [Sighra Attariq Sumere Jati](https://www.github.com/sgraa) | 5027221068 |
| [Wilson Matthew Thendry](https://www.github.com/waifuwetdream) | 5027221024 |

## Hasil Pengerjaan

### ATM or ATP or FTP ? 🤔
Untuk mendapatkan flag dari soal ini, kami diminta untuk menjawab password yang didapatkan hacker setelah bruteforce login ftp. Kami memanfaatkan filter `ftp` dan juga `TCP` dan kami mencari dimana terdapat respon login yang berhasil. Setelah menemukan paket yang dicari, kami mengikuti hingga stream 319 dan memperoleh *PASS m4y_th3_Kn!fe_ch1p_&_sh4tter*. Maka, password yang diperoleh hacker tersebut adalah **m4y_th3_Kn!fe_ch1p_&_sh4tter**\

![m4y_th3_Kn!fe_ch1p_&_sh4tter](images/ftp_proof.png)
![terminal_m4y_th3_Kn!fe_ch1p_&_sh4tter](images/ftp_proof2.png)

