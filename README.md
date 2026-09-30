# MEB Araştırma Kontrol Platformu

Bu paket üç hedef kullanım biçimi için ortak bir başlangıç ürünüdür:

1. Web / PWA
2. Mobil (PWA; ileride Capacitor)
3. Masaüstü (Tauri wrapper)

## Hemen çalıştırma

`web/index.html` dosyasını modern bir tarayıcıda açabilirsiniz.

PWA servis çalışanı bazı tarayıcılarda `file://` üzerinden çalışmayabilir. PWA kurulumu için basit bir HTTP sunucusu kullanın.

Örnek:
`python -m http.server 8080 --directory web`

Sonra:
`http://localhost:8080`

## Önemli
Bu sürüm bir **çalışan prototiptir**. Gerçek APK/EXE, merkezi backend ve gerçek PDF/DOCX/OCR motoru henüz derlenip test edilmemiştir.

## Kaynak kural seti
- 26.06.2025 Araştırma Uygulama İzinleri Yönergesi
- 2025 Başvuru ve Değerlendirme Kılavuzu
- EK 1 – 30 değerlendirme kriteri
- 07.08.2025 duyuru
