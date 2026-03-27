<div align="center">
  <img src="assets/banner.png" alt="NASAFIX" width="100%">
  <br><br>
  
  <h1>NasaFIX</h1>
  
  <p><strong>Сервис для управления стратегиями обхода DPI на базе <a href="https://github.com/bol-van/zapret">zapret</a></strong></p>
  <p>Тестируйте, выбирайте и запускайте оптимальную стратегию для вашего провайдера — в один клик.</p>
  <p align="center">
  <a href="https://github.com/Jack-Lat/NasaFIX">
    <img alt="Platform" src="https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?style=for-the-badge&logo=windows&logoColor=white">
  </a>
  <p align="center">
    <a href="https://github.com/Jack-Lat/NasaFIX/releases">
      <img alt="Pre-release" src="https://img.shields.io/badge/release-pre--release-orange?style=for-the-badge">
    </a>
  </p>
  <a href="https://github.com/Jack-Lat/NasaFIX/releases">
    <img alt="Downloads" src="https://img.shields.io/github/downloads/Jack-Lat/NasaFIX/total?style=for-the-badge&color=blue&label=downloads">
  </a>
  <a href="https://github.com/Jack-Lat/NasaFIX/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/badge/license-All%20Rights%20Reserved-grey?style=for-the-badge">
  </a>
</p>

  <a href="#-установка">📥 Скачать</a> ·
  <a href="#-быстрый-старт">⚡ Быстрый старт</a> ·
  <a href="#-возможности">📖 Возможности</a> ·
  <a href="#-частые-вопросы">❓ FAQ</a> ·
  <a href="#-лицензия">📜 Лицензия</a>
</div>

<br>

