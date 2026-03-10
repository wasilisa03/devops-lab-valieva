Создала простое Flask-приложение, написала Dockerfile, настроила репозитории на GitHub и Docker Hub. Разработала CI/CD пайплайн с GitHub Actions, который автоматически собирает образ и публикует его в Docker Hub при каждом пуше в main ветку. Добавила секреты для безопасного хранения учетных данных.
Больше всего проблем возникло с авторизацией в Docker Hub — долго не могла понять разницу между токеном и паролем, а также между правами Read-only и Read & Write. 
Большую часть времени потратила на отладку ошибок авторизации и понимание структуры GitHub Actions.

<img width="1032" height="870" alt="image" src="https://github.com/user-attachments/assets/c7a43db0-1e27-4ee3-bdf9-d8b8214bbab9" />
<img width="1430" height="272" alt="image" src="https://github.com/user-attachments/assets/089b64b3-f477-40f3-86cd-5b59fba4c681" /> 
<img width="1460" height="120" alt="image" src="https://github.com/user-attachments/assets/ed515d7d-eced-41d2-9800-903189f98ad0" />
