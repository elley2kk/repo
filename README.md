# CSV Reader на GitHub Pages

Простой одностраничный web-визуализатор CSV-файлов:  
загружает файл с диска **или** через *drag & drop*,  
показывает его в настраиваемой таблице, а все изменения
(масштаб, ширина/видимость столбцов, последний файл) сохраняет в `localStorage`.


---

## ⚙️ Возможности

| Функция | Описание |
|---------|----------|
| Загрузка CSV | `<input type="file">` + Drag & Drop в область «📥 Перетащи…» |
| Масштаб | Ползунок `0 % – 100 %`, значение хранится между сессиями |
| Ширина столбцов | Тянем правый край ячейки заголовка (работает благодаря `table-layout: fixed`) |
| Видимость столбцов | Чек-боксы под заголовком; состояние сохраняется |
| Автосохранение | Содержимое CSV, масштаб, ширина и видимость → `localStorage` |
| Кнопка «Очистить всё» | Полный сброс `localStorage` и перезагрузка страницы |

---

## 🚀 Быстрый старт

```bash
# 1. Склонируйте репозиторий
git clone https://github.com/<username>/<repo>.git
cd <repo>

# 2. Добавьте/замените свои CSV файлы или начните сразу
# 3. Опубликуйте ветку `main` (или `docs`) в GitHub Pages
