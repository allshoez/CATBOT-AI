CatBot AI 🐱🤖

CatBot AI New Custom 2025 chatbot web yang interaktif dan fleksibel, bisa dijalankan offline/lokal maupun online via 2 API. 
* gemini
* OpenAi

Didesain untuk pengguna yang ingin chatbot pintar dengan dua mode operasi dan dua API key untuk integrasi AI eksternal. terdapapat fitur copy paste setiap percapakan


---

🎯 Fitur Utama

Dua Mode Chat

Mode A: Jawaban diambil dari rules.json (offline)

Mode B: Jawaban diambil/simpan di data.json, bisa request jawaban baru jika belum ada


Menu Popup Interaktif

Atur API key, reset data, pilih mode, atau setting lainnya


Dukungan Multimedia

Embed gambar dan video langsung di chat


Dua API Key gemini & Open Ai

Bisa mengatur dua API key berbeda untuk panggilan AI eksternal


Responsif & Mobile-Friendly

Bisa dibuka di HP, tablet, maupun desktop




---

🗂 Struktur Folder

catbot/
│
├─ index.html        # Halaman utama ChatBot
├─ script.js         # Logic interaktif
├─ style.css         # Styling UI
├─ rules.json        # Rules default Mode A
├─ data.json         # Data dinamis Mode B
└─ assets/           # Gambar/video tambahan


---

⚡ Instalasi

1️⃣ Versi Browser (Lokal)

1. Clone repo:

git clone https://github.com/username/catbot-ai.git


2. Buka index.html di browser


3. Gunakan popup menu ⚙️ untuk memasukkan API key atau pilih mode


4. Mulai chat dengan CatBot



2️⃣ Versi Termux

1. Pastikan python atau nodejs sudah terinstall


2. Jalankan server lokal:

cd catbot
python -m http.server 8080


3. Buka browser Termux: http://localhost:8080/




---

💬 Contoh Penggunaan

Menu Popup



Input API key 1 & 2

Pilih mode A/B

Reset data Mode B


Contoh Chat

Mode A (offline)

User: Halo CatBot!
CatBot: Halo! Apa kabar hari ini?

Mode B (API)

User: Buatkan puisi tentang kucing
CatBot: Di bawah sinar bulan, si kucing menari...

Media Embed

Bisa menampilkan gambar/video langsung di chat



---

🛠 Kontribusi

1. Fork project ini


2. Buat branch baru untuk fitur tambahan


3. Pull request untuk bergabung ke repo utama




---

📜 Lisensi

MIT License © 2025


---
