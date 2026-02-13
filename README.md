# Netology_K8S_2.4 (Моисеенко А.Н.)
## Задание 1. Подготовить Helm-чарт для приложения
- Необходимо упаковать приложение в чарт для деплоя в разные окружения.
- Каждый компонент приложения деплоится отдельным deployment’ом или statefulset’ом.
- В переменных чарта измените образ приложения для изменения версии.
## Задание 2. Запустить две версии в разных неймспейсах
- Подготовив чарт, необходимо его проверить. Запуститe несколько копий приложения.
Создание namespace app1
<img width="589" height="35" alt="image" src="https://github.com/user-attachments/assets/c1f1a649-e7e0-4f17-b0b6-565ef33568ea" />
Устанавка первой версии (1.0.0) в namespace app1
<img width="976" height="141" alt="image" src="https://github.com/user-attachments/assets/2e9e0fb4-7ce5-45b0-a072-11fc267fc419" />
Создание namespace app2
<img width="611" height="37" alt="image" src="https://github.com/user-attachments/assets/03d49b96-c76b-47c3-9e28-0444b43e7697" />

- Одну версию в namespace=app1, вторую версию в том же неймспейсе, третью версию в namespace=app2.
- Продемонстрируйте результат.
