# QA Portfolio — Артём Проскурнин

> Репозиторий содержит тестовую документацию и артефакты ручного тестирования,  
> подготовленные в рамках портфолио QA Engineer.

---

## 🎯 Объект тестирования

**[Reqres.in](https://reqres.in/)** — публичный REST API для тестирования.  
Имитирует реальный бэкенд: пользователи, авторизация, CRUD-операции.

Выбран как репрезентативный пример REST API с документацией, аналогичной Swagger/OpenAPI — что соответствует реальному рабочему опыту.

---

## 📁 Структура репозитория

```
qa-portfolio/
├── test-plan/
│   └── test-plan.md              # Тест-план проекта
├── test-cases/
│   ├── api/
│   │   └── api-test-cases.md     # Тест-кейсы для REST API
│   └── web/
│       └── web-test-cases.md     # Тест-кейсы для Web UI
├── checklists/
│   ├── api-checklist.md          # Чек-лист тестирования API
│   └── regression-checklist.md   # Регрессионный чек-лист
├── bug-reports/
│   └── bug-reports.md            # Примеры баг-репортов
├── sql/
│   └── test-queries.sql          # SQL-запросы для валидации данных
└── postman/
    └── README.md                 # Описание Postman-коллекции
```

---

## 🛠 Стек и инструменты

| Инструмент | Применение |
|---|---|
| **Postman / Insomnia** | Тестирование REST API |
| **Swagger / OpenAPI** | Чтение и анализ документации |
| **Jira** | Баг-трекинг, тест-менеджмент |
| **SQL / PostgreSQL** | Валидация данных на уровне БД |
| **DevTools** | Анализ HTTP-запросов, логи сети |
| **Kibana** | Анализ логов микросервисов |
| **TestRail / Jira Zephyr** | Ведение тестовой документации |

---

## 📊 Покрытие

| Модуль | Тест-кейсов | Покрытие |
|---|---|---|
| Users API (GET/POST/PUT/DELETE) | 18 | ~95% |
| Auth API (Login/Register) | 10 | ~95% |
| Web UI (формы, навигация) | 12 | ~90% |
| **Итого** | **40** | |

---

## 🐛 Найденные дефекты

В ходе тестирования выявлено **6 дефектов**, из них:
- 🔴 Критических — 1
- 🟠 Высоких — 2
- 🟡 Средних — 2
- 🟢 Низких — 1

Подробнее: [bug-reports/bug-reports.md](./bug-reports/bug-reports.md)

---

## 📬 Контакты

**Артём Проскурнин** — QA Engineer  
📧 rnifik@gmail.com  
💬 Telegram: [@whouwarrior](https://t.me/whouwarrior)  
🔗 [Резюме на HH.ru]([#](https://hh.ru/resume/1f850d3eff1087a7310039ed1f4f5a74364b44))
