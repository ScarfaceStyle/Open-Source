# Open-Source
Repo
# 🛠️ Bash Utility Script

Kumpulan script Bash ringan yang dirancang untuk mempermudah pekerjaan administrasi sistem, automasi folder, dan task harian.

## 📌 Deskripsi
Proyek ini menyediakan script yang dapat digunakan untuk:
- Manajemen file & direktori
- Automasi proses repetitif
- Logging bawaan
- Mode interaktif dan non-interaktif

## 🚀 Instalasi

Clone repository:
git clone https://github.com/username/bash-utility.git
cd bash-utility

Izin eksekusi:
chmod +x tool.sh

## ▶️ Penggunaan

Menjalankan script utama:
./tool.sh

Menjalankan task tertentu:
./tool.sh backup

Mengaktifkan mode debug:
./tool.sh --debug

## 🧪 Contoh Output
>>> Starting utility...
>>> Task : backup
>>> Status: Completed (0.88s)

## ⚙️ Konfigurasi (Opsional)

Buat file konfigurasi:
config.ini

Contoh:
mode=production
destination=/home/user/backup
debug=false

## 📁 Struktur Proyek
bash-utility/
├── tool.sh
├── libs/
│   ├── file.sh
│   └── system.sh
└── config.ini.example

## 📜 Contoh Isi Script Utama
#!/bin/bash
echo ">>> Starting utility..."

if [[ "$1" == "--debug" ]]; then
  echo ">>> Debug mode ON"
fi

echo ">>> Done"

## 🧩 Pengembangan

Buat branch baru:
git checkout -b improvement

Commit:
git commit -m "chore: improve file system module"

Push:
git push origin improvement

## 📄 Lisensi
MIT License
