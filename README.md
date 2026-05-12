# 🌑 InStudy / disto.mveu.ru — Dark Mono

Tampermonkey-скрипт, применяющий монохромную тёмную тему к студенческому порталу [disto.mveu.ru](https://disto.mveu.ru) (InStudy, МВЭУ).

![screenshot](screenshot.png)

## ⚙️ Установка

1. Установите расширение [Tampermonkey](https://www.tampermonkey.net/) для вашего браузера.
2. Откройте **Tampermonkey → Настройки → Утилиты → Импорт из URL** и вставьте ссылку:
   ```
   https://raw.githubusercontent.com/juushimatsu/instudy-mveu-ui-fix-tampermonkey/main/main.js
   ```

## ✨ Возможности

- Монохромная тёмная тема для всего интерфейса портала
- Переключение тёмная / светлая тема кнопкой в шапке (состояние сохраняется в `localStorage`)
- Шрифты **JetBrains Mono** + **Unbounded**
- Lazy-load списка преподавателей
- Фиксы вёрстки: боковое меню, шапка, форма входа, чат, таблицы
- Исправление отображения бейджей и аватаров
- Адаптивные CSS-правки без вмешательства в логику портала

## 🌐 Совместимость

| Браузер | Поддержка |
|---------|-----------|
| Chrome  | ✅        |
| Firefox | ✅        |
| Edge    | ✅        |

Требуется расширение **Tampermonkey**.

## 📝 Лицензия

[Apache License 2.0](LICENSE)
