# ESP32-S3 LVGL Widgets Demo
Program demo **LVGL Widgets** untuk **ESP32-S3 HMI 4.3" 480×270 LCD**, 8MB PSRAM, 16MB Flash, mendemonstrasikan rendering GUI berbasis **LVGL** dengan dukungan WiFi & Bluetooth.  

Program ini menggunakan:
- **LVGL** (Light and Versatile Graphics Library) untuk rendering grafis.
- **Arduino GFX Library** untuk komunikasi display RGB.
- Driver sentuh yang terpisah (XPT2046, FT6X36, GT911).

---

## Spesifikasi Hardware
- **MCU:** ESP32-S3
- **PSRAM:** 8MB
- **Flash:** 16MB
- **Layar:** 4.3" RGB LCD (Resolusi: 480×270)
- **Touch:** Kapasitif (contoh: GT911)
- **Fitur Tambahan:** WiFi, Bluetooth

---

## Fitur Program
✅ Inisialisasi driver LCD RGB  
✅ Inisialisasi driver sentuh (konfigurasi di `touch.h`)  
✅ Pengujian warna dasar (merah, hijau, biru, hitam)  
✅ Render demo LVGL Widgets  
✅ Dukungan buffer internal PSRAM  
✅ Konfigurasi kustom resolusi layar

---

## Dependensi Library
Anda **wajib** menginstal library berikut di Arduino IDE atau PlatformIO:

### LVGL
- Repo: [https://github.com/lvgl/lvgl](https://github.com/lvgl/lvgl)

**Konfigurasi LVGL:**
1. Salin file konfigurasi:
