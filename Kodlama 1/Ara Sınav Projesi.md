
### **Proje Gereksinimleri:**

#### 1. **Öğrenci Bilgilerinin Girişi (Hafta 1, 2, 3)**
   - Kullanıcıdan her öğrenci için şu bilgileri isteyin: isim (string), öğrenci numarası (int), üç farklı dersten alınan notlar (float).
   - `printf` ve `scanf` kullanarak kullanıcıdan giriş alın.
   - Örnek giriş:
     ```
     Öğrencinin ismini girin: Doğa Çöl
     Öğrencinin numarasını girin: 12345
     Matematik notunu girin: 85.5
     Fen notunu girin: 90.0
     Edebiyat notunu girin: 78.2
     ```

#### 2. **Ortalama Hesaplama ve Not Atama (Hafta 4, 5)**
   - Üç notu aldıktan sonra, her öğrenci için **ortalama** notu hesaplayın.
   - Ortalama nota göre `if-else` veya `switch-case` yapısını kullanarak şu harf notunu atayın:
     - A: 90-100
     - B: 80-89
     - C: 70-79
     - D: 60-69
     - F: 60’ın altı
   - Öğrencinin adını, numarasını, ortalama notunu ve harf notunu yazdırın.
   - Örnek çıktı:
     ```
     Doğa Çöl (Numara: 12345) - Ortalama: 84.6, Not: B
     ```

#### 3. **Girdi Doğrulama (Hafta 4)**
   - Program, sadece 0 ile 100 arasında geçerli notlar kabul etmelidir. Geçersiz bir not girilirse, kullanıcıya tekrar giriş yapması için uyarı verin.
   - Öğrencinin numarasının pozitif bir tam sayı olduğundan emin olun.

#### 4. **Birden Fazla Öğrenci ve Döngüler (Hafta 6, 7)**
   - Program, birden fazla öğrenci (en fazla 5) bilgilerini işleyebilmelidir. Her öğrenci için bir **for döngüsü** kullanarak verileri işleyin.
   - Öğrencilerin bilgilerini (isim, numara, notlar) bir **dizi** kullanarak saklayın.
   - Tüm öğrenciler işlendiğinde, her öğrencinin adı, numarası, ortalama notu ve harf notunu içeren bir özet yazdırın.

#### 5. **İsteğe Bağlı: İstatistikler (Hafta 7)**
   - Ek bir zorluk olarak, tüm öğrenciler girildikten sonra şu istatistikleri hesaplayın ve yazdırın:
     - **En yüksek ortalama nota** sahip öğrenci.
     - **Sınıf ortalaması** (tüm öğrencilerin ortalama notlarının ortalaması).
     - Örnek çıktı:
       ```
       Sınıf Ortalaması: 82.4
       En Yüksek Not: Doğa Çöl, 90.3 ile
       ```

---

### **Uygulama Notları:**

- **Veri türleri:** İsimler için `char[]`, numaralar için `int`, notlar ve ortalamalar için `float` kullanın.
- **Koşullu ifadeler:** Harf notlarını atamak için `if-else` veya `switch-case` yapıları kullanın.
- **Döngüler:** Birden fazla öğrenci için giriş almak amacıyla `for` veya `while` döngüleri kullanın.
- **Diziler:** Notları ve öğrenci bilgilerini saklamak için diziler kullanın.

---

### **Tam Program Etkileşimi Örneği:**

```
Öğrenci sayısını girin (en fazla 5): 3

Öğrencinin ismini girin: Alice Smith
Öğrencinin numarasını girin: 67890
Matematik notunu girin: 95.0
Fen notunu girin: 88.5
Edebiyat notunu girin: 92.0

Öğrencinin ismini girin: Bob Brown
Öğrencinin numarasını girin: 12346
Matematik notunu girin: 72.0
Fen notunu girin: 80.0
Edebiyat notunu girin: 65.5

Öğrencinin ismini girin: Carol White
Öğrencinin numarasını girin: 54321
Matematik notunu girin: 60.0
Fen notunu girin: 55.0
Edebiyat notunu girin: 58.0

Sonuçlar:
Alice Smith (Numara: 67890) - Ortalama: 91.8, Not: A
Bob Brown (Numara: 12346) - Ortalama: 72.5, Not: C
Carol White (Numara: 54321) - Ortalama: 57.7, Not: F

Sınıf Ortalaması: 74.0
En Yüksek Not: Alice Smith, 91.8 ile
```

---

### **Değerlendirme Kriterleri:**

- **Doğruluk**: Program beklenen şekilde çalışıyor mu ve tüm gereksinimleri karşılıyor mu?
- **Kod yapısı**: Kod düzenli ve okunabilir mi? Fonksiyonlar uygun şekilde kullanılmış mı?
- **Girdi doğrulama**: Program hatalı girdileri düzgün bir şekilde yönetiyor mu?
- **Verimlilik**: Program gereksiz hesaplamalardan kaçınıyor ve belleği verimli kullanıyor mu?
