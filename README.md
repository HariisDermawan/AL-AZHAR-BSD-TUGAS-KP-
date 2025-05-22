# 🎓 Sistem Absensi Sekolah Menggunakan RFID Reader

Proyek ini merupakan bagian dari **Kerja Praktek** yang bertujuan membangun sistem **Absensi Sekolah otomatis menggunakan RFID Reader (RC522)**. Sistem ini memadukan teknologi **Arduino** dan **Laravel** untuk merekam kehadiran siswa secara real-time saat kartu RFID ditempelkan ke alat pembaca.

![RFID Absensi Demo](https://github.com/HariisDermawan/AL-AZHAR-BSD-TUGAS-KP-/blob/main/img/login.png)

---

## 📌 Tujuan Proyek

- Meningkatkan efisiensi absensi siswa di sekolah
- Mengurangi praktik titip absen
- Menyediakan rekap presensi secara digital

---

## 🚀 Fitur Sistem

- 📶 Pembacaan kartu RFID dengan Arduino Uno + RC522
- 💾 Penyimpanan data kehadiran ke database MySQL via Laravel
- 👨‍🏫 Halaman admin untuk kelola data siswa dan laporan
- 🔐 Login aman menggunakan Laravel Breeze
- 📈 Rekap absensi (Hadir, Izin, Sakit, Alfa)

---

## 🔧 Teknologi yang Digunakan

| Komponen         | Keterangan                            |
|------------------|----------------------------------------|
| Arduino Uno      | Mikrokontroler untuk membaca kartu     |
| RFID RC522       | Modul pembaca kartu RFID siswa         |
| Laravel 11       | Backend PHP dan manajemen data         |
| MySQL            | Penyimpanan database absensi           |
| Tailwind CSS     | Tampilan antarmuka frontend            |
| Serial Communication | Untuk mengirim UID ke Laravel     |

---

## 🔌 Rangkaian Arduino + RFID RC522

| RFID RC522 Pin | Arduino Uno Pin |
|----------------|------------------|
| SDA            | D10              |
| SCK            | D13              |
| MOSI           | D11              |
| MISO           | D12              |
| GND            | GND              |
| RST            | D9               |
| 3.3V           | 3.3V             |

---
