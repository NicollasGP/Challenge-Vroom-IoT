# 🚀 Challenge Vroom IoT - Mottu

Solução desenvolvida como parte do desafio **Vroom IoT**, com foco na organização e segurança de pátios de motocicletas da empresa **Mottu**. A proposta envolve o uso de tags inteligentes simuladas no Wokwi, integração com Node-RED e um dashboard interativo.

---

## 📍 Visão Geral

O sistema simula o funcionamento de uma tag inteligente com:
- LED RGB que muda de cor a cada clique no botão.
- Buzzer que emite sons diferentes conforme a cor.
- Comportamento de desligamento ao pressionar continuamente o botão.

Esses eventos são enviados para o **Node-RED**, onde são processados e exibidos em tempo real em um **dashboard interativo**.

---

## 🛠 Tecnologias Utilizadas

- **Arduino (Wokwi Simulator)** – Simulação do hardware da tag inteligente.
- **Node-RED** – Processamento e roteamento dos dados da tag.
- **Node-RED Dashboard** – Visualização em tempo real dos dados da tag.
- **MQTT (simulado no Wokwi)** – Comunicação entre o dispositivo e o servidor.

---

## 🎮 Projeto no Wokwi

Acesse o projeto simulador da tag no Wokwi:  
🔗 [https://wokwi.com/projects/431580008684127233](https://wokwi.com/projects/431580008684127233)

---

## 🧰 Configuração do Node-RED

1. Instale o pacote `node-red-dashboard` (caso ainda não tenha):
   ```bash
   npm install node-red-dashboard
