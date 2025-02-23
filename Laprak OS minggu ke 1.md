**1. Langkah-Langkah instalasi:**

Langkah awal dalam menginstall OS Linux adalah menyiapkan iso imagenya, kemudian siapkan VB, bisa menggunakan VirtualBox, VMWare Player, dsb. Disini saya akan menggunakan VirtualBox
Langkah-langkah:

1. Buka VirtualBox

2. Klik 'New'

3. Masukkan nama dari projectnya, lalu tentukan di mana virtual os akan disimpan, kemudian pilih iso image mana yang telah didownload

4. Centang 'Unattended Installation,' Klik 'Next'

5. Atur ukuran dari memory dan jumlah CPU yang akan digunakan (4096mb/2)

6. Atur ukuran dari penyimpanan yang akan digunakan (25GB)

7. Pada bagian 'Summary,' terdapat informasi spesifikasi yang telah ditentukan. Pastikan semua benar.

8. Klik 'Finish'

9. Pilih OS yang baru saja dibuat atau yang akan digunakan. Klik 'Start'

10. Lakukan penginstallan sesuai standar distro Linux masing-masing.

**2. Perbandingan Debian 11 dan Debian 12:**

| ASPEK                | DEBIAN 11 (BULLSEYE) | DEBIAN 12 (BOOKWORM)  |
|----------------------|----------------------|-----------------------|
| Versi kernel         | Linux 5.10           | Linux 6.1             |
| Kebutuhan sistem     | Minimal menggunakan RAM 256 mb dan menyediakan Storage minimal 5 GB   | Minimal menggunakan RAM 512 mb dan menyediakan Storage minimal 10 GB |
| Penerapan systemd    | Menggunakan systemd v247     | Menggunakan systemd v252 dengan beberapa peningkatan fitur didalamnya |
| Perbedaan Package    | GNOME 3.38, OpenSSL 1.1, GCC 10, Mesa 20.3, Systemd 247, Python 3.9 | GNOME 43, OpenSSL 3.0, GCC 12, Mesa 22.3, Systemd 252, Python 3.11 |

**3. Cek Environment menggunakan CPU-X:**

1. Buka terminal yang ada di linux kemudian ketikan perintah ``` sudo apt install cpu-x ```
2. Setelah terinstall buka cpu-x nya
3. Setelah terbuka akan muncul informasi tentang spesifikasi yang digunakan

**4. Cara lain:**

- Untuk storage: 
```bash
df -h
```
- Cek RAM:
```bash
free -h
```
- Cek network interface:
```bash
ip a
```
- Cek GPU:
```bash
lspci | grep
```
- Cek aplikasi dengan snap atau flatpak:
    - Snap list: 
    ```bash
    snap list
    ```
    - Flatpak list:
    ```bash
    flatpak list
    ```
