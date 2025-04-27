# META-AI-CLIENT

<p align="center">
  <img src="https://img.shields.io/npm/v/meta-ai-client?color=blue&style=flat-square" alt="npm version" />
  <img src="https://img.shields.io/npm/dw/meta-ai-client?color=brightgreen&style=flat-square" alt="downloads" />
  <img src="https://img.shields.io/npm/l/meta-ai-client?style=flat-square" alt="license" />
</p>

[![A Brand](https://readme-typing-svg.herokuapp.com?font=Charm&duration=2000&pause=1000&color=00FFFF&background=000000&center=true&vCenter=true&width=435&lines=Created+With+%F0%9F%A4%8D+By+Faris+Ali+%E2%86%92;It's+Not+Just+a+Name+Bro+%E2%86%90;It's+a+Brand+%E2%86%92+%F0%9F%A5%87)]([https://git.io/typing-svg](https://www.npmjs.com/package/npm-scrapper-faris))

### 📝 About
**META-AI-CLIENT** Is a unofficial api made by faris ali that allows to call meta ai directly from node.

---

## 🚀 Features

- 🤖 Seamless Meta AI integration  
- 🔄 Automatic token refresh (6h lifespan)  
- 💾 Persistent conversation sessions  

---

## 📦 Installation

```bash
npm install meta-ai-client
```

---

## 🔧 Usage

```javascript
const meta = require('meta-ai-client');
(async () => {
  let ans = await meta.sendMessage("How's The Weather Today In Pakistan?", "786");
  console.log(ans);
})();
// HUH TO EASY IF U WANT ONLY AI RESPONSE JUST USE response.Faris
// While response.Faris2 IS CLEAN RESPONCE (Markdown Free)
// meta.sendMessage(msg, chatID) Chatid Can be any string max 30 chars
```

### Example Output:

```json
{
  success: true,
  status: 'existing_chat',
  token_status: 'existing_token',
  conversation_id: 'bc9860fc-f3e6-49ad-a8a1-609862c71e28',
  user_id: '786',
  Faris: "Here's a snapshot of the current weather in various cities across Pakistan:\n" +
    '\n' +
    '* **Islamabad**: Expect abundant sunshine today with highs reaching 38°C and lows of 23°C. Humidity is at 19% with 0% chance of precipitation.\n' +
    '* **Karachi**: Currently, the temperature is 27°C.\n' +
    '* **Lahore**: The temperature is 25°C.\n' +
    '* **Peshawar**: The temperature is 20°C.\n' +
    '* **Multan**: The temperature is 27°C.\n' +
    '* **Hyderabad**: The temperature is 28°C.\n' +
    '* **Sukkur**: The temperature is 29°C, which is the highest in the country today.\n' +
    '* **Murree**: The temperature is 13°C.\n' +
    '* **Quetta**: The temperature is 19°C.\n' +
    '\n' +
    '\n' +
    'Some other cities in Pakistan are experiencing the following temperatures ¹ ² ³:\n' +
    '* **Rawalpindi**: 24°C\n' +
    '* **Gujranwala**: 22°C\n' +
    '* **Sialkot**: 22°C\n' +
    '* **Faisalabad**: 22°C\n' +
    '* **Skardu**: 5°C\n' +
    '\n' +
    '\n' +
    'The weather forecast indicates hot and dry conditions in most parts of the country, with abundant sunshine expected in cities like Islamabad ².',
  Faris2: "Here's a snapshot of the current weather in various cities across Pakistan:   Islamabad: Expect abundant sunshine today with highs reaching 38°C and lows of 23°C. Humidity is at 19% with 0% chance of precipitation.  Karachi: Currently, the temperature is 27°C.  Lahore: The temperature is 25°C.  Peshawar: The temperature is 20°C.  Multan: The temperature is 27°C.  Hyderabad: The temperature is 28°C.  Sukkur: The temperature is 29°C, which is the highest in the country today.  Murree: The temperature is 13°C.  Quetta: The temperature is 19°C.   Some other cities in Pakistan are experiencing the following temperatures ¹ ² ³:  Rawalpindi: 24°C  Gujranwala: 22°C  Sialkot: 22°C  Faisalabad: 22°C  Skardu: 5°C   The weather forecast indicates hot and dry conditions in most parts of the country, with abundant sunshine expected in cities like Islamabad ².",
  timestamp: '2025-04-27T00:50:34.804Z'
}
```

---

## Repository

Show Your Love To This Pkg By Giving This Repo A [Star](https://github.com/how-faris/meta-ai-client) :)


---

## 🤝 Contributing

Contributions are currently not accepted as the code is proprietary and encrypted.

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE).

---

<p align="center">Made with ❤️ by Faris</p>
