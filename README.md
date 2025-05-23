~~~~# 🚀 Challenge Vroom IoT

Solução desenvolvida como parte do desafio Vroom IoT, com foco na organização e segurança de pátios de motocicletas da empresa Mottu. A proposta envolve o uso de tags inteligentes simuladas no Wokwi, integração com Node-RED e um dashboard interativo.

---

## 📍 Visão Geral
O sistema simula o funcionamento de uma tag inteligente com:

- LED RGB que muda de cor a cada clique no botão.
- Buzzer que emite sons diferentes conforme a cor.
- Comportamento de desligamento ao pressionar continuamente o botão.
- Esses eventos são enviados para o Node-RED, onde são processados e exibidos em tempo real em um dashboard interativo.

## 🛠 Tecnologias Utilizadas
- ESP32 (Wokwi Simulator) – Simulação do hardware da tag inteligente.
- Node-RED – Processamento e roteamento dos dados da tag.
- Node-RED Dashboard – Visualização em tempo real dos dados da tag.
- MQTT (simulado no Wokwi) – Comunicação entre o dispositivo e o servidor.

## 🔌 Projeto no Wokwi

Acesse a simulação diretamente pelo link:  
👉 [https://wokwi.com/projects/431580008684127233](https://wokwi.com/projects/431580008684127233)

---

## 📦 Node-RED

- ⚠️ **É necessário instalar o pacote `node-red-dashboard` no Node-RED.**
- 🗂️ O fluxo está disponível no arquivo `vroom.json` deste repositório.
- 📊 Acesse o dashboard em:  
  👉 [http://localhost:1880/ui](http://localhost:1880/ui)

---

## 🎥 Vídeos

- 📽️ **Pitch das Tecnologias Utilizadas:**  
  *(link das tecnologias a ser adicionado)*

- 🧠 **Apresentação da Solução (Pitch Final):**  
  👉 [https://youtu.be/UBFGZRqeJI0?si=7aTC5ctlODD1IMW3](https://youtu.be/UBFGZRqeJI0?si=7aTC5ctlODD1IMW3)

---

## 📑 Descritivo da Solução

*(Adicione aqui o link para o documento explicativo da solução com arquitetura, funcionamento e objetivos)*

---

## 📁 Estrutura do Projeto

- `codigo-fonte-wokwi/` – Código da simulação IoT no Wokwi
- `vroom.json` – Fluxo do Node-RED exportado
- `dashboard` – Interface
- `README.md` – Este arquivo

---

## 🛠️ Como Executar

1. Instale o [Node-RED](https://nodered.org/)
2. Instale o pacote `node-red-dashboard`
3. Importe o fluxo `vroom.json` no editor do Node-RED
4. Inicie o Node-RED e acesse o painel em [http://localhost:1880/ui](http://localhost:1880/ui)
5. Para a simulação, abra o projeto no Wokwi pelo link acima

---

> Projeto desenvolvido para fins acadêmicos e de demonstração tecnológica.
