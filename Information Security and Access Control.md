## **Bilgi Güvenliği ve Erişim Kontrolü Kavramları**  

### **1. Kimlik Tespiti (Identification)**  
- Kullanıcının kim olduğunu beyan etmesi.  
- **Örnek:** Kullanıcı adı girmek.  
- **Not:** Kimlik tespiti erişim hakkı vermez.  

---

### **2. Kimlik Doğrulama (Authentication)**  
- Kullanıcının gerçekten beyan ettiği kişi olup olmadığının doğrulanması.  
- **Yöntemler:**  
  - Şifre, PIN, parola  
  - Biyometrik veri (parmak izi, yüz tanıma)  
- **Not:** Kimlik doğrulama, tek başına erişim hakkı vermez.  

---

### **3. Yetkilendirme (Authorization)**  
- Kullanıcının hangi kaynaklara erişebileceğinin belirlenmesi.  
- **Örnek:** Sisteme giriş yapmak ama tüm dosyalara erişememek.  

---

### **4. Denetleme (Auditing)**  
- Kullanıcı işlemlerini izleme ve kaydetme süreci.  
- **Amaç:**  
  - Yetkisiz erişimleri tespit etmek.  
  - Sistem hatalarını incelemek.
  - Bu sayede sistem çökme nedenleri incelenebilir.
- **Örnek:** Günlük (log) kayıtlarının tutulması.  

---

### **5. Hesap Verebilirlik (Accountability)**  
- Kullanıcıların yaptıkları işlemlerden sorumlu tutulması.  
- **Sağlanma Yöntemleri:**  
  - Kimlik tespiti  
  - Kimlik doğrulama  
  - Yetkilendirme  
  - Denetleme  

---

### **6. İnkar Edilemezlik (Nonrepudiation)**  
- Kullanıcının yaptığı işlemi reddetmesini önler.  
- **Örnek:** Dijital imza ile e-posta gönderildiğinde, gönderen sonradan inkâr edemez.
