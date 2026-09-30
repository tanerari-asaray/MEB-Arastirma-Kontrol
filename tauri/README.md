# Tauri masaüstü paketleme iskeleti

Bu klasör, `web/` uygulamasının Windows/macOS/Linux masaüstü uygulamasına sarılması için ayrılmıştır.

Gerçek Tauri derlemesi bu çalışma ortamında yapılmadı. Bu nedenle burada "EXE oluşturuldu" iddiası yoktur.

Önerilen adımlar:
1. Rust + Tauri kurulumu.
2. `web/` içeriğini Tauri frontend olarak bağlama.
3. Dosya sistemi izinlerini minimum yetkiyle tanımlama.
4. Windows release build.
5. Gerçek Windows cihazında kurulum ve test.
