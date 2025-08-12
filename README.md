# 🚀 Dashboard MQTT - SENAI 790

Este projeto é um dashboard web para monitoramento de sensores e controle de LEDs via MQTT, utilizando o protocolo WebSocket seguro.

---

## 🗂️ Estrutura do Projeto

```
📁 Dashboard-1/
 ├── 📝 index.html
 ├── 📂 css/
 │    └── 🎨 style.css
 └── 📂 js/
      └── 📜 script.js
```

---

## ⚙️ Funcionalidades

- 🌡️ **Monitoramento de Temperatura e Umidade:** Recebe dados do sensor DHT22 via MQTT e exibe na interface.
- 💡 **Controle de LEDs:** Permite ligar/desligar dois LEDs remotamente, enviando comandos MQTT.

---

## 🖥️ Como usar

1. Abra o arquivo `Dashboard-1/index.html` em um navegador moderno.
2. Certifique-se de estar conectado à internet para acessar o broker público HiveMQ.
3. Visualize os dados do sensor e controle os LEDs pelos botões da interface.

---

## 🛠️ Tecnologias

- HTML, CSS, JavaScript
- [Paho MQTT JavaScript Client](https://www.eclipse.org/paho/clients/js/) 🔗
- Broker público: [HiveMQ](https://www.hivemq.com/public-mqtt-broker/) 🔗

---

## 👨‍🏫 Autor

Projeto desenvolvido para aulas de IoT pelo Prof. Eng. Cristiano de Paula.