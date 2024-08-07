# Задание 1

Создать образ
   ```bash
   docker build . --tag nginx-hw
   ```
Запустить контейнер
   ```bash
   docker run -d -p 5000:80 nginx-hw
   ```

# Задание 2

Создать образ
   ```bash
   docker build . --tag django-hw
   ```
Запустить контейнер
   ```bash
   docker run -d -p 5000:6000 django-hw
   ```
