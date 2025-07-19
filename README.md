# SimonSayGame
# 🕹️ Simon Says Tangible Game – Unity x ESP32

🌟 *A tangible interaction project combining real hardware with interactive digital gameplay*

## 🧠 Tentang Proyek Ini

Proyek ini merupakan tugas besar yang saya kerjakan sebagai bagian dari kegiatan saya di **MetaLabs**, sebuah laboratorium riset dan eksplorasi teknologi di kampus saya. Di lab ini, saya memilih untuk fokus di divisi **Tangible Interaction**, yaitu bidang yang menggabungkan interaksi fisik (*hardware*) dengan media digital (*software/game*).

Sebagai bentuk penerapan, saya dan tim mengembangkan permainan klasik **Simon Says** namun dengan pendekatan **tangible**. Artinya, pemain diajak berinteraksi langsung dengan **tombol fisik** yang dikendalikan oleh **ESP32**, sementara visualisasi dan logika permainan dibangun menggunakan **Unity Engine**.

---

## 🔧 Teknologi & Tools

- 🧠 **Unity** (engine game & visualisasi)
- 💡 **ESP32** (microcontroller untuk kontrol hardware)
- 💬 **UART** (komunikasi serial real-time)
- 🖥️ **C#** (scripting game)
- 🔌 **ArduinoIDE** (coding ESP32)
- 🗃️ **Git & GitHub** (versi kontrol & portofolio)

---

## 🎯 Tujuan Proyek

- Menyatukan pengalaman interaktif antara dunia nyata & digital  
- Menerapkan pemahaman hardware-software dalam konteks game edukatif  
- Belajar kolaborasi antar perangkat & debugging lintas platform (hardware-software)

---

## 🎮 Fitur Permainan

- Urutan LED menyala secara acak yang harus diikuti pemain  
- Input dilakukan lewat **tombol fisik**, bukan UI digital  
- Tampilan **skor dan feedback visual** di layar Unity  
- **Komunikasi 2 arah** antara Unity & ESP32 secara real-time  
- Potensial untuk dikembangkan jadi **multiplayer game fisik**

---

## 📋 Kolaborasi Tim & Pembagian Tugas

Proyek ini dikerjakan secara kolaboratif oleh tim beranggotakan 3 orang:

- 👨‍🔧 **Irfan** – Bertanggung jawab di bagian **wiring**: menyusun sambungan kabel, LED, tombol, dan komponen lain di breadboard secara rapi dan fungsional.
- 👩‍💻 **Alya** (saya) – Fokus pada bagian **pemrograman mikrokontroler (Arduino/ESP32)**: menangani input tombol, output LED dan buzzer, serta komunikasi data ke Unity.
- 👩‍🎨 **Rinda** – Menangani **Unity & game logic**: merancang tampilan, mengatur alur permainan, serta menghubungkan komunikasi antara Unity dan ESP32.

> Kolaborasi dengan sistem kerja fleksibel secara online dan onsite, serta diskusi harian untuk menjaga progress.

---

## 💬 Catatan Pribadi

Project ini jadi salah satu pengalaman paling seru selama aku gabung di metaLab 🎉  
Awalnya, aku nggak nyangka bakal bisa ngoding game sambil ngoprek hardware beneran (biasanya cuma main game, sekarang malah bikin!).

Selama proses, aku belajar banget gimana caranya bikin **komunikasi antara dunia digital (Unity)** dan **dunia fisik (ESP32)** bisa jalan mulus. Tantangannya juga gak sedikit: dari buzzer yang gak bunyi-bunyi sampai tombol yang suka ngaco bacanya 😅 Tapi justru dari situ, aku makin paham gimana pentingnya debugging, trial-error, dan kerja tim.

Yang bikin aku makin bangga, kita bisa bawa konsep **tangible interaction** ke dalam bentuk yang playable, bukan cuma teori di kelas. Buat aku, ini bukan sekadar tugas lab tapi batu loncatan untuk eksplorasi ide-ide interaktif lainnya ke depan 🚀
