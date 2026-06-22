# AI-bouqet-advisor-chatbot
Chatbot berbasis AI untuk rekomendasi buket bunga yang dibangun menggunakan n8n, Google Gemini, Telegram Bot, dan Google Sheets.

## Gambaran Umum
Chatbot ini membantu pengguna menemukan buket bunga yang sesuai untuk berbagai acara, seperti:
* Wisuda
* Pernikahan
* Ulang Tahun
* Peringatan Hari Jadi (Anniversary)
Chatbot ini menggunakan Google Gemini sebagai model bahasa dan Google Sheets sebagai basis pengetahuan produk.

## Fitur
* Rekomendasi buket
* Saran berdasarkan acara
* Penyaringan produk
* Respons yang dibatasi pada domain tertentu
* Integrasi Telegram

## Teknologi
* n8n
* Google Gemini API
* Telegram Bot API
* Google Sheets

## Arsitektur
Pengguna Telegram → Telegram Bot → Alur Kerja n8n → Google Gemini → Google Sheets → Respons
