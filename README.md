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
### profile -> settings -> SSH and GPG keys -> New SSH key -> Title, key -> add SSH key
<img width="907" height="477" alt="ZUPZEoo-Ng455bdBn1oirU6kS9_bRqAJ43tCfh-6Em6NqRohcBYg1QuDXtQCWDYgSpY1gzjdK625HObruFMEu5Oe" src="https://github.com/user-attachments/assets/3bdde0f7-c724-4dde-b73b-e0dad00e4959" />

## 3. Проверка SSH-подключения к GitHub
<img width="730" height="157" alt="Screenshot From 2026-11-06 14-52-27" src="https://github.com/user-attachments/assets/79ed5d45-770e-4340-b8e1-fba138d4f881" />


## 4. Работа с репозиторием по SSH
### code -> clone ssh -> git clone git@github.com:kittymef/group_project.git
<img width="734" height="152" alt="Screenshot From 2026-11-06 16-15-00" src="https://github.com/user-attachments/assets/1c4e1ba6-571d-48b5-8f85-b77045d4b1ee" />
<img width="763" height="42" alt="Screenshot From 2026-11-06 16-27-42" src="https://github.com/user-attachments/assets/cc5fb108-2b32-4950-bb6c-ed534d56ec24" />
<img width="705" height="99" alt="Screenshot From 2026-11-06 16-27-18" src="https://github.com/user-attachments/assets/8d47cb97-0189-4d70-a2c9-440ab7a0e55f" />
<img width="765" height="240" alt="Screenshot From 2026-11-06 16-28-00" src="https://github.com/user-attachments/assets/7bfb2ee0-ab67-494d-80c7-9bff27181032" />
