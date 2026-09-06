# 📱 Doripay — Aplikasi PPOB (Payment Point Online Bank)

## Tentang Aplikasi

**Doripay** adalah aplikasi web pembayaran digital (PPOB) yang memungkinkan pengguna untuk membeli produk-produk digital seperti pulsa, paket data, token listrik, voucher game, dan membayar tagihan bulanan — semuanya dalam satu tempat yang praktis dan efisien.

## Arsitektur & Teknologi

Aplikasi ini dibangun dengan arsitektur modern untuk memastikan performa yang cepat, aman, dan mudah dikembangkan:

*   **Backend:** Go (Golang) + Fiber Framework + PostgreSQL
*   **Frontend:** Svelte + Tailwind CSS
*   **Provider H2H:** Terintegrasi dengan Digiflazz & OrderKuota (Orkut) sebagai penyedia produk *Host-to-Host*
*   **Payment Gateway:** Tripay (Mendukung QRIS, Virtual Account, dan E-Wallet)
*   **Integrasi AI/Bot:** Bot WhatsApp untuk pencatatan keuangan (Buku Kas) dan bantuan transaksi pengguna

---

## Modul Pengujian (Quality Assurance)

Berikut adalah daftar cakupan modul yang diuji (*Test Cases*) untuk memastikan stabilitas dan fungsionalitas sistem:

| Modul | TC Yang Diuji |
| :--- | :--- |
| **Dashboard** | |
| **Katalog & Pembelian** | |
| **Top Up Saldo** | |
| **Riwayat Transaksi** | |
| **Profil** | |
| **Keuangan & Buku Kas** | |
| **Notifikasi** | |
| **Pusat Bantuan** | |
