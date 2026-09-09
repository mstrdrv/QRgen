# QRgen — Честный генератор QR-кодов

[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Open Source](https://img.shields.io/badge/open-source-blue.svg)](https://github.com/mstrdrv/QRgen)
[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen.svg)](https://mstrdrv.github.io/QRgen/)

> **Локальный генератор QR-кодов, который работает прямо в браузере. Ничего не отправляется в сеть. Бесплатно. Просто. Честно.**

[🇬🇧 English](#english) | [🇷🇺 Русский](#русский) | [🇩🇪 Deutsch](#deutsch)

---

## 🇷🇺 Русский

### Что это?

**QRgen** — это веб-приложение для создания QR-кодов, которое работает **полностью в вашем браузере**. 

✅ **Никакие данные не отправляются на сервер**  
✅ **Работает без интернета** (после загрузки)  
✅ **Без рекламы и трекинга**  
✅ **Открытый исходный код**  
✅ **Поддержка 5 языков**  

### Возможности

- 📝 **3 строки ввода** — для создания многострочных QR-кодов
- 🎯 **8 готовых шаблонов**:
  - Простой текст
  - URL-адреса
  - Wi-Fi сети
  - vCard (контакты)
  - Координаты (Geo)
  - SMS-сообщения
  - Email
  - Телефонные номера

- 📏 **4 размера** — от 256px до 1600px
- 💾 **3 формата экспорта** — JPG, PNG, WebP
- 🌍 **5 языков** — английский, русский, немецкий, испанский, французский

### Быстрый старт

1. **Откройте** [QRgen онлайн](https://mstrdrv.github.io/QRgen/)
2. **Выберите язык**
3. **Введите текст** или используйте шаблон
4. **Нажмите "Генерировать"**
5. **Скачайте** в нужном формате

### Для разработчиков

```bash
# Клонируйте репозиторий
git clone https://github.com/mstrdrv/QRgen.git
cd QRgen

# Откройте index.html в браузере
open index.html
```

Все необходимые библиотеки загружаются из CDN:
- [qrcode-generator](https://cdn.jsdelivr.net/npm/qrcode-generator@1.4.4/qrcode.js)

### Структура файлов

```
QRgen/
├── index.html      # Основное приложение (HTML + CSS + JS)
├── README.md       # Этот файл
├── readme.txt      # Описание на нескольких языках
├── license.txt     # Лицензия
└── .gitattributes  # Git конфиг
```

### Примеры использования

**Создание QR для Wi-Fi:**
```
Выберите шаблон "Wi‑Fi"
Вставится: WIFI:T:WPA;S:MyNetwork;P:MyPassword;;
Отредактируйте название и пароль
Нажмите "Генерировать"
```

**Создание vCard (контакт):**
```
Выберите шаблон "vCard"
Отредактируйте имя, фамилию и контакты
Нажмите "Генерировать"
```

### Лицензия

MIT License — полностью свободен для использования и модификации

### Контрибьютинг

Нашли баг или хотите добавить фичу? 
- [Откройте Issue](https://github.com/mstrdrv/QRgen/issues)
- [Создайте Pull Request](https://github.com/mstrdrv/QRgen/pulls)

---

## 🇬🇧 English

### What is this?

**QRgen** is a web application for generating QR codes that works **entirely in your browser**.

✅ **No data sent to servers**  
✅ **Works offline** (after loading)  
✅ **No ads or tracking**  
✅ **Open source**  
✅ **5 language support**  

### Features

- 📝 **3 input lines** — for multi-line QR codes
- 🎯 **8 ready-made templates**:
  - Plain text
  - URLs
  - Wi-Fi networks
  - vCard (contacts)
  - Geo coordinates
  - SMS messages
  - Email
  - Phone numbers

- 📏 **4 sizes** — from 256px to 1600px
- 💾 **3 export formats** — JPG, PNG, WebP
- 🌍 **5 languages** — English, Russian, German, Spanish, French

### Quick Start

1. **Open** [QRgen online](https://mstrdrv.github.io/QRgen/)
2. **Select language**
3. **Enter text** or use a template
4. **Click "Generate"**
5. **Download** in your preferred format

### For Developers

```bash
# Clone the repository
git clone https://github.com/mstrdrv/QRgen.git
cd QRgen

# Open index.html in your browser
open index.html
```

All required libraries are loaded from CDN:
- [qrcode-generator](https://cdn.jsdelivr.net/npm/qrcode-generator@1.4.4/qrcode.js)

### License

MIT License — completely free to use and modify

### Contributing

Found a bug or want to add a feature?
- [Open an Issue](https://github.com/mstrdrv/QRgen/issues)
- [Create a Pull Request](https://github.com/mstrdrv/QRgen/pulls)

---

## 🇩🇪 Deutsch

### Was ist das?

**QRgen** ist eine Webanwendung zur Generierung von QR-Codes, die **vollständig in Ihrem Browser** funktioniert.

✅ **Keine Daten an Server gesendet**  
✅ **Funktioniert offline** (nach dem Laden)  
✅ **Keine Werbung oder Verfolgung**  
✅ **Open Source**  
✅ **5-Sprachen-Unterstützung**  

### Funktionen

- 📝 **3 Eingabezeilen** — für mehrzeilige QR-Codes
- 🎯 **8 vorgefertigte Vorlagen**
- 📏 **4 Größen** — von 256px bis 1600px
- 💾 **3 Exportformate** — JPG, PNG, WebP
- 🌍 **5 Sprachen** — Englisch, Russisch, Deutsch, Spanisch, Französisch

---

## 📊 Keywords & SEO

`QR code generator`, `QR-код генератор`, `free QR`, `offline QR`, `browser QR`, `open source`, `privacy`, `no tracking`, `генератор кодов`, `локальный генератор`

---

**Создано с ❤️ для людей, которые ценят приватность и простоту.**

[⬆ К началу](#qrgen--честный-генератор-qr-кодов)
