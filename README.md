# 🎉 Мальчишник · Нижний Новгород · 11–14 июня 2026

Лендинг для выбора жилья на мальчишник.

## 🚀 Публикация через GitHub Pages

### Шаг 1 — Создай репозиторий
1. Зайди на [github.com](https://github.com) → **New repository**
2. Название: `bachelor-nn` (или любое другое)
3. Видимость: **Public** *(GitHub Pages бесплатно только для публичных)*
4. Нажми **Create repository**

### Шаг 2 — Загрузи файлы
**Вариант A — через браузер (проще):**
1. В репозитории нажми **Add file → Upload files**
2. Перетащи `index.html` и `README.md`
3. Нажми **Commit changes**

**Вариант B — через терминал:**
```bash
git init
git add .
git commit -m "init"
git branch -M main
git remote add origin https://github.com/ВАШ_ЮЗЕРНЕЙМ/bachelor-nn.git
git push -u origin main
```

### Шаг 3 — Включи GitHub Pages
1. Перейди в репозиторий → **Settings** → **Pages** (левое меню)
2. Source: **Deploy from a branch**
3. Branch: **main** / `/ (root)`
4. Нажми **Save**

### Шаг 4 — Готово 🎉
Через ~1 минуту сайт будет доступен по адресу:
```
https://ВАШ_ЮЗЕРНЕЙМ.github.io/bachelor-nn/
```

---

## 📁 Структура файлов

```
bachelor-nn/
├── index.html   # Весь сайт в одном файле
└── README.md    # Этот файл
```

> Сайт полностью автономный — все стили, скрипты и данные внутри `index.html`. Внешние зависимости: Google Fonts, Chart.js (CDN) и фото с sutochno.ru.
