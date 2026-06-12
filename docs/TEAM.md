# Участники проекта «Пилюля»

## Синкин Г.А. — Team Lead & Android-разработчик

**Вклад в проект:**

- Архитектура приложения (Room DB, слои data/ui/notif)
- Система навигации (Navigation Compose, bottom bar)
- Напоминания: AlarmManager, ReminderScheduler, ReminderReceiver
- Фоновые задачи: WorkManager, BootReceiver
- Настройка Gradle, версионирование зависимостей

## Кудрявцева К.А. — UI/UX-дизайнер

**Вклад в проект:**

- Дизайн всех экранов в Material 3 (светлая и темная темы)
- Верстка Compose UI: HomeScreen, MedicationListScreen, MedicationEditScreen, HistoryScreen
- Редактор лекарства с динамическими формами и day-picker
- Анимации переходов и состояний
- Мокапы в Figma, экспорт в SVG и PNG

## Ковалев Д.Г. — Разработчик слоя данных (Room/Repo)

**Вклад в проект:**

- Проектирование схемы БД: Medication, ScheduleEntry, IntakeLog
- Реализация DAO: MedicationDao, ScheduleDao, IntakeLogDao
- MedicationRepository — бизнес-логика приема/пропуска/откладывания
- Расчет adherence-метрик за 30 дней
- Flow-запросы для реактивного обновления UI

## Мартынов К.А. — Тестировщик (QA)

**Вклад в проект:**

- Полный цикл тестирования: юнит-тесты, интеграционные сценарии
- Проверка граничных случаев (пустая БД, отказ в разрешениях)
- Тестирование восстановления будильников после перезагрузки
- Обработка permissions (POST_NOTIFICATIONS, SCHEDULE_EXACT_ALARM)
- Отладка adherence-расчетов и day-picker

## Никифорова А.А. — Медийный менеджер

**Вклад в проект:**

- Подготовка проектной документации по ГОСТ
- Оформление маркдаун-документов (README, TEAM, JOURNAL, RESOURCES)
- Создание и верстка лендинга проекта
- Подготовка презентации и отчета по практике
