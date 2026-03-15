# Türkiye Hava Durumu & Sayısal Yöntemler Projesi

## Proje Özeti
Bu proje, web tabanlı bir hava durumu uygulaması ile Python tabanlı sayısal yöntemler analiz modülünü birleştirir. Kullanıcılar Türkiye'nin 81 ilinden birini seçerek güncel hava durumu verilerini görebilir, geçmiş sıcaklık değişimlerini grafikle inceleyebilir ve bu verileri Python ile sayısal analizlere tabi tutabilir.

## Klasör Yapısı
- `frontend/`: Web arayüzü (HTML, CSS, JS)
- `backend/`: Python ile sayısal yöntemler modülleri
- `data/`: Hava durumu ve analiz verileri (JSON/CSV)
- `main.py`: Python modüllerini çalıştıran ana script

## Kurulum & Çalıştırma
1. `frontend/` klasöründeki `index.html` dosyasını tarayıcıda açın.
2. OpenWeatherMap API anahtarınızı `frontend/weather.js` dosyasına ekleyin.
3. Hava durumu verileri `data/` klasörüne kaydedilebilir ve Python analizlerinde kullanılabilir.
4. Python modüllerini çalıştırmak için:
   ```bash
   python main.py
   ```

## Modüller ve Açıklamalar
Her Python modülü, ilgili sayısal yöntemi örneklerle, grafiklerle ve açıklamalarla sunar. Detaylar için `backend/` klasöründeki dosyalara bakınız.

## Numerical Methods Konuları
1. Error Analysis and Floating-Point Precision
2. Root Finding (Bisection, Newton-Raphson, Secant)
3. Interpolation Techniques (Lineer, Spline)
4. Numerical Differentiation
5. Numerical Integration
6. Solving Linear Systems
7. LU Decomposition
8. Optimization Techniques
9. ODE Solving
10. Performance & Error Handling
11. Visualization & Documentation
12. Comparative Analysis and Case Study

Her modül, örneklerle ve yorum satırlarıyla detaylı açıklanmıştır.
