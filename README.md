# 🩺 Diabetic Foot Ulcer (DFU) Detection & Localization

Dokumentasi penelitian dan pengembangan model *Deep Learning* untuk deteksi serta lokalisasi objek (*Object Detection*) area luka kaki diabetik (*Diabetic Foot Ulcer* / DFU) pada citra medis menggunakan arsitektur **YOLOv8s** dan **SSD300-VGG16**.

---

## 📌 Abstraksi / Latar Belakang

Diabetic Foot Ulcer (DFU) merupakan salah satu komplikasi serius dari diabetes melitus yang dapat menyebabkan infeksi, nekrosis jaringan, hingga amputasi jika tidak ditangani sejak dini. Deteksi DFU secara manual melalui observasi visual oleh tenaga medis sering menghadapi kendala berupa:
1. Subjektivitas penilaian.
2. Variasi tingkat pengalaman klinis.
3. Keterlambatan identifikasi akibat neuropati pada pasien.

Oleh karena itu, pendekatan berbasis *Deep Learning* berpotensi membantu proses deteksi secara lebih cepat, objektif, dan konsisten. **Penelitian ini bertujuan membandingkan performa dua model *single-stage object detection*, yaitu YOLOv8s dan SSD300-VGG16, untuk mendeteksi serta melokalisasi area ulcer pada citra kaki diabetik.**

---

## ✨ Arsitektur & Model yang Dibandingkan

Proyek ini berfokus pada evaluasi dua pendekatan *single-stage object detection*:

* **YOLOv8s (You Only Look Once v8 - Small):** Model deteksi objek generasi terbaru yang dirancang untuk performa tinggi, kecepatan inferensi cepat, serta bobot model yang tergolong ringan.
* **SSD300-VGG16 (Single Shot MultiBox Detector 300 dengan Backbone VGG16):** Arsitektur deteksi objek klasik yang memanfaatkan *multi-scale feature maps* dari tulang belakang VGG16 untuk mengenali objek dalam berbagai ukuran citra.
