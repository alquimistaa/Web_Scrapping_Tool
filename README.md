# WebScraperGenerator

WebScraperGenerator, verilen bir ana URL üzerinden aynı domaine ait tüm sayfaları otomatik olarak ziyaret eder, sayfalardaki gereksiz HTML etiketlerini temizler ve her sayfanın başlık-paragraf içeriklerini ayrı ayrı `.docx` dosyalarına kaydeder.

## Özellikler

- Verilen ana URL'deki tüm iç bağlantıları (aynı domain altında) toplar
- script, style, nav, footer, header, aside gibi yapıları ve sosyal medya gibi içerikleri temizler
- Sadece p, h1-h5 gibi yapısal metin etiketlerinden içerik toplar
- Her sayfa için bir `.docx` dosyası üretir
- Tüm dosyaları `output_{domain}` adında bir klasöre kaydeder

## Kurulum

```bash
pip install -r requirements.txt

