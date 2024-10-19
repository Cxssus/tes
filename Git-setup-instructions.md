# Шаги для настройки Git и генерации SSH ключа

## 1. Генерация SSH ключа на сервере:
ssh-keygen -t rsa -b 4096 -C "frazibe@gmail.com"
## 2. Получить публичный ключ
cat ~/.ssh/id_rsa.pub
## Настройка автора и email в Git
git config --global user.name "Alexander Sergeev"
git config --global user.email "Frazibe@gmail.com"
## 3. Основные команды для публикации кода в GitHub
git add .
git commit -m "Добавлен файл README"
git push origin ветка
