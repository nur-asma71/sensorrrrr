# SENSOR QUEST — Website Pembelajaran Interaktif WSN

## Menjalankan di VS Code
1. Ekstrak ZIP ini.
2. Buka folder `sensor_quest_vscode` di VS Code.
3. Pasang ekstensi **Live Server** jika belum ada.
4. Klik kanan `index.html` → **Open with Live Server** atau tekan **Go Live**.

## Isi website
- 14 layar utama: splash, login demo, dashboard, peta misi, pengantar WSN, Sensor Node, Sink/Base Station, Gateway, komunikasi nirkabel, evaluasi, feedback benar, feedback salah, hasil akhir/badge, profil, dan prestasi.
- Navigasi antarlayar, layout responsif, diagram alur WSN, dan narasi text-to-speech jika browser mendukung.
- Evaluasi 5 soal pilihan ganda dengan pemeriksaan jawaban, poin, nyawa, progres, dan badge.
- Profil demo, edit nama, pengaturan toggle, serta penyimpanan lokal browser.

## Catatan
Ini adalah prototipe frontend, bukan sistem login berbasis server. Data disimpan di `localStorage` browser. Halaman pengantar WSN dan Sensor Node ditambahkan sebagai pelengkap karena halaman sumber yang tersedia melompat dari halaman 4 ke halaman 7.
