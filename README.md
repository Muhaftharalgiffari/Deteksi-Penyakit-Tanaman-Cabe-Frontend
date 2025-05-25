# ChiliDetect - Deteksi Penyakit Daun Cabai

Aplikasi web untuk mendeteksi penyakit pada daun cabai menggunakan machine learning.

## 🚀 Fitur

- Upload gambar daun cabai
- Deteksi penyakit secara otomatis
- Riwayat deteksi
- Informasi jenis cabai dan penyakit
- Profil tim pengembang

## 🛠️ Teknologi

### Frontend
- Vite
- Tailwind CSS
- Vanilla JavaScript

### Backend
- Node.js
- Express.js
- Python (untuk model ML)

## 📦 Instalasi

### Backend
```bash
cd backend
npm install
npm run dev
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

## 📁 Struktur Proyek

```
chilidetect/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── api/
│   │   └── style/
│   ├── public/
│   └── vite.config.js
└── backend/
    ├── server.js
    ├── predict.py
    └── uploads/
```

## 🌐 API Endpoints

- `POST /api/predict` - Upload gambar dan dapatkan prediksi

## 🎨 Warna Tema

- Primary: #E63946 (Merah Cabai)
- Secondary: #A8DADC (Hijau Daun)
- Light: #F1FAEE (Putih)
- Dark: #1D3557 (Abu Gelap)

## 👥 Tim Pengembang

- [Nama Anggota 1] - Role
- [Nama Anggota 2] - Role
- [Nama Anggota 3] - Role 