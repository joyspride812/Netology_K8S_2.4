# Netology_K8S_2.4 (Моисеенко А.Н.)
## Задание 1. Подготовить Helm-чарт для приложения
- Необходимо упаковать приложение в чарт для деплоя в разные окружения.
- Каждый компонент приложения деплоится отдельным deployment’ом или statefulset’ом.
- В переменных чарта измените образ приложения для изменения версии.
## Задание 2. Запустить две версии в разных неймспейсах
- Подготовив чарт, необходимо его проверить. Запуститe несколько копий приложения.
Создание namespace app1
<img width="589" height="35" alt="image" src="https://github.com/user-attachments/assets/c1f1a649-e7e0-4f17-b0b6-565ef33568ea" />
Устанавка release1 в namespace app1
<img width="805" height="139" alt="image" src="https://github.com/user-attachments/assets/9dcbfb7d-fb6c-40b8-8e61-5deed2bf2ec1" />

Создание namespace app2
<img width="611" height="37" alt="image" src="https://github.com/user-attachments/assets/03d49b96-c76b-47c3-9e28-0444b43e7697" />
Устанавка release2 в namespace app1
<img width="559" height="193" alt="image" src="https://github.com/user-attachments/assets/8e1198a0-f671-4c54-a7da-4d8149d11fb5" />
Устанавка release3 в namespace app2
 <img width="635" height="144" alt="image" src="https://github.com/user-attachments/assets/a2190b6e-20c2-4e8e-a3d2-b0a982e5313d" />

- Одну версию в namespace=app1, вторую версию в том же неймспейсе, третью версию в namespace=app2.
- Продемонстрируйте результат.
