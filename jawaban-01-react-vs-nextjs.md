# 📝 Jawaban — 01. React vs Next.js

| Info | Detail |
|------|--------|
| **Nama** | Muhammad Faizal |
| **NIM** | 105841104623 |
| **Halaman** | 01. React vs Next.js |
| **Tanggal** | 29 April 2026, 16.35 |

---

## 📝 Kuis Singkat

### 1. Next.js adalah...

**Jawaban:** 
Next.js adalah framework berbasis React yang digunakan untuk membangun aplikasi web dengan fitur tambahan seperti routing otomatis, server-side rendering, dan optimasi performa.

### 2. Mana yang TIDAK perlu di-install manual di Next.js?

**Jawaban:** 
Routing (karena sudah otomatis disediakan oleh Next.js).

### 3. Saat install Next.js, agar menggunakan JavaScript (bukan TypeScript), kita harus pilih...

**Jawaban:** 
Pilih No saat ditanya ingin menggunakan TypeScript.

### 4. Apakah komponen React bisa dipakai di Next.js?

**Jawaban:** 
Ya, bisa. Next.js sepenuhnya menggunakan React, jadi semua komponen React tetap bisa digunakan.

### 5. Sebutkan minimal 3 fitur yang Next.js berikan di atas React biasa!

**Jawaban:** 
Routing otomatis (file-based routing)
Server-Side Rendering (SSR)
Static Site Generation (SSG)
API Routes (backend sederhana di dalam project)
Image Optimization

---

## ✏️ Jawaban Latihan

### Latihan 1 — Halaman Utama

import Image from "next/image";
import styles from "./page.module.css";

export default function Home() {
  return (
    <main>
      <h1>🎓 Halo Mahasiswa!</h1>
      <p>Ini proyek Next.js pertama saya.</p>
      <p>Menggunakan <strong>JavaScript</strong>, bukan TypeScript.</p>
    </main>
  );
}

### Latihan 2 — Halaman About

export default function About() {
  return <h1>Welcome</h1>;
}

### Latihan 3 — Tantangan: Bandingkan Routing
React: lebih fleksibel tapi butuh setup manual
Next.js: lebih praktis dan cepat karena routing sudah otomatis



---

## 📊 Ringkasan

| Metrik | Nilai |
|--------|-------|
| Total dijawab | 0 / 8 |
| Skor kuis | 0 / 4 (0%) |
| Latihan terisi | 0 / 3 |

---

_Dibuat otomatis oleh Sistem Kuis Pertemuan 00_
