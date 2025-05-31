# Uptime Kuma – Monitorización con Docker

Este proyecto contiene la configuración necesaria para desplegar **Uptime Kuma**, una herramienta de monitorización tipo "self-hosted" similar a Uptime Robot, utilizando **Docker y Docker Compose** sobre un servidor con Ubuntu Server.

## 🚀 ¿Qué es Uptime Kuma?

Uptime Kuma es una herramienta moderna, elegante y de código abierto para monitorear la disponibilidad de tus servicios, páginas web, ping, puertos y más. Ideal para entornos caseros o profesionales.

## ⚙️ Tecnologías utilizadas

- Ubuntu Server 22.04
- Docker
- Docker Compose
- Git
- Uptime Kuma

## 🧱 Estructura del proyecto

```bash
uptimekuma/
├── docker-compose.yml
└── .env (opcional)
```bash

📦 Instrucciones para desplegar
1. Clonar el repositorio
bash
Copiar
Editar
git clone git@github.com:Nyxazzz/UptimeKuma.git
cd UptimeKuma
2. Desplegar con Docker Compose
bash
Copiar
Editar
docker compose up -d
3. Acceder a la interfaz
Abre tu navegador en:

cpp
Copiar
Editar
http://<IP-de-tu-servidor>:3001
