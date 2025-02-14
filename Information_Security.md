
# Information Security Concepts

## Sensitivity (Duyarlılık)
**Duyarlılık**, bir bilginin açıklanması veya yetkisiz kişilerle paylaşılması durumunda ortaya çıkabilecek zarar veya riskleri ifade eder. Yüksek derecede hassas bilgiler açığa çıkarsa ciddi problemler yaratabilir.

### Örnekler:
- **Müşteri şifrelerinin sızdırılması** → Saldırı riski artar.
- **Tıbbi kayıtların açığa çıkması** → Mahremiyet ihlali ortaya çıkar.

### Anahtar Kelimeler:
- **Data Exposure** → Veri açığa çıkması
- **Information Leakage** → Bilgi sızıntısı
- **Unauthorized Access** → Yetkisiz erişim

---

## Discretion (Takdir Yetkisi)
**Takdir yetkisi**, bilgilere farklı kişilerin farklı seviyelerde erişebilmesini ve müdahale edebilmesini ifade eder.

### Anahtar Kelimeler:
- **Access Control** → Erişim kontrolü
- **Privilege Levels** → Yetki seviyeleri
- **Role-Based Access** → Rol tabanlı erişim

---

## Criticality (Kritiklik)
**Kritiklik**, bir bilginin bir kuruluş için ne kadar hayati veya önemli olduğunu gösterir. Sensitivity'den farklı olarak, kuruluşun operasyonlarına veya projelerine etkisiyle ilgilidir.

### Anahtar Kelimeler:
- **Business Impact** → İş etkisi
- **Mission-Critical** → Görev açısından kritik
- **Operational Risk** → Operasyonel risk

---

## Concealment (Gizleme)
**Gizleme**, bilgiyi koruma veya karmaşıklaştırma yöntemlerini ifade eder.

### Örnekler:
- **Askeri belgelerin şifrelenerek korunması**
- **VPN kullanımı ile kişisel IP adresinin gizlenmesi**

### Anahtar Kelimeler:
- **Encryption** → Şifreleme
- **Obfuscation** → Belirsizleştirme
- **Steganography** → Steganografi (gizli yazı tekniği)

---

## Secrecy (Gizlilik)
**Gizlilik**, bilginin tamamen saklı tutulması ve asla dışarı sızmaması anlamına gelir.

### Confidentiality (Gizlilik) ile farkı:
- **Confidentiality** → Bilginin yetkisiz kişilerden saklanması
- **Secrecy** → Bilginin kesinlikle dış dünyaya açılmaması

### Anahtar Kelimeler:
- **Non-Disclosure Agreement (NDA)** → Gizlilik sözleşmesi
- **Trade Secrets** → Ticari sırlar
- **Need-to-Know Basis** → Bilmesi gereken prensibi

---

## Privacy (Mahremiyet)
**Mahremiyet**, kişisel bilgilerin başkaları tarafından izinsiz olarak ele geçirilmesini önlemeyi amaçlar.

### Örnekler:
- **KVKK, GDPR** gibi yasalar kişisel verileri korumak için oluşturulmuştur.

### Anahtar Kelimeler:
- **Data Protection** → Veri koruma
- **Personal Identifiable Information (PII)** → Kişisel tanımlayıcı bilgi
- **Anonymization** → Anonimleştirme

---

## Seclusion (Tecrit)
**Tecrit**, bilgilere erişimin belirli bir yerde sınırlandırılması ve yalnızca belirli kişilere izin verilmesidir.

### Örnekler:
- **Gizli araştırma laboratuvarlarında, global internete bağlı olmadan verilerin saklanması**
- **Gizli kasalarda dosyaların saklanması**

### Anahtar Kelimeler:
- **Restricted Access** → Kısıtlı erişim
- **Secure Storage** → Güvenli depolama
- **Classified Information** → Gizli bilgi

---

## Isolation (Yalıtım)
**Yalıtım**, bilgilerin birbirinden tamamen ayrı tutulmasını sağlar. Bazı bilgileri izole ederek yalnızca yetkililerin erişimine açık hale getirir.

### Örnekler:
- **Devletin özel ağları kullanması (Air-Gapped Networks)**
- **Farklı departmanlarda verilerin ayrı tutulması**

### Anahtar Kelimeler:
- **Network Segmentation** → Ağ bölümlendirme
- **Sandboxing** → Korumalı alan oluşturma
- **Air-Gap Security** → Fiziksel ağ yalıtımı
