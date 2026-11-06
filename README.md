# -SSH-

## Ход работы:

## 1. Установка SSH-клиента и генерация ключевой пары
### Проверка наличия и работы SSH-клиента в системе:
sudo systemctl status ssh
### Генерация новой пары ключей:
ssh-keygen -t ed25519
### Создание пароля для приватного ключа.
### Проверка сохранения публичного ключа:
cat ~/.ssh/id_ed25519.pub

## 2. Добавление публичного ключа в аккаунт GitHub
profile -> settings -> SSH and GPG keys -> New SSH key -> Title, key -> add SSH key
<img width="907" height="477" alt="ZUPZEoo-Ng455bdBn1oirU6kS9_bRqAJ43tCfh-6Em6NqRohcBYg1QuDXtQCWDYgSpY1gzjdK625HObruFMEu5Oe" src="https://github.com/user-attachments/assets/3bdde0f7-c724-4dde-b73b-e0dad00e4959" />

## 3. Проверка SSH-подключения к GitHub
