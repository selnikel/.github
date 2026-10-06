# Selnikel A.Ş. Güvenlik Politikası (Security Policy)

Selnikel Isı, Enerji ve Hava Teknikleri A.Ş. olarak, dijital altyapımızın, endüstriyel mühendislik araçlarımızın ve kurumsal web platformlarımızın güvenliğini en üst düzeyde tutmayı taahhüt ediyoruz.

---

## 🛡️ Desteklenen Sürümler

Aşağıdaki aktif dallar ve canlı platform sürümleri güvenlik güncellemeleri kapsamında takip edilmektedir:

| Proje / Sürüm | Durum | Güvenlik Desteği |
| :--- | :--- | :--- |
| `selnikel-astro` (`main`) | Canlı / Üretim (Production) | :white_check_mark: Tam Destek |
| `selnikel-nextjs` | Arşiv / Referans | :warning: Yalnızca Kritik Yamalar |
| Gelecek CMS / API Servisleri | Geliştirme | :white_check_mark: Tam Destek |

---

## 🚨 Güvenlik Açığı Bildirimi (Reporting a Vulnerability)

Selnikel dijital sistemlerinde veya kaynak kodlarında potansiyel bir güvenlik zafiyeti tespit ettiyseniz, lütfen bunu **herkese açık (public) Issue olarak paylaşmayınız**.

Zafiyetleri sorumlu bildirim (Responsible Disclosure) ilkeleri doğrultusunda şu kanallardan iletmenizi rica ederiz:

1. **GitHub Security Advisories (Önerilen):**  
   İlgili deponun **Security** sekmesine giderek **"Report a vulnerability"** butonu üzerinden gizli güvenlik bildirimi açabilirsiniz.
   
2. **Doğrudan Kurumsal İletişim:**  
   * **E-posta:** [selnikel@selnikel.com.tr](mailto:selnikel@selnikel.com.tr)  
   * **Konu Başlığı:** `[GÜVENLİK BİLDİRİMİ] - Proje Adı / Modül`

Lütfen bildiriminizde şu ayrıntılara yer veriniz:
* Açığın türü ve potansiyel etki derecesi
* Yeniden oluşturma (reproduce) adımları veya kavram kanıtı (PoC)
* Varsa çözüm veya yama önerisi

---

## ⏱️ Müdahale ve Değerlendirme Süreci

* **İlk Yanıt:** Bildiriminiz tarafımıza ulaştıktan sonra en geç **24-48 saat** içerisinde incelemeye alınır ve alındı teyidi verilir.
* **Doğrulama ve Çözüm:** Zafiyet doğrulandıktan sonra aciliyet seviyesine göre önceliklendirilir, gerekli yama hazırlanarak test edilir.
* **Canlıya Alma & Bilgilendirme:** Düzeltme üretim ortamına alındıktan sonra bildirim sahibine teşekkür edilerek süreç kapatılır.

Selnikel'in dijital güvenliğine katkı sağlayan tüm araştırmacılara ve mühendislerimize teşekkür ederiz.
