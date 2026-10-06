# Selnikel A.Ş. Katkı ve Geliştirme Rehberi (Contributing Guidelines)

Selnikel dijital projelerine katkı sağladığınız için teşekkür ederiz. Projelerimizin kalitesini, güvenliğini ve sürdürülebilirliğini korumak amacıyla lütfen aşağıdaki iş akışını takip ediniz.

---

## 🌿 Dal (Branch) Stratejisi

Tüm depolarımızda standart Git-Flow veya GitHub-Flow dallanma modeli uygulanır:

* **`main`**: Yalnızca üretim (production) onaylı, test edilmiş ve canlıya hazır kodları barındırır. Doğrudan commit atılamaz.
* **`staging` / `develop`**: Entegrasyon ve canlı öncesi test dalı.
* **Özellik Dalları (`feature/<ozellik-adi>`)**: Yeni özellikler için açılır.
* **Hata Düzeltme Dalları (`fix/<hata-adi>`)**: Hata çözümleri için açılır.

---

## 📝 Commit Mesajı Standartları (Conventional Commits)

Commit mesajlarının net ve izlenebilir olması için şu standart ön ekler kullanılmalıdır:

* `feat:` Yeni bir özellik veya sayfa eklendiğinde (örn: `feat(calc): buhar kazani hesaplayici eklendi`)
* `fix:` Bir hata düzeltildiğinde (örn: `fix(seo): canonical etiket hatasi giderildi`)
* `perf:` Performans veya hız optimizasyonu yapıldığında (örn: `perf(images): webp yukleme hizi artirildi`)
* `refactor:` Kodun yapısı iyileştirildiğinde (davranış değişmeden)
* `docs:` Dokümantasyon veya README güncellemelerinde
* `chore:` Bağımlılık güncellemeleri veya build ayarlarında

---

## 🔍 Pull Request (PR) ve Kod İnceleme Süreci

1. Geliştirmenizi ilgili `feature/` veya `fix/` dalında tamamlayınız.
2. Yerelde testleri ve derlemeyi mutlaka çalıştırınız:
   ```bash
   npm run check
   npm run build
   ```
3. `main` dalına doğru bir Pull Request (PR) açınız.
4. PR açarken otomatik gelen şablonu (açıklama, yapılan testler, SEO kontrolleri) eksiksiz doldurunuz.
5. En az bir yetkili mühendis onayı ve CI/CD derleme testi başarıyla tamamlanmadan kod `main` dalına birleştirilemez.

---

## 🌐 Kalite, SEO ve Güvenlik İlkeleri

* **SEO Bütünlüğü:** Tüm statik ve dinamik sayfalarda `<title>`, meta description, canonical, 5 dilli `hreflang` ve `schema.org` doğrudan HTML kaynağında yer almalıdır.
* **Sıfır Fazla JS:** Sayfaların saf HTML çıktısını bozacak gereksiz istemci taraflı kütüphaneler eklenmemelidir.
* **Mobil Uyumluluk:** Geliştirilen tüm arayüzler masaüstü, tablet ve mobil ekranlarda titizlikle test edilmelidir.
