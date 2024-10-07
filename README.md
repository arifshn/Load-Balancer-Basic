# Load Balancer Projesi

Bu projede, Load Balancer'ın nasıl çalıştığını anlamak amacıyla basit bir Python uygulaması geliştirdim. 

## Proje Hakkında

Proje, temel bir Load Balancer mantığını göstermek için tasarlanmıştır. Docker kullanarak uygulamayı konteyner haline getirip çalıştırdım.

## Adımlar

1. **Python Uygulaması Oluşturma**:
   Basit bir Python uygulaması geliştirerek Load Balancer'ın işleyişini anlamaya çalıştım.

2. **Docker ile İmaj Oluşturma**:
   Uygulamayı Docker ile imaj haline getirdim. `Dockerfile` oluşturup gerekli yapılandırmaları yaptım.

3. **Konteyner Oluşturma ve Çalıştırma**:
   Oluşturduğum Docker imajını kullanarak bir konteyner oluşturdum ve çalıştırdım. 

4. **Çalışma Kontrolü**:
   Konteyneri çalıştırdıktan sonra , uygulamanın Docker Hub üzerinde çalıştığını doğruladım. Ayrıca, localhost ile deneme yaparak ekran çıktısını gözlemledim.

5. **Load Balancer Mantığını Anlama**:
   Localhost üzerindeki web sayfasını yenileyerek Load Balancer'ın çalışma mantığını kavradım. Uygulama, istekleri farklı sunuculara yönlendirerek yük dengeleme işlevini gerçekleştirdi.

## Sonuç

Bu proje, Load Balancer'ın temel işleyişini anlamama yardımcı oldu. Docker ile uygulamayı container ortamında çalıştırarak, yük dengeleme sürecinin nasıl gerçekleştiğini deneyimledim.
