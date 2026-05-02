# CryptoLiqMap - Real-time Cryptocurrency Liquidation Map

🚀 **Live Site: https://mymdo.github.io/CryptoLiqMap/**

## ✅ Проєкт завершено!

### 📌 Статус
- **GitHub репозиторій:** https://github.com/MYMDO/CryptoLiqMap
- **Live сайт:** https://mymdo.github.io/CryptoLiqMap/
- **Статус:** ✅ Активний, розгорнутий на GitHub Pages

### 🛠️ Технології
- **Pure HTML5** - чистий HTML без залежностей
- **Pure CSS3** - вбудовані стилі (CSS Variables для тем)
- **Pure JavaScript (ES6+)** - жодних бібліотек чи фреймворків
- **Canvas 2D API** - рендеринг heatmap
- **WebSocket API** - пряме піклчення до бірж

### 🎯 Функціональність
✅ **Real-time WebSocket** - Binance, Bybit, OKX (публічні API)
✅ **Live Liquidation Feed** - пряма стрічка ліквідацій
✅ **Canvas Heatmap** - візуалізація кластерів ліквідації
✅ **Statistics Dashboard** - 24h статистика, Long/Short
✅ **Dark/Light Theme** - перемикання тем
✅ **Адаптивний дизайн** - працює на всіх пристроях
✅ **Нульові залежності** - жодних npm пакетів

### 🌐 Як це працює
1. Браузер піклчається напряму до WebSocket API бірж
2. Дані про ліквідації надходять в реальному часі
3. Canvas відмальовує графік (heatmap)
4. Стрічка показує останні події
5. Статистика оновлюється динамічно

### 📦 Підтримувані біржі
| Біржа | WebSocket URL | Статус |
|--------|--------------|--------|
| **Binance** | `wss://fstream.binance.com/stream?streams=!forceOrder@arr` | 🟢 Активний |
| **Bybit** | `wss://stream.bybit.com/v5/public/linear` | 🟢 Активний |
| **OKX** | `wss://ws.okx.com:8443/ws/v5/public` | 🟢 Активний |

### 🚀 Деплой
- Використовується GitHub Pages
- Автоматичне розгортання при push в `main`
- Жодних build tools - просто HTML файл

### 📝 Подальші покращення (опціонально)
- [ ] Додати звукові сповіщення
- [ ] Розширити список символів (ETH, SOL, тощо)
- [ ] Додати графік ціни (candlestick)
- [ ] Покращити візуалізацію heatmap
- [ ] Додати більше бірж (Hyperliquid, Aevo)

---

**Побудовано з ❤️ використовуючи публічні WebSocket APIs**

### 🔍 Як запустити локально
```bash
# Просто відкрийте файл в браузері
open index.html

# Або використовуйте простий сервер
python3 -m http.server 8000
# Потім відкрийте http://localhost:8000
```

### ⚠️ Дебагінг
Відкрийте консоль браузера (F12), щоб побачити:
- Подключення до WebSocket
- Отримані дані ліквідації
- Помилки (якщо є)

---

**Проєкт готовий до використання! 🎉**
