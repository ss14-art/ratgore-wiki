# Ratgore Wiki

**Описание:**
Этот репозиторий содержит исходники вики для проекта **Ratgore** (модификация **Space Station 14**).

**Лицензия контента:** [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)

---

## 🔧 Быстрый старт

### 1. Клонирование и настройка
```bash
git clone https://github.com/ss14.art/ratgore-wiki.git
cd ratgore-wiki
```

### 2. Установка Mintlify CLI
Требуется для локального предпросмотра изменений:
```bash
npm i -g mint
```

### 3. Локальный предпросмотр
Запустите сервер для проверки правок:
```bash
mint dev
```
Откройте [http://localhost:3000](http://localhost:3000).

---

## 🚀 Развёртывание изменений
Изменения автоматически публикуются на продакшн после пуша в `main`.
**Требования:**
- Установлен [GitHub App от Mintlify](https://dashboard.mintlify.com/settings/organization/github-app).
- Файл `docs.json` в корне репозитория.

---

## ⚠️ Решение проблем
- **Ошибка 404 при локальном запуске?**
  Проверьте наличие `docs.json` в текущей директории.
- **CLI не обновляется?**
  ```bash
  mint update
  ```

---

## 📚 Ресурсы
- [Документация Mintlify](https://mintlify.com/docs)
- [Дашборд Ratgore Wiki](https://dashboard.mintlify.com)