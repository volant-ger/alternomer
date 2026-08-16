# AlterNomer

**Второй номер. Сейчас.** — бесплатное приложение для Windows: временный телефонный номер и получение SMS-кодов без сим-карты и регистрации.

A second number, right now. — free Windows app: a temporary phone number and SMS codes without a SIM card or registration.

## Скачать / Download

- **Windows (.exe):** [AlterNomer.exe](release/AlterNomer.exe) (SHA256: `c261c5223b8dbe82d40d5f482bc6aeb917593492e5552dab5f02091ec2f6aac2`)
- **Microsoft Store:** *ссылка появится после публикации*
- Обновления проверяются автоматически при каждом запуске (см. [манифест](release/alter-nomer-update.json)).

## Возможности

- Временный номер от нескольких бесплатных сервисов (резерв и ротация при сбоях)
- Получение и извлечение SMS-кодов одной кнопкой
- Без регистрации, данные хранятся только локально
- Русский / English интерфейс
- CLI-режим: `python freecatch.py`

## Политика конфиденциальности

[privacy-policy.md](privacy-policy.md)

## Описание для магазинов

[Store_description.md](Store_description.md) · [Отчёт WACK](AlterNomer_WACK_report.xml)

## Сборка

- Python 3.12, только стандартная библиотека (tkinter GUI)
- Упаковка: PyInstaller onefile (прямой .exe), MSIX (Microsoft Store)
- Данные: `%LOCALAPPDATA%\AlterNomer\` (config.json, monetization.log, update.log)

## Релизы

[Releases](https://github.com/volant-ger/alternomer/releases) — история версий и артефакты.