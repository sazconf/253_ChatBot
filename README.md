# 253_ChatBot

Praktikum Web Service - Pertemuan 10: Implementasi ChatBot AI dengan Streaming Response (Server-Sent Events) menggunakan Express.js dan OpenRouter API.

## Fitur
- **Express.js Server**: Menyajikan file frontend statis dan endpoint API.
- **OpenRouter AI Integration**: Menggunakan model `openai/gpt-4o-mini` melalui OpenRouter.
- **Streaming Response**: Real-time response streaming menggunakan Server-Sent Events (SSE) dengan `TextDecoder` dan stream reader.
- **Web UI**: Antarmuka obrolan web interaktif berbasis HTML, CSS, dan JavaScript vanilla.

## Prasyarat
- [Node.js](https://nodejs.org/) (v18 ke atas disarankan)
- API Key dari [OpenRouter](https://openrouter.ai/)

## Konfigurasi
1. Gandakan file `.env.example` menjadi `.env`:
   ```bash
   cp .env.example .env
   ```
2. Isi nilai `OPENROUTER_API_KEY` pada file `.env`:
   ```env
   PORT=3000
   OPENROUTER_API_KEY=sk-or-v1-xxxxxxxxxxxx
   ```

## Menjalankan Aplikasi
1. Instal dependensi:
   ```bash
   npm install
   ```
2. Jalankan server:
   ```bash
   npm start
   ```
   Atau untuk mode pengembangan (auto-reload):
   ```bash
   npm run dev
   ```
3. Buka browser pada alamat:
   ```
   http://localhost:3000
   ```
