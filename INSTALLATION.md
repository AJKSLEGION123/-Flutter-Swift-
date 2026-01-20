# Инструкция по установке

## Вариант 1: Установка Flutter (рекомендуется)

### Шаги установки:

1. **Скачайте Flutter SDK:**
   - Перейдите на https://flutter.dev/docs/get-started/install/windows
   - Скачайте последнюю стабильную версию Flutter SDK
   - Распакуйте архив в папку (например, `C:\src\flutter`)

2. **Добавьте Flutter в PATH:**
   - Откройте "Переменные среды" (Environment Variables)
   - Добавьте путь к `flutter\bin` в переменную PATH
   - Например: `C:\src\flutter\bin`

3. **Проверьте установку:**
   ```bash
   flutter doctor
   ```

4. **Установите зависимости проекта:**
   ```bash
   flutter pub get
   ```

5. **Запустите приложение:**
   ```bash
   flutter run
   ```

## Вариант 2: Веб-версия (без установки)

Если не хотите устанавливать Flutter, можно запустить веб-версию приложения.
См. папку `web_version/` для HTML/JavaScript версии.

## Вариант 3: Swift (требует macOS или Linux)

Swift на Windows требует дополнительной настройки. Если у вас есть доступ к macOS, можно создать iOS/macOS версию.
