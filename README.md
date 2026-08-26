# 📑 TapuMasraf PRO // Türkiye Gayrimenkul Alım-Satım & Maliyet Analizörü
> **bGroup // DATEX Tasarım**  
> *Gayrimenkul Alım-Satım Süreçlerinde Tapu Harcı (%4), Kredi Tahsis, SPK Ekspertiz, Komisyon ve Net Nakit Analizini Hesaplayan A4 Baskı Uyumlu PropTech Aracı*

<p align="left">
  <a href="https://tapumasraf-hesaplayici.vercel.app/"><img src="https://img.shields.io/badge/Canlı%20Demo-Vercel-10b981?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel Canlı Demo"></a>
  <img src="https://img.shields.io/badge/Ecosystem-bGroup-0f172a?style=for-the-badge" alt="bGroup">
  <img src="https://img.shields.io/badge/Design-DATEX%20Tasarım-2563eb?style=for-the-badge" alt="DATEX Tasarım">
  <img src="https://img.shields.io/badge/Compliance-TR%20Mevzuatı-059669?style=for-the-badge" alt="Mevzuat">
  <img src="https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge" alt="License">
</p>

---

## 📌 Proje Özeti

**TapuMasraf PRO**, Türkiye gayrimenkul sektöründeki alım-satım işlemlerinde tarafların karşılaştığı tüm yasal ve finansal maliyetleri kuruşu kuruşuna şeffaflaştıran **sunucusuz (Serverless & Client-Side)** bir PropTech ve FinTech hesaplama motorudur.

492 Sayılı Harçlar Kanunu, Taşınmaz Ticareti Hakkında Yönetmelik ve 6502 Sayılı Tüketicinin Korunması Hakkında Kanun parametrelerine tam uyumlu olarak; gerçek satış bedeli ile tapu beyan bedeli ayrımı yapar, banka masraflarını modeller ve alıcının ihtiyaç duyduğu toplam nakit ile satıcının eline geçecek net tutarı anlık raporlar.

---

## ✨ Öne Çıkan Özellikler

* 🏠 **Gerçek Satış & Tapu Beyan Ayrımı:** Tapu harcını beyan üzerinden (%2 Alıcı + %2 Satıcı), danışmanlık hizmet bedelini ise gerçek satış bedeli üzerinden ayrı ayrı hesaplama.
* 🏛️ **Döner Sermaye Paylaşımı:** İlçe bazlı döner sermaye bedelini alıcı, satıcı veya eşit paylaşımlı olarak dağıtma.
* 💳 **Kredi & Banka Maliyet Motoru:** 6502 sayılı kanun uyarınca kredi anaparasının binde 5'i (0.5%) yasal kredi tahsis ücreti, ipotek tesis harcı ve SPK lisanslı ekspertiz gideri dökümü.
* 🛡️ **Sigorta & Yan Masraflar:** DASK, Konut Sigortası, noter vekaletnameleri ve belediye rayiç/vergi kapanış giderlerini sürece dahil etme.
* 💰 **Net Nakit & Kazanç Analizi:**
  * **Alıcı İçin:** Peşinat + Tüm Resmi Masraflar = Toplam Nakit İhtiyacı.
  * **Satıcı İçin:** Satış Bedeli - Tüm Giderler = Eline Geçecek Net Tutar.
* 🖨️ **A4 Resmi Rapor & PDF Baskı:** `@media print` kurallarıyla optimize edilmiş; kontrol butonlarını gizleyen ve doğrudan müşteriye takdim edilebilir formatta temiz A4 maliyet belgesi.
* 📲 **WhatsApp Finansal Dökümü:** Hesaplanan tüm kalemleri tek tuşla formatlı WhatsApp mesaj taslağına dönüştürme.

---

## 🛠️ Teknoloji Yığını

* **Arayüz / Tasarım:** Mobile-First Responsive HTML5, Tailwind CSS CDN, Lucide Icons
* **Baskı Mimarisi:** Print CSS (`@media print`, sayfa kesme optimizasyonu)
* **Hesaplama Motoru:** Vanilla ES6+ JavaScript (`Calculator` sınıfı)
* **Dağıtım / Edge:** Vercel Edge Network

---

## 🚀 Yerel Kurulum ve Çalıştırma

```bash
# Repoyu klonlayın
git clone [https://github.com/batuhanbayatli/tapumasraf-hesaplayici.git](https://github.com/batuhanbayatli/tapumasraf-hesaplayici.git)

# Proje dizinine geçin
cd tapumasraf-hesaplayici

# index.html dosyasını tarayıcınızda açın veya canlı demoyu ziyaret edin:
# [https://tapumasraf-hesaplayici.vercel.app/](https://tapumasraf-hesaplayici.vercel.app/)
