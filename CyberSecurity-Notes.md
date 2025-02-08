# **Siber Güvenlik Temelleri ve Şifreleme Yöntemleri**  

## **1️⃣ CIA Triad (CIA Üçgeni) – Önemli Olan Denge**  
Bilgi güvenliği **üç temel unsur** üzerine kurulur:  

### ✅ **Confidentiality (Gizlilik)**  
Bilgilerin yetkisiz kişiler tarafından erişilmesini engeller.  

**Örnekler:**  
- **Şifreleme (Encryption)** – Veriyi yalnızca yetkili kişilerin okuyabilmesini sağlar.  
- **Proof of Concept:** Man-in-the-Middle (MitM) Attack (Ortadaki Adam Saldırısı)  
- **Yetkilendirme (Access Control)** – Kullanıcı izinlerini belirler.  

### ✅ **Integrity (Bütünlük)**  
Bilgilerin doğruluğunu, tutarlılığını ve değiştirilmeden kalmasını sağlar.  

**Örnekler:**  
- **Hashing (Özetleme Algoritmaları)** – Verinin değişmediğini kontrol etmek için kullanılır.  
- **Erişim Kontrolleri (Access Control)** – Yetkisiz değişiklikleri önler.  
- **Yedekleme (Backups) & Sistem Kayıtları (Logs)** – Veri kaybı ve hataların önüne geçer.  

### ✅ **Availability (Erişilebilirlik)**  
Bilginin yetkili kişiler tarafından her zaman ulaşılabilir olması gerekir.  

**Örnekler:**  
- **Sistem yedekleme (Backup Solutions)**  
- **Siber saldırılara karşı savunma (DDoS koruması, antivirüs programları)**  
- **Acil durum planları (Disaster Recovery Plan)**  

📌 **ÖNEMLİ:**  
CIA Triad'daki üç unsurun dengeli olması gerekir. Biri aşırıya kaçarsa, diğerlerini olumsuz etkileyebilir.  

---

## **2️⃣ Veri Türleri**  
- **Data at Rest (Bekleyen Veri)** – Sabit disk, USB veya veritabanında saklanan veri.  
- **Data in Transit (İletimdeki Veri)** – Ağ üzerinden iletilen veri (e-posta, internet trafiği vb.).  
- **Data in Use (Kullanımdaki Veri)** – Aktif olarak işlenen veri (RAM’de veya açık bir dosyada bulunan veri).  

---

## **3️⃣ Brute Force Attack (Kaba Kuvvet Saldırısı)**  
Bir saldırganın **tüm olası şifre kombinasyonlarını tek tek deneyerek** parolayı kırmaya çalışmasıdır.  

📌 **Örnek:**  
- **0-0-0-0’dan başlayarak tüm kombinasyonları denemek.**  

### **🛡 Brute Force Saldırılarına Karşı Önlemler**  
- **Güçlü Parola Kullanımı** – Uzun, karmaşık ve tahmin edilmesi zor şifreler seçilmeli.  
- **Şifre Deneme Sınırlandırması** – Belirli sayıda hatalı girişten sonra hesap kilitlenmeli.  
- **İki Faktörlü Kimlik Doğrulama (2FA)** – Ek güvenlik katmanı sağlanmalı.  
- **Salt & Hashing** – Parola veri tabanlarının Rainbow Table saldırılarına karşı korunması için kullanılmalı.  

📌 **Brute Force İçin Kullanılan Veritabanları:**  
- **Rainbow Tables (RockYou, CrackStation, Hashes.org Database)**  
- **NTDS.dit (Windows’un Active Directory şifreleri içeren dosyası)**  

---

## **4️⃣ Şifreleme Türleri**  
Şifreleme yöntemleri **2 ana gruba** ayrılır:  

### **1) Simetrik Şifreleme (Symmetric Encryption)**  
- Aynı anahtar hem **şifreleme** hem **şifre çözme** işlemleri için kullanılır.  
- **Hızlıdır**, ancak anahtar paylaşımı güvenlik riski oluşturabilir.  

**Popüler Algoritmalar:**  
- **DES (Data Encryption Standard)**  
- **AES (Advanced Encryption Standard) – Günümüzde en yaygın kullanılan algoritma**  
- **3DES, IDEA, BLOWFISH, SKIPJACK**  

📌 **Önemli Bilgiler:**  
- **DES (1977, ABD hükümeti tarafından geliştirildi).**  
- **DES 56-bit anahtar kullanır ve 16 tur şifreleme uygular.**  
- **DES artık güvenli değildir, 2001’de AES ile değiştirildi.**  
- **AES ise 128, 192 ve 256-bit anahtar uzunluklarıyla kullanılabilir.**  

### **2) Asimetrik Şifreleme (Asymmetric Encryption)**  
- **İki farklı anahtar kullanır:**  
  - **Public Key (Açık Anahtar)** → Şifreleme için kullanılır.  
  - **Private Key (Özel Anahtar)** → Şifre çözme için kullanılır.  
- **Daha güvenlidir** ancak simetrik şifrelemeye göre **daha yavaştır.**  

**Örnekler:**  
- **RSA** – Şifreleme için yaygın olarak kullanılır.  
- **Diffie-Hellman** – Anahtar değişimi için kullanılır.  
- **ECC (Elliptic Curve Cryptography)** – Mobil cihazlar için daha verimli bir alternatif.  

📌 **Asimetrik Şifreleme Avantajları & Dezavantajları**  
✅ **Avantaj:** Güvenli anahtar paylaşımı sağlar.  
❌ **Dezavantaj:** Simetrik şifrelemeye kıyasla daha yavaş çalışır.  

---

## **📌 Özet – En Önemli Noktalar**  
- **CIA Triad:** Gizlilik, Bütünlük, Erişilebilirlik **(Denge Önemli!)**  
- **Brute Force:** Tüm olasılıkları deneyerek parolaları kırma saldırısı.  
- **Simetrik Şifreleme:** **AES, DES, IDEA** (Hızlı ama anahtar paylaşımı riskli)  
- **Asimetrik Şifreleme:** **RSA, Diffie-Hellman** (Güvenli ama yavaş)  
- **Anahtar Paylaşımı:** Offline, Açık Anahtar Şifreleme veya Diffie-Hellman  
