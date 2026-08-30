<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366F1,50:8B5CF6,100:10B981&height=220&section=header&text=TANUKI&fontSize=70&fontColor=FFFFFF&fontAlignY=38&desc=Enterprise%20Intelligent%20Agent%20and%20WhatsApp%20Automation%20Platform&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="Tanuki Header" />

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=8B5CF6&center=true&vCenter=true&width=650&lines=Plataforma+SaaS+Multi-Tenant+de+IA;RAG+%2B+Modelos+Multimodales;Automatizaci%C3%B3n+de+WhatsApp+en+tiempo+real;Arquitectura+de+Microservicios)](https://github.com/ai-tanuki)

[![Organization](https://img.shields.io/badge/GitHub-ai--tanuki-6366F1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ai-tanuki)
[![Author](https://img.shields.io/badge/Author-Alexis_Mendoza-8B5CF6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alexismendozaa)
[![Architecture](https://img.shields.io/badge/Architecture-Microservices-10B981?style=for-the-badge&logo=docker&logoColor=white)](https://github.com/ai-tanuki)

![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-20232A?style=flat-square&logo=vite&logoColor=646CFF)
![Node.js](https://img.shields.io/badge/Node.js_LTS-20232A?style=flat-square&logo=node.js&logoColor=339933)
![MongoDB](https://img.shields.io/badge/MongoDB_Atlas-20232A?style=flat-square&logo=mongodb&logoColor=47A248)
![Docker](https://img.shields.io/badge/Docker_Multi--Arch-20232A?style=flat-square&logo=docker&logoColor=2496ED)
![Gemini](https://img.shields.io/badge/Google_Gemini-20232A?style=flat-square&logo=google&logoColor=4285F4)
![WhatsApp](https://img.shields.io/badge/WhatsApp_Cloud_API-20232A?style=flat-square&logo=whatsapp&logoColor=25D366)

</div>

<br/>

![line](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif)

## Resumen Ejecutivo

**Tanuki** es una plataforma SaaS multi-tenant diseñada para automatizar la atención al cliente, la gestión de catálogos y los flujos comerciales mediante Agentes de Inteligencia Artificial conectados a WhatsApp.

La solución combina **recuperación aumentada por generación (RAG)** y modelos de lenguaje multimodales para interpretar catálogos en PDF, procesar consultas técnicas sobre productos, analizar imágenes, transcribir notas de voz y registrar pedidos o reservas en tiempo real.

![line](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif)

## Repositorios del Ecosistema

| Repositorio | Alcance Técnico |
|---|---|
| **[`frontend`](https://github.com/ai-tanuki/frontend)** | Panel de control y dashboard interactivo desarrollado en React y Vite. Incluye soporte para temas claro y oscuro, monitoreo analítico, bandeja de entrada omnicanal, gestión de catálogos y simulador de chat. |
| **[`agent-service`](https://github.com/ai-tanuki/agent-service)** | Núcleo de Inteligencia Artificial y mensajería. Orquestación RAG mediante embeddings vectoriales, llamadas a Google Gemini, transcripción de voz, integración con Meta Cloud API y WebSockets en tiempo real. |
| **[`auth-service`](https://github.com/ai-tanuki/auth-service)** | Microservicio de identidad y seguridad. Control de acceso con tokens JWT (Access y Refresh), verificación en dos pasos (2FA), administración de roles (Administrador, Propietario, Asesor) y gestión de sesión activa. |

![line](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif)

## Módulos Principales

<table>
<tr>
<td width="50%" valign="top">

### Motor RAG Vectorial
Indexación automática de catálogos PDF y bases de conocimiento corporativas mediante embeddings semánticos y cálculo de similitud de coseno.

### Mensajería Omnicanal
Conectividad con WhatsApp mediante Meta Cloud API oficial y soporte alternativo de sincronización por código QR Multi-Device.

</td>
<td width="50%" valign="top">

### Procesamiento Multimodal
Comprensión visual de imágenes enviadas por clientes y transcripción nativa de notas de voz a texto.

### Control Multi-Tenant
Aislamiento seguro de datos por empresa, administración de límites por suscripción, métricas de consumo y transferencia hacia asesores humanos.

</td>
</tr>
</table>

![line](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif)

## Stack de Infraestructura y Tecnologías

| Capa | Tecnologías |
|---|---|
| **Frontend** | `React` · `Vite` · `CSS Modular` · `Context API` · `WebSockets` |
| **Backend** | `Node.js` · `Express` · `Socket.IO` · `JWT` · `Mongoose` |
| **Inteligencia Artificial** | `Google Gemini 2.0 Flash` · `Text Embeddings` · `Cosine Similarity` |
| **Base de Datos** | `MongoDB Atlas` · `Cloudinary CDN` |
| **DevOps y Cloud** | `Docker Multi-Arch (AMD64 / ARM64)` · `Nginx` · `GitHub Actions CI/CD` · `Oracle Cloud Infrastructure` |

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:10B981,50:8B5CF6,100:6366F1&height=120&section=footer" width="100%" alt="Tanuki Footer" />

<sub>Tanuki Platform © 2026 • Arquitectura y desarrollo por <a href="https://github.com/alexismendozaa">alexis</a></sub>

</div>
