# Katmanlı Güvenlik Notları

## Katmanlı Güvenlik (Layering) 🏰

Katmanlı güvenlik (*Defense in Depth*), birden fazla güvenlik kontrolünün ardışık olarak kullanılmasını ifade eder. Tek bir önlem tüm tehditleri durduramayacağı için çok katmanlı koruma tercih edilir.

### 🔄 Seri vs. Paralel Güvenlik
- ✅ **Seri Güvenlik** (*Serial Security*) (Bankalar, Havalimanları ✈️) → Tek giriş noktası, ardışık kontroller
- ❌ **Paralel Güvenlik** (*Parallel Security*) (Alışveriş Merkezleri 🏢) → Çoklu girişler, daha az kontrol

### 🔐 Ağ Güvenliğinde Katmanlı Koruma (*Network Security*)
Farklı sistemlerin güvenlik önlemleri birleşerek güçlü bir savunma duvarı oluşturur.  
Bir katman başarısız olsa bile, diğerleri tehditleri engeller. Katmanlı güvenlik, sistemleri daha dayanıklı ve güvenli hale getirir. 🚀

---

## Soyutlama (Abstraction) 🎭

Soyutlama, güvenliği daha verimli ve yönetilebilir hale getirmek için kullanılır. Benzer nesneler veya kullanıcılar gruplara ayrılarak tek tek değil, topluca güvenlik kontrolleri uygulanır.

### 🔑 Kullanım Alanları
- **Erişim Yönetimi (*Access Management*)** – Çalışanlar rollerine göre farklı yetkilere sahiptir:
  - 👨‍💼 **Yöneticiler** → Geniş yetkiler
  - 👩‍💻 **Çalışanlar** → Kısıtlı erişim
  - 🛠 **Teknik Personel** → Sistem değişiklikleri yapabilir

- **Veri Tanımlama (*Data Classification*)** – Hangi nesnenin hangi verilere erişebileceğini belirler.

Soyutlama, güvenlik yönetimini basitleştirir ve sistemleri daha güçlü hale getirir. 🚀

---

## Veri Gizleme (Data Hiding) 🔒

Veri gizleme, yetkisiz erişimi önlemek için verileri saklama veya erişilemez hale getirme yöntemidir. Bilgilerin belirli kullanıcılar veya sistemler tarafından görülmesini veya keşfedilmesini engeller.

### Örnekler:
- 🛑 Yetkisiz kişilerin bir veritabanına erişmesini önlemek
- 🔐 Düşük yetkili kullanıcıların yüksek seviyeli verilere erişmesini engellemek
- 🚫 Uygulamaların donanıma doğrudan erişimini kısıtlamak

Veri gizleme, güvenlik kontrollerinde ve yazılım geliştirmede önemli bir rol oynar. Verilere yalnızca yetkili kişilerin erişmesini sağlayarak sistemlerin korunmasına yardımcı olur. 🚀

---

## Şifreleme (Encryption) 🔑

Şifreleme, verileri korumak için kullanılan bir yöntemdir. Veriler belirli bir algoritma ile şifrelenir ve yalnızca yetkili kişiler tarafından çözülebilir.

### 📌 Temel Şifreleme Türleri:
- **Simetrik Şifreleme (*Symmetric Encryption*)** → Tek anahtar kullanılır. (Örn: AES, DES)
- **Asimetrik Şifreleme (*Asymmetric Encryption*)** → İki farklı anahtar (açık ve özel) kullanılır. (Örn: RSA, ECC)

### 📌 Şifreleme Kullanım Alanları:
- **Veri Güvenliği:** Hassas bilgilerin korunması
- **İletişim Güvenliği:** E-posta, mesajlaşma uygulamalarında güvenlik
- **Kimlik Doğrulama:** Dijital imzalar ve sertifikalar

Şifreleme, verilerin korunmasını sağlayarak siber güvenliğin temel taşlarından biri olur. 🔐🚀
