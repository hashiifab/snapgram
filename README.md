# 🚀 SocialMedia App - React + Vite

A modern social media platform featuring real-time posts, user management, and file storage powered by Appwrite.

---

## 🛠 Tech Stack

### Backend
- **Appwrite** - Database, Authentication & Storage
- **React Query** - Data fetching & caching

### Frontend
- **React 18**
- **TypeScript**
- **Vite**
- **Shadcn/ui** - Modern UI components
- **Tailwind CSS**

---

## 🌟 Main Features

- 📝 Create and manage social media posts
- 👥 User authentication via Appwrite
- 🖼 Image uploads with Appwrite Storage
- 🔍 Real-time search
- 💾 Structured data storage using Appwrite Database
- ⚡ Performance optimized with React Query

---

## 📁 Folder Structure

```bash
social_media_app/
├── src/
│   ├── _auth/          # Authentication pages
│   ├── _root/          # Main layout
│   ├── components/     # Reusable UI components
│   ├── constants/      # App constants
│   ├── context/        # React context providers
│   ├── hooks/          # Custom hooks
│   ├── lib/
│   │   ├── appwrite/   # Appwrite config
│   │   └── react-query # Queries & mutations
│   ├── types/          # TypeScript definitions
│   └── ...
├── public/             # Static assets
└── ...

```

## 🖥 Instalasi Lokal

```bash
npm install
npm run dev
```

## 🔑 Environment Variables

Buat file `.env` dengan konten:
```
VITE_APPWRITE_URL='https://cloud.appwrite.io/v1'
VITE_APPWRITE_PROJECT_ID='your_project_id'
VITE_APPWRITE_DATABASE_ID='your_database_id'
VITE_APPWRITE_STORAGE_ID='your_storage_id'
VITE_APPWRITE_POST_COLLECTION_ID='your_collection_id'
VITE_APPWRITE_USER_COLLECTION_ID='your_collection_id'
VITE_APPWRITE_SAVES_COLLECTION_ID='your_collection_id'
```

## 📚 Dokumentasi Appwrite

1. Pastikan Appwrite project sudah dibuat di cloud/appwrite.io
2. Buat database dan koleksi sesuai ID yang terdaftar di `.env`
3. Konfigurasi permissions di Appwrite Console untuk:
   - Database
   - Storage
   - Authentication

## 👨💻 Penulis
- GitHub: [@hashiifabdillah](https://github.com/hashiifab)
- LinkedIn: [Hashiif Abdillah](https://www.linkedin.com/in/hashiif-abdillah-665373297/)