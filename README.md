# IoT_html_dashboard
HTML的儀表板


```markdown
# 🌐 IoT HTML Dashboard

A lightweight and responsive **IoT Dashboard** built with **HTML, CSS, and JavaScript** for real-time visualization of sensor data.  
This project provides a clean and easy-to-customize interface for monitoring IoT systems such as temperature, humidity, and light sensors.

Designed to work seamlessly with Raspberry Pi, ESP32, Node-RED, Flask, and other IoT platforms.

---

## 🚀 Features

- 📊 **Real-time Data Display** — Updates automatically via WebSocket, MQTT, or HTTP API.  
- ⚙️ **Modular Widget Design** — Easily add or remove components like temperature, humidity, or light panels.  
- 📱 **Responsive Layout** — Works on desktop, tablet, and mobile devices.  
- 🌈 **Customizable Theme** — Adjust colors, layout, and icons easily.  
- 💾 **Local & Remote Support** — Can be opened locally or hosted on a web server (e.g., Raspberry Pi).  

---

## 🧩 Project Structure

```

IoT_html_dashboard/
├── index.html          # Main dashboard page
├── css/
│   └── style.css       # Dashboard styling
├── js/
│   ├── main.js         # Core dashboard logic
│   └── api.js          # Handles backend or sensor data fetching
├── assets/
│   └── icons/          # Icons or image assets
└── README.md           # Project documentation

````

---

## 🖥️ Dashboard Preview

![Dashboard Preview](https://via.placeholder.com/900x500?text=IoT+Dashboard+Preview)

---

## 🔌 How It Works

1. **IoT devices** (ESP32, Raspberry Pi, etc.) collect sensor data.  
2. **Backend server or MQTT broker** receives and provides the data through APIs.  
3. The **HTML dashboard** fetches and visualizes the data in real time using JavaScript.  

Compatible with:
- 🌡️ Raspberry Pi  
- 🌤️ ESP32 / ESP8266  
- 🧠 Node-RED  
- ☁️ AWS IoT / ThingsBoard / MQTT Broker  

---

## ⚙️ Setup & Usage

### 🧰 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/IoT_html_dashboard.git
cd IoT_html_dashboard
````

### 🌐 2. Open the Dashboard

Simply open `index.html` in your browser.

### 🔄 3. (Optional) Connect to a Backend

Edit the API endpoint in `js/api.js`:

```js
const API_URL = "http://your-server-ip:5000/api/sensor";
```

---

## 🧠 Example Data Format

Example JSON response from your backend:

```json
{
  "temperature": 25.3,
  "humidity": 61,
  "light": 420
}
```

The dashboard will automatically update its widgets with the latest sensor values.

---

## 🔮 Future Improvements

* Add WebSocket / MQTT live update support
* Integrate with Node-RED or Flask backend
* Add login authentication for dashboard access
* Implement dark mode support

---

## 👨‍💻 Author

**Lucas Chung (鍾明志)**
IoT Developer / Embedded Systems Enthusiast
📧 Email: [your_email@example.com](mailto:your_email@example.com)
🔗 GitHub: [@your-username](https://github.com/your-username)

---

## 🪪 License

This project is licensed under the [MIT License](LICENSE).
You are free to use and modify it — just keep the author credit.


