# 🚓 PlakaDedektifi

PlakaDedektifi, Android cihazlar için geliştirilen açık kaynaklı bir uygulamadır. Uygulama, kamera görüntüsünü kullanarak trafikteki yasa dışı sürüş davranışlarını (örneğin ters şerit, ani fren, çakar kullanımı, uygunsuz sollama) algılar, olay anının fotoğrafını çeker, araç plakasını tanır ve yetkililere otomatik olarak bildirir.

---

## 📱 Özellikler

- 📷 **Gerçek Zamanlı Kamera İzleme**
- 🚨 **Yasa Dışı Davranış Tespiti**
- 🔎 **Plaka Tanıma (OCR)**
- 📤 **Yetkililere Otomatik Rapor Gönderimi**
- 🤖 **TensorFlow Lite ile Görüntü İşleme**

---

## 🛠️ Kullanılan Teknolojiler

- Kotlin / Android SDK
- CameraX
- TensorFlow Lite
- ML Kit (OCR)
- Firebase (bildirim için, isteğe bağlı)
- OpenCV (isteğe bağlı)

---

## 📂 Proje Yapısı

```
PlakaDedektifi/
├── app/
│   └── src/
│       └── main/
│           ├── java/com/techdrivex/plakadedektifi/
│           │   ├── MainActivity.kt
│           │   ├── CameraAnalyzer.kt
│           │   ├── PlateRecognizer.kt
│           │   ├── ViolationDetector.kt
│           │   └── Reporter.kt
│           ├── res/
│           └── assets/models/
│               ├── violation_model.tflite
│               └── plate_ocr.tflite
```

---

## 🚧 Geliştirme Aşamaları

- [x] Kamera ve canlı görüntü analizi
- [x] TensorFlow Lite model entegrasyonu
- [x] Plaka OCR entegrasyonu
- [ ] Otomatik yetkili bilgilendirme API'si
- [ ] Çevrimdışı çalışma desteği
- [ ] Açık veri setiyle eğitilmiş modeller

---

## 🧠 Nasıl Katkı Sağlayabilirim?

1. Bu repoyu fork'la
2. Yeni bir dal (branch) oluştur (`feature/yenilik`)
3. Değişikliklerini yap ve commit et
4. Pull Request gönder 🎉

---

## 📜 Lisans

MIT Lisansı

---

## 👤 Geliştirici

Bu proje [TechDriveX](https://github.com/techdrivex) tarafından açık kaynak olarak geliştirilmektedir.

---

## 🛡️ Uyarı

PlakaDedektifi yalnızca kamu yararına geliştirilmiştir. Yasalara aykırı veri toplama, ifşa veya özel yaşamın gizliliğini ihlal edecek şekilde kullanılması **yasaktır**.
