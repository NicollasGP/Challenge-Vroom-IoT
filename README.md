# 🚀 Challenge Vroom IoT

Solução desenvolvida como parte do desafio Vroom IoT, com foco na organização e segurança de pátios de motocicletas da empresa Mottu. A proposta envolve o uso de tags inteligentes simuladas no Wokwi, integração com Node-RED e um dashboard interativo.

---

## Integrantes
- Guilherme Guimarães - RM 557074 / 2TDSA
- Nicollas Guedes Pontes - RM 556850 / 2TDSB
- Matheus Oliveira de Luna - RM 555547 / 2TDSA

---

## 📍 Visão Geral
O sistema simula o funcionamento de uma tag inteligente com:

- LED RGB que muda de cor a cada clique no botão.
- Buzzer que emite sons diferentes conforme a cor.
- Botão que altera o estado da led.
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
- 🗂️ O fluxo está disponível na pasta `node-red` deste repositório.
- 📊 Acesse o dashboard em:  
  👉 [http://localhost:1880/ui](http://localhost:1880/ui)

---

## 🎥 Vídeos

- 📽️ **Pitch das Tecnologias Utilizadas:**  
  👉 [https://youtu.be/OuXchSjabAA](https://youtu.be/OuXchSjabAA)

- 🧠 **Apresentação da Solução (Pitch Final):**  
  👉 [https://youtu.be/UBFGZRqeJI0?si=7aTC5ctlODD1IMW3](https://youtu.be/UBFGZRqeJI0?si=7aTC5ctlODD1IMW3)

---

## 📁 Estrutura do Projeto

- `codigo-fonte-wokwi/` – Pasta com o código da simulação IoT no Wokwi
- `node-red` – Pasta com o fluxo do Node-RED exportado
- `dashboard` – Pasta com o link da interface
- `descritivo-solucao` – Pasta com o PDF da Descrição da Solução
- `README.md` – Este arquivo

---

## 🛠️ Como Executar

1. Instale o [Node-RED](https://nodered.org/)
2. Instale o pacote `node-red-dashboard`
3. Importe o fluxo na pasta `node-red` no editor do Node-RED
4. Inicie o Node-RED e acesse o painel em [http://localhost:1880/ui](http://localhost:1880/ui)
5. Para a simulação, abra o projeto no Wokwi pelo link [https://wokwi.com/projects/431580008684127233](https://wokwi.com/projects/431580008684127233)

---

> Projeto desenvolvido para fins acadêmicos e de demonstração tecnológica.