> [!NOTE]
> 🆕 **Ускорение Telegram Desktop** — [Flowseal/tg-ws-proxy](https://github.com/Flowseal/tg-ws-proxy)  
> 📦 **Альтернатива (без GUI)** — [bol-van/zapret-win-bundle](https://github.com/bol-van/zapret-win-bundle)

<br>

## 🖼️ Интерфейс

<div align="center">

<img src="assets/screenshot-main.png" alt="Главная" width="900">

<details>
  <summary><b>Показать остальные скриншоты</b></summary>
  <br>

  <p align="center">
    <b>Стратегии</b><br>
    Выбор и запуск пресетов обхода
    <br><br>
    <img src="assets/screenshot-strategies.png" alt="Стратегии" width="900">
  </p>

  <br>

  <p align="center">
    <b>Настройки</b><br>
    Конфигурация режимов работы
    <br><br>
    <img src="assets/screenshot-settings.png" alt="Настройки" width="900">
  </p>

  <br>

  <p align="center">
    <b>О программе</b><br>
    Информация, контакты и предупреждения
    <br><br>
    <img src="assets/screenshot-about.png" alt="О программе" width="900">
  </p>
</details>

</div>

<br>

## 📥 Установка

1. **Настройте Secure DNS** (обязательно — без этого обход может не работать)
2. Скачайте установщик со страницы [последнего релиза](https://github.com/Jack-Lat/NasaFIX/releases/latest)
3. Запустите `NasaFix Setup 1.0.0.exe`
4. Готово

### 🔐 Настройка Secure DNS

<details>
<summary><b>Google Chrome</b></summary>
<br>

Настройки → Конфиденциальность и безопасность → Безопасность → **«Использовать безопасный DNS»** → выберите поставщика, отличного от провайдера по умолчанию.
</details>

<details>
<summary><b>Mozilla Firefox</b></summary>
<br>

Настройки → Конфиденциальность и защита → **«Включить DNS через HTTPS»** → Максимальная защита → «Выбрать поставщика» → укажите вручную, например:
`https://dns.google/dns-query`
</details>

<details>
<summary><b>Windows 11 (рекомендуется)</b></summary>
<br>

Параметры → Сеть и Интернет → Wi-Fi / Ethernet → Свойства → Назначение DNS-сервера → Изменить → «Вручную» → IPv4 → DNS: `8.8.8.8` → DNS через HTTPS: **Включено**.
</details>

<br>

## ⚡ Быстрый старт

1. Откройте вкладку **«Тестирование»** в боковой панели
2. Выберите сайт для проверки (Discord, YouTube и т.д.)
3. Выберите BAT-стратегии для тестирования
4. Нажмите **«Начать тестирование»** и дождитесь результатов
5. Нажмите **«Применить и запустить»** на рекомендуемой стратегии

> Также можно перейти на вкладку **«Стратегии»**, выбрать нужную вручную и нажать **«Запустить выбранный»**.

<br>

## 📖 Возможности

### Основные функции

| Функция              | Описание |
|----------------------|---------|
| **Автотест стратегий** | Автоматическая проверка всех BAT-стратегий на работоспособность |
| **Сетевая диагностика** | Проверка доступности discord.com, youtube.com и других сервисов |
| **Автозапуск**         | Установка любой стратегии как Windows-службы |
| **Game Filter**        | Режим для игр (обход UDP/TCP на портах выше 1023) |
| **IPSet Filter**       | Обход сервисов из `ipset-all.txt` |
| **Отправка логов**     | Диагностика и отправка логов для решения проблем |

### Статусы системы

| Статус                    | Значение |
|---------------------------|---------|
| 🟢 Соединение установлено | Система работает |
| ⚫ Неактивно              | Система отключена |
| 🔵 Тестирование           | Идёт проверка стратегий |
| 🔴 Ошибка сервиса         | Требуется перезапуск NasaFIX |

<br>

## 🛡️ Антивирусы

> [!WARNING]
> **WinDivert может вызвать реакцию антивируса.**

WinDivert — это легитимный инструмент для перехвата и фильтрации сетевого трафика (аналог `iptables` + `NFQUEUE` в Linux). Он необходим для работы zapret-стратегий.

Некоторые антивирусы (особенно Kaspersky, Avast, ESET) могут определять его как `Not-a-virus:RiskTool.Multi.WinDivert` или просто `WinDivert`.

**Что делать:**
- Добавить папку с NasaFIX в исключения антивируса (рекомендуется)
- Отключить проверку PUA (Potentially Unwanted Applications)

> [!IMPORTANT]
> Все бинарные файлы в папке `bin` взяты из официального репозитория [bol-van/zapret-win-bundle](https://github.com/bol-van/zapret-win-bundle). Вы можете проверить их по хэшам.

<br>

## ❓ Частые вопросы

<details>
<summary><b>После запуска стратегии general* ничего не происходит</b></summary>
<br>

Убедитесь, что в вкладке **«Тестирование»** статус стал **«Соединение установлено»**.
Если не помогает — напишите в Discord: `Jack_Lat` или Telegram: [@Jack_Lat](https://t.me/Jack_Lat)
</details>

<details>
<summary><b>Не работает Telegram / бесконечное «подключение» в Discord</b></summary>
<br>

1. Перезапустите NasaFIX
2. Обновите сборку, если предлагается
3. При необходимости положите актуальные стратегии в `AppData\Roaming\nasafix\strategies`
</details>

<details>
<summary><b>Обход не работает или перестал работать</b></summary>
<br>

Стратегии со временем могут "выгорать". Попробуйте создать новую стратегию на основе существующей. Документация по параметрам: [zapret readme](https://github.com/bol-van/zapret/blob/master/docs/readme.md#nfqws)
</details>

(остальные вопросы оставил как были, они в целом нормальные)

---

Хочешь, я могу сделать ещё более чистую версию (убрать некоторые детали, улучшить стиль, добавить эмодзи аккуратнее и т.д.). Скажи, в какую сторону править.

Также могу отдельно подготовить улучшенный промпт для баннера.
