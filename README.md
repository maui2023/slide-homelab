# Modern HTML5 Presentation Slides

Satu persembahan slaid (*presentation deck*) moden yang dibina sepenuhnya menggunakan HTML5, CSS3, dan JavaScript. Projek ini direka bentuk khusus untuk memberikan pengalaman interaktif yang lancar, dinamik, dan premium.

## 🚀 Ciri-ciri Utama

- **Interaktif & Beranimasi**: Menggunakan animasi mikro dan peralihan slaid yang lancar untuk menarik perhatian audiens.
- **Navigasi Tanpa Butang (*Buttonless Navigation*)**:
  - Antara muka yang bersih tanpa butang navigasi fizikal yang menyemak skrin.
  - Menggunakan pembahagian kawasan skrin (*split screen detection*) untuk kawalan:
    - **Kawasan Kanan (*Right Half*)**: Klik atau ketik (*tap*) untuk ke slaid seterusnya (**Next Slide**).
    - **Kawasan Kiri (*Left Half*)**: Klik atau ketik (*tap*) untuk kembali ke slaid sebelumnya (**Back Slide**).
- **Reka Bentuk Premium (*Glassmorphism & Dark Mode*)**: Tema gelap yang estetik dengan kesan kad kaca, bayangan bercahaya (*glow orbs*), dan tipografi moden menggunakan Google Fonts.
- **Responsif Sepenuhnya**: Sesuai untuk dipaparkan pada pelbagai saiz skrin, daripada peranti mudah alih hinggalah ke skrin projektor bilik mesyuarat.

## 🛠️ Teknologi yang Digunakan

- **HTML5 & CSS3**: Struktur semantik dengan CSS Grid/Flexbox, pemboleh ubah CSS, dan kesan `backdrop-filter`.
- **Vanilla JavaScript**: Mengurus logik pembahagian skrin untuk navigasi kiri/kanan.
- **GSAP (GreenSock Animation Platform)**: Mengawal animasi masuk (*reveal effects*) dan peralihan slaid.
- **Lenis Smooth Scroll / ScrollTrigger**: Memastikan tatalan persembahan terasa sangat lancar dan organik.

## 🎮 Cara Kawalan Persembahan

Navigasi slaid ini adalah sangat intuitif:

| Tindakan | Fungsi | Kawasan Skrin |
| :--- | :--- | :--- |
| **Klik/Ketik Sebelah Kanan** | Slaid Seterusnya (Next) | 50% Bahagian Kanan Skrin |
| **Klik/Ketik Sebelah Kiri** | Slaid Sebelumnya (Back) | 50% Bahagian Kiri Skrin |

> [!NOTE]
> Kawasan navigasi ini tidak kelihatan secara visual (*invisible zones*) untuk mengekalkan kebersihan reka bentuk slaid anda.

## 📦 Cara Menjalankan Projek

1. Buka pautan persembahan slaid secara langsung: [https://maui2023.github.io/slide-homelab](https://maui2023.github.io/slide-homelab)
2. *Alternatif (Tempatan):* Buka folder projek dan jalankan fail `index.html` menggunakan Live Server di VS Code untuk pembangunan tempatan.

## 📝 Kandungan Slaid Pembentangan

Slaid pembentangan ini merangkumi panduan membina Homelab peribadi secara langkah demi langkah:
1. **Pengenalan Homelab**: Apa itu Homelab dan objektif utama kelas.
2. **Sebab Memilih PC Lama**: Perbandingan kos dan privasi berbanding Cloud/NAS.
3. **Senibina & Aliran Sistem**: Bermula daripada PC Lama -> **Ubuntu 26.04 LTS (Resolute Raccoon)** -> Docker Engine -> CasaOS Dashboard -> Aplikasi Web.
4. **Modul 01: Asas Ubuntu 26.04 LTS**: Pengenalan CLI, arahan SSH, navigasi sistem fail, dan kemas kini repositori.
5. **Modul 02: Kuasa Docker**: Konsep containerization vs persekitaran tradisional.
6. **Modul 03: Dashboard CasaOS**: Arahan pemasangan satu baris dengan butang salin:
   ```bash
   curl -fsSL https://get.casaos.io | sudo bash
   ```
7. **Pilihan Aplikasi Docker**:
   - **File Browser**: Pengurusan fail berasaskan web.
   - **Jellyfin**: Pelayan media peribadi (*Netflix self-hosted*).
   - **Uptime Kuma**: Pemantauan status peranti & rangkaian.
   - **Vaultwarden**: Pengurus kata laluan peribadi (*self-hosted Bitwarden*).
   - **AdGuard Home & Pi-Hole**: Penapis DNS dan penyekat iklan peringkat rangkaian.
   - **MySpeed**: Perekod kelajuan internet berkala secara automatik.
   - **Tailscale VPN**: Rangkaian VPN selamat tanpa memerlukan *port forwarding*.
   - **Hermes AI**: AI Agent pintar hos sendiri dengan memori berterusan (*self-hosted AI assistant*).

