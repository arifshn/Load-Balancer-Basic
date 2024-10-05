# Base image olarak Python kullan
FROM python:3.9-slim

# Çalışma dizinini ayarla
WORKDIR /app

# Uygulama dosyalarını container'a kopyala
COPY . .

# Gerekli bağımlılıkları yükle
RUN pip install flask

# Uygulamayı başlat
CMD ["python", "app.py"]

