# Base image olarak Python kullandım
FROM python:3.9-slim

# Çalışma dizinini ayarladım
WORKDIR /app

# Uygulama dosyalarını container'a kopyaladım
COPY . .

# Gerekli bağımlılıkları yükledim
RUN pip install flask

# Uygulamayı başlattım
CMD ["python", "app.py"]

