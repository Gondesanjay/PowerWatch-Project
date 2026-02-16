# Power Watch ⚡

**Power Watch** adalah aplikasi monitoring listrik berbasis web yang dirancang untuk membantu pengguna memantau pemakaian listrik secara *real-time*, mengestimasi biaya bulanan, dan memberikan saran penghematan energi.

Proyek ini dibuat sebagai Tugas Akhir Dasar-Dasar Pemrograman oleh **Kelompok 7**.

## 📋 Fitur Utama

Berdasarkan struktur aplikasi, berikut adalah fitur yang tersedia:

1.  **Dashboard**: Menampilkan ringkasan total penggunaan (kWh), jumlah peralatan, dan estimasi biaya bulanan dalam bentuk visual yang mudah dipahami.
2.  **Peralatan Elektronik**: Menu untuk input data perangkat elektronik (Nama alat, Watt, Jumlah unit, dan Durasi pemakaian).
3.  **Penggunaan Listrik**: Melihat detail konsumsi daya berdasarkan data yang telah diinput.
4.  **Estimasi Biaya Listrik**: Menghitung perkiraan tagihan listrik bulanan berdasarkan tarif dan konsumsi.
5.  **Saran Penggunaan**: Fitur cerdas yang memberikan rekomendasi optimasi untuk menghemat biaya listrik dan mengurangi emisi karbon.

## 🛠️ Teknologi yang Digunakan

Aplikasi ini dibangun menggunakan bahasa pemrograman **Python** dengan library berikut:
* **Streamlit**: Framework untuk membuat antarmuka web interaktif (User Interface).
* **Pandas**: Untuk manajemen dan pengolahan data struktur (DataFrame).
* **Plotly**: Untuk membuat visualisasi grafik yang interaktif.
* **NumPy**: Untuk komputasi matematika dan aljabar.

## 🚀 Cara Menjalankan Aplikasi

1.  **Clone Repository**
    ```bash
    git clone [https://github.com/USERNAME_KAMU/NAMA_REPO.git](https://github.com/USERNAME_KAMU/NAMA_REPO.git)
    cd monitor_listrik4
    ```

2.  **Buat Virtual Environment (Opsional tapi disarankan)**
    ```bash
    # Windows
    python -m venv venv
    venv\Scripts\activate

    # Mac/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install Library yang Dibutuhkan**
    ```bash
    pip install -r requirements.txt
    ```
    *(Pastikan file requirements.txt sudah berisi: streamlit, pandas, plotly, numpy)*

4.  **Jalankan Aplikasi**
    ```bash
    streamlit run app.py
    ```

## 📖 Cara Penggunaan (User Guide)

Berikut adalah alur penggunaan aplikasi sesuai flowchart sistem:

1.  **Mulai (Start)**: Buka aplikasi melalui browser (biasanya di `http://localhost:8501`).
2.  **Input Data**: Pergi ke menu **"Peralatan Elektronik"**. Masukkan data alat elektronik di rumahmu (contoh: AC, Kulkas, Lampu), beserta daya (Watt) dan durasi pemakaian harian.
3.  **Monitoring**:
    * Pilih menu **"Penggunaan Listrik"** untuk melihat grafik konsumsi daya.
    * Pilih menu **"Estimasi Biaya"** untuk melihat prediksi tagihan listrikmu.
4.  **Optimasi**: Buka menu **"Saran Penggunaan"**. Aplikasi akan membandingkan penggunaan "Saat Ini" vs "Setelah Saran" dan menunjukkan potensi penghematan (Rupiah & kWh) yang bisa kamu dapatkan.

## 👥 Tim Penyusun (Kelompok 7)

* **Aisah Khoirunnisa** (SI 11-0110124066)
* **Ikmal Rizal** (SI 11-0110124148)
* **Imtiyaz Mufidah** (SI 11-0110124086)
* **Aura Najwa** (SI 11-0110124096)

---
*Dibuat dengan ❤️ menggunakan Python dan Streamlit.*
