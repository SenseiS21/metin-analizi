# Türkçe Metin Analiz Uygulaması

Bu uygulama, Türkçe metinleri analiz etmek ve işlemek için geliştirilmiş bir masaüstü uygulamasıdır.

## Özellikler

- Metin analizi
- Metin ilişkilendirme
- Anahtar kelime çıkarma
- Duygu analizi
- Özetleme
- Görselleştirme
- Metin karşılaştırma
- Metin kategorilendirme

## Kurulum

1. Python 3.11.6 veya üzeri sürümü yükleyin
2. Gerekli paketleri yükleyin:
   ```
   pip install -r requirements.txt
   ```
3. spaCy Türkçe dil modelini indirin:
   - [tr_core_news_md-1.0-py3-none-any.whl](https://github.com/explosion/spacy-models/releases/download/tr_core_news_md-3.4.2/tr_core_news_md-3.4.2-py3-none-any.whl) dosyasını indirin
   - İndirilen dosyayı proje dizinine kopyalayın
   - Modeli yükleyin:
     ```
     pip install tr_core_news_md-1.0-py3-none-any.whl
     ```

## Kullanım

Uygulamayı başlatmak için:

```
python main.py
```

## Geliştirici

Anonim Kullanıcı

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## İletişim

Sorularınız veya önerileriniz için lütfen bir issue açın. 