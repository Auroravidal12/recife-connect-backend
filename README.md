# Recife Connect Backend 🖥️

Backend desenvolvido em Node.js + Express para o aplicativo Recife Connect.

---

## 🚀 Objetivo

Este backend tem como objetivo armazenar e fornecer dados de localização do usuário enviados pelo aplicativo mobile.

---

## ⚙️ Tecnologias utilizadas

- Node.js
- Express
- CORS

---

## 📡 Rotas da API

### 📍 POST /location

Recebe a localização do usuário e salva no servidor.

Exemplo de body:

```json
{
  "latitude": -8.05,
  "longitude": -34.9
}
