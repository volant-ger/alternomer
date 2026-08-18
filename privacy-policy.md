# Политика конфиденциальности MiloNumo

*Privacy Policy / Datenschutzerklärung (для Microsoft Partner Center, п. 10.5)*

Дата: 17.08.2026

## RU

MiloNumo — приложение для Windows, которое ищет публично доступные бесплатные
временные номера телефонов, показывает доступные входящие сообщения и
извлекает код подтверждения из полученного SMS для регистрации в онлайн-сервисах.

**Обработка данных полностью локальная.** Номера телефонов и тексты SMS
обрабатываются только на вашем устройстве. Приложение не передаёт их ни
третьим лицам, ни на серверы разработчика.

### Локальные данные

В локальном каталоге приложения `%LOCALAPPDATA%\AlterNomer\` хранятся:

* настройки приложения (`config.json`: язык, таймауты, параметры обновления);
* локальная история поиска и попыток (`intelligence.db`, SQLite): идентификаторы
  номеров, источники, оценки ранжирования, результаты попыток; **тексты SMS и
  коды подтверждения в базе не сохраняются** и отображаются только в журнале
  текущего сеанса;
* локальные журналы: `update.log` (события проверки/применения обновлений),
  `monetization.log` (показы/переходы партнёрских блоков), `routing.log`
  (идентификаторы и оценки выбранных кандидатов).

Ни один из этих файлов не покидает ваше устройство и не отправляется
разработчику.

### Сетевые подключения

* **Публичные сервисы временных номеров.** Для поиска номеров и проверки
  входящих SMS приложение обращается к публичным веб-страницам независимых
  сторонних сервисов (на момент публикации: freeonlinephone.org,
  receivesmsonline.net, receivefreesms.net). Запросы направляются с обычным
  браузерным идентификатором; сбор и обработка данных этими сервисами
  подчиняются их собственным политикам, на которые разработчик MiloNumo не
  влияет.
* **Обновления (только standalone-версия).** Стоящая отдельно (не из Microsoft
  Store) версия проверяет наличие обновлений на GitHub Pages: передаётся только
  текущая версия приложения и запрашивается адрес загрузки. Версия из Microsoft
  Store обновляется через сам Store и сетевых запросов к GitHub Pages не делает.
* **Партнёрские ссылки.** Если в приложении отображается партнёрская
  рекомендация, переход по ней открывает страницу независимого партнёра в
  вашем браузере. С этого момента вы взаимодействуете с третьей стороной на
  её условиях и под её политикой конфиденциальности. Приложение не передаёт
  партнёрам никаких ваших данных, а только открывает его публичный адрес.

### Аналитика и телеметрия

MiloNumo **не использует аналитику и не передаёт телеметрию разработчику**.
Приложение не собирает статистику использования, не содержит сторонних
аналитических SDK и не отправляет события на серверы разработчика.

Приложение не требует учётной записи, не собирает личные данные (ФИО,
адреса, идентификаторы устройств), не запрашивает доступ к контактам, камере
или микрофону, не запускает фоновые службы и не требует прав администратора.

---

## EN

MiloNumo is a Windows app that searches publicly available free temporary phone
numbers, shows incoming messages, and extracts the confirmation code from a
received SMS for sign-ups in online services.

**All processing is local.** Phone numbers and SMS texts are handled only on
your device. The app never transmits them to third parties or to developer
servers.

### Local data

The app's local data directory `%LOCALAPPDATA%\AlterNomer\` stores:

* app settings (`config.json`: language, timeouts, update parameters);
* local search and attempt history (`intelligence.db`, SQLite): number
  identifiers, sources, ranking scores, attempt results; **SMS texts and
  confirmation codes are never stored in the database** and are shown only in
  the current session log;
* local logs: `update.log` (update check/apply events), `monetization.log`
  (partner block impressions/clicks), `routing.log` (candidate identifiers and
  scores).

None of these files leave your device or are sent to the developer.

### Network access

* **Public temporary-number services.** To find numbers and check incoming SMS,
  the app requests public web pages of independent third-party services (at the
  time of publication: freeonlinephone.org, receivesmsonline.net,
  receivefreesms.net). Requests carry a regular browser identifier; data
  collection and processing by those services are governed by their own
  policies, which are outside the control of the MiloNumo developer.
* **Updates (standalone edition only).** The standalone (non-Store) edition
  checks for updates on GitHub Pages: it sends only the current app version and
  requests the download address. The Microsoft Store edition is updated through
  the Store itself and makes no GitHub Pages requests.
* **Partner links.** When a partner recommendation is shown, following it opens
  the independent partner's page in your browser. From that point you interact
  with a third party under its own terms and privacy policy. The app passes no
  personal data to partners; it only opens their public address.

### Analytics and telemetry

MiloNumo **uses no analytics and transmits no telemetry to the developer**. The
app collects no usage statistics, contains no third-party analytics SDKs, and
sends no events to developer servers.

The app requires no account, collects no personal data (names, addresses,
device identifiers), requests no access to contacts, camera, or microphone,
runs no background services, and requires no administrator rights.
