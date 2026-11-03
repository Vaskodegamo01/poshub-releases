# POSHub — касса и учёт для малого бизнеса

**POSHub** — семейство приложений для касс и учёта в малом бизнесе: бильярдные клубы,
кафе, фастфуд и магазины. Один продукт ставится на один компьютер, работает без интернета
и не требует администрирования.

Разработчик — **R&D Code** · [rndcode.com](https://rndcode.com)
Сайт продукта — [poshub.club](https://poshub.club)
Коммерческие предложения — **sales@poshub.club**

## Приложения

| Приложение | Для кого | Что внутри |
|---|---|---|
| **Billiards Master** | бильярдные клубы | столы и время, свет (Modbus), брони, лист ожидания, бар, членство, касса, отчёты |
| **Food Master** | кафе и рестораны с официантом | зал, заказы, кухня (KDS), подача, выдача, счёт, разделение счёта |
| **Food Master Counter** | фастфуд, ларьки, кофейни у кассы | быстрая продажа, предоплата, «оплатить и отправить», KDS |
| **Retail Master** | магазины | штрихкоды и сканер, весовой товар, каталог, партии и сроки годности, сдача |

## Ключевые принципы

- **Деньги не теряются.** Единственный писатель — касса; все операции в транзакциях, с аудитом и историей.
- **Работает офлайн.** Нет интернета — касса продолжает работать, данные остаются локально.
- **Простые настройки.** Без админа: установил, открыл смену, продал.
- **Локальная сеть.** Экран кухни на телевизоре, панель менеджера, приложение официанта и QR-меню — по локальной сети, без облака.
- **Аналитика.** Выручка, чеки, средний чек, топ товаров, загрузка по часам, «требуется внимание».
- **Диагностика.** Один файл с логами и состоянием — для поддержки.

## Скачивание

Готовые сборки — в разделе **[Releases](../../releases)** этого репозитория.

- **Windows 10/11** — установщик `.exe` (NSIS).
- **Linux** — `.AppImage` (Ubuntu 24.04+ или совместимый дистрибутив, glibc ≥ 2.39).

### Установка

**Windows.** Запустите `.exe`. Если Windows покажет SmartScreen — «Подробнее» → «Выполнить в любом случае».

**Linux.** Скачайте `.AppImage`, выполните `chmod +x <файл>.AppImage` и запустите. Для печати нужен CUPS.

## Лицензия

Программа коммерческая, лицензия привязывается к оборудованию и выдаётся на клуб/магазин.
Активация — в разделе «Лицензия» внутри приложения. Пробный период — по запросу.

---

# POSHub — POS and bookkeeping for small business (EN)

**POSHub** is a family of point-of-sale and bookkeeping apps for small businesses:
billiard clubs, cafés, fast food and retail stores. One app per PC, works offline,
no system administration required.

Developer — **R&D Code** · [rndcode.com](https://rndcode.com)
Product site — [poshub.club](https://poshub.club)
Commercial offers — **sales@poshub.club**

## Apps

| App | For | Includes |
|---|---|---|
| **Billiards Master** | billiard clubs | tables and time, table lights (Modbus), bookings, waiting list, bar, membership, cash desk, reports |
| **Food Master** | cafés and restaurants with waiters | hall, orders, kitchen display, serving, pickup, bill, split bill |
| **Food Master Counter** | fast food, kiosks, coffee shops | quick sale, prepayment, “pay & send”, kitchen display |
| **Retail Master** | stores | barcodes and scanner, weighted goods, catalog, batches and expiry dates, change |

## Principles

- **Money safety.** The cash desk is the only writer; every operation is transactional, audited and kept in history.
- **Offline first.** No internet — the cash desk keeps working, data stays local.
- **Simple setup.** No sysadmin: install, open a shift, sell.
- **Local network.** Kitchen display on a TV, manager panel, waiter app and QR menu over LAN — no cloud.
- **Analytics.** Revenue, receipts, average check, top items, hourly load, “needs attention”.
- **Diagnostics.** One archive with logs and state for support.

## Download

Ready builds are in the **[Releases](../../releases)** section of this repository.

- **Windows 10/11** — `.exe` installer (NSIS).
- **Linux** — `.AppImage` (Ubuntu 24.04+ or compatible, glibc ≥ 2.39).

### Install

**Windows.** Run the `.exe`. If SmartScreen appears — “More info” → “Run anyway”.

**Linux.** Download the `.AppImage`, run `chmod +x <file>.AppImage` and start it. Printing requires CUPS.

## License

Commercial software; the license is bound to hardware and issued per club/store.
Activate it in the “License” section inside the app. Trial period — on request.
