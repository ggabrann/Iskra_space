# Iskra_space

Живой шаблон на базе Very Good Core, настроенный под Искру.

## Требования
- Flutter (стабильный канал)
- Dart SDK поставляется вместе с Flutter
- Любой поддерживаемый эмулятор или браузер для запуска

## Быстрый старт
```bash
flutter pub get
flutter run -d chrome # или другую доступную платформу
```

## Проверки качества
```bash
dart format --output=none --set-exit-if-changed .
flutter analyze
flutter test --coverage
```

## CI
Проект использует GitHub Actions (`.github/workflows/flutter-ci.yml`) для проверки форматирования, анализа и тестов с покрытием. Артефакт `coverage/lcov.info` загружается после каждого прогона.

## Структура
- `lib/` — исходный код приложения.
- `test/` — модульные тесты.
- `web/`, `android/`, `ios/` и другие платформенные директории — оболочки для сборок под конкретные цели.

## Полезные ссылки
- [Документация Flutter](https://docs.flutter.dev/)
- [Very Good Core](https://github.com/VGVentures/very_good_cli/tree/main/packages/very_good_core)
