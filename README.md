# 🌞 Smart Solar Street Light (Remote Monitor)
# 📖 Deskripsi Proyek
Smart Solar Street Light adalah sistem lampu jalan pintar berbasis energi surya yang dapat dipantau secara jarak jauh melalui platform cloud. Sistem ini bertujuan untuk menghemat energi dengan mengontrol nyala/mati lampu secara otomatis berdasarkan kondisi lingkungan dan aktivitas manusia. Tujuan Proyek ini juga guna memenuhi **Tugas Besar Mata Kuliah Mikrokontroler dan IoT**.

## 🎯 Sistem ini dirancang untuk:

- Menghemat energi dengan mengontrol lampu jalan secara otomatis.

- Memantau status lampu secara real-time melalui platform cloud.

# 🌍 Kontribusi terhadap SDGs
✅ SDG 7 - Clean Energy
Dengan memanfaatkan energi matahari, sistem ini berkontribusi dalam transisi menuju energi terbarukan dan efisiensi energi. 

# 🚀 Fitur Utama
* Otomatisasi pengendalian lampu jalan tenaga surya.

* Pemantauan status lampu secara real-time melalui koneksi cloud.

* Ramah lingkungan dan efisien dalam penggunaan energi.

# 🧰 Teknologi yang Digunakan
## 📦 Komponen Perangkat Keras

| No. | Komponen                | Fungsi                                                                 |
|-----|-------------------------|------------------------------------------------------------------------|
| 1   | ESP32                   | Mikrokontroler utama untuk kontrol sistem dan koneksi ke cloud         |
| 2   | Solar Panel             | Menghasilkan energi dari sinar matahari                                |
| 3   | Solar Charge Controller | Mengatur pengisian daya ke baterai dari panel surya                    |
| 4   | Baterai                 | Menyimpan energi untuk digunakan saat malam                            |
| 5   | Relay Switch            | Mengendalikan nyala/mati lampu LED secara elektronik                   |
| 6   | Lampu LED               | Sumber penerangan yang hemat energi                                    |
| 7   | LCD/OLED Display        | Menampilkan informasi seperti waktu, suhu, dan status sistem           |
| 8   | Kamera                  | (Opsional) Digunakan untuk pemantauan visual atau keamanan             |

## 📡 Sensor dan Modul Pendukung

| No. | Sensor/Modul        | Fungsi                                                                 |
|-----|---------------------|------------------------------------------------------------------------|
| 1   | LDR                 | Mendeteksi tingkat pencahayaan lingkungan                              |
| 2   | PIR Sensor          | Mendeteksi pergerakan manusia untuk mengaktifkan lampu                 |
| 3   | DHT11 / DHT22       | Mengukur suhu dan kelembapan udara                                     |
| 4   | RTC Module          | Menyediakan waktu dan tanggal yang akurat                              |
| 5   | Cloud (Firebase / Blynk) | Platform monitoring dan kontrol jarak jauh                       |

## 📌 Cara Kerja Sistem

1. **Energi Matahari** mengisi baterai melalui **solar panel** dan **solar charge controller**.
2. **LDR** mendeteksi terang/gelap untuk menentukan waktu siang/malam.
3. **PIR sensor** mendeteksi keberadaan manusia.
4. **RTC module** memastikan waktu aktual sebagai cadangan logika waktu.
5. **DHT11/DHT22** mencatat suhu dan kelembapan lingkungan.
6. **ESP32** sebagai otak sistem mengolah data dari sensor dan mengirim ke **Cloud**.
7. **Relay Switch** mengontrol nyala/mati **lampu LED**.
8. **LCD/OLED display** menampilkan informasi lokal.
9. **Kamera (opsional)** untuk pengawasan area lampu.
    
# 🧩 Diagram Blok Sistem
![Diagram Blok Sistem](Diagram-Blok-Sistem.png)

# 💥Desain Sistem UI/UX
## 📱 Software

## 💽 Hardware

# 📸 Demo / Ilustrasi
(Sisipkan diagram, foto prototipe, atau link video demo)

# 🫂 Kelompok 2
1. **105221004 | Helmi Apriando**
2. **105221027 | Mohamad Reza Pahlevi**

[LinkedIn/GitHub/Website jika ada]
