# immich-docker
# Immich (Self-Hosted Photo & Video Backup)

**Immich** adalah solusi **self-hosted** untuk backup, pengelolaan, dan sinkronisasi foto & video, sebagai alternatif Google Photos.

Deployment ini menggunakan **Docker Compose** dengan penyimpanan data persisten di host.

---

## ✨ Fitur Utama
- Backup otomatis dari Android & iOS
- Manajemen foto & video berbasis AI
- Face recognition & object detection
- Timeline & album
- 100% self-hosted

---

## 📦 Stack
- Immich Server
- Immich Microservices
- PostgreSQL
- Redis
- Machine Learning Service

---

## 📁 Struktur Direktori

```bash
/opt/immich
├── library/        # Foto & video (UPLOAD_LOCATION)
├── postgres/       # Database PostgreSQL
├── docker-compose.yml
└── .env
