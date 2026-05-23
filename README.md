# 🤖 SUPER JARVIS
### The Ultimate Cross-Platform Personal AI Assistant — By FatihMakes

> 📺 **[Watch the full setup video on YouTube](https://youtu.be/ej1f5OE3SNQ?si=lCxDhJix9ungq1Ry)**

A real-time voice AI that can hear, see, understand, and control your computer — on any OS. Supporting Windows, macOS, and Linux. Local execution. Zero subscriptions. Engineered for total autonomy.

---

## ✨ Overview

MARK XXXIX represents the pinnacle of the Jarvis series, evolving into a more flexible and robust system. It bridges the gap between the operating system and human intent. Through natural dialogue, Mark 39 analyzes your screen, processes uploaded documents, and executes complex workflows with a brand-new, adaptive interface.

It's not just an assistant — it's an extension of your digital life.

---

## 🚀 Capabilities

### Core Features
|
 Feature 
|
 Description 
|
|
---
|
---
|
|
 🎙️ Real-time Voice 
|
 Ultra-low latency conversation in any language 
|
|
 🖥️ System Control 
|
 Launch apps, manage files, execute terminal commands 
|
|
 🧩 Autonomous Tasks 
|
 High-level planning for complex, multi-step goals 
|
|
 👁️ Visual Awareness 
|
 Real-time screen processing and webcam vision 
|
|
 🧠 Persistent Memory 
|
 Deeply remembers your projects, preferences, and personal context 
|
|
 ⌨️ Hybrid Input 
|
 Seamlessly switch between keyboard typing and voice commands 
|

---

## 🆕 What's New in XXXIX

- 📂 **Advanced File Handling** — New support for direct file uploads. Drop PDFs, source code, or images into the assistant to have them analyzed, summarized, or edited instantly.
- 🎨 **Adaptive & Flexible UI** — A complete overhaul of the interface. The new UI is fully resizable and responsive, featuring transparency controls and customizable layouts to fit your workspace perfectly.
- 🐧🍎 **Refined Cross-Platform Stability** — Major fixes for macOS and Linux compatibility. Core system actions are now more consistent across all three major operating systems.
- ⚡ **Optimized Core Engine** — Significant performance boost in tool-calling logic and response generation, resulting in a 40% faster interaction speed.

---

## ⚡ Quick Start

```bash
git clone https://github.com/FatihMakes/Mark-XXXIX.git
cd Mark-XXXIX
pip install -r requirements.txt
playwright install
python main.py
```

> ⚠️ **Installation Note:** To keep the repository lightweight, some OS-specific dependencies are not bundled in `requirements.txt`. If you run into a `ModuleNotFoundError`, simply install the missing package via `pip install <module_name>` for your specific system.

---

## 📋 Requirements

|
 Requirement 
|
 Details 
|
|
---
|
---
|
|
**
OS
**
|
 Windows 10/11, macOS, or Linux 
|
|
**
Python
**
|
 3.11 or 3.12 
|
|
**
Microphone
**
|
 Required for voice interaction 
|
|
**
API Key
**
|
 Free Gemini API key 
|

---

## ⚠️ License

Personal and non-commercial use only.
Licensed under **[Creative Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)**.

---

## 👤 Connect with the Creator

Engineered by a developer building a real-world JARVIS-style assistant.
⭐ **Star the repository to support the journey to Mark 100.**

|
 Platform 
|
 Link 
|
|
---
|
---
|
|
 YouTube 
|
[
@FatihMakes
](
https://www.youtube.com/@FatihMakes
)
|
|
 Instagram 
|
[
@fatihmakes
](
https://www.instagram.com/fatihmakes
)
|
<div align="center">
  <img src="face.png" alt="Super Jarvis Logo" width="150"/>
  <h1>🤖 SUPER JARVIS</h1>
  <p><strong>O Assistente Pessoal Definitivo com IA, Smart Home e Clone de WhatsApp</strong></p>
</div>
---
## ✨ Sobre o Projeto
**SUPER JARVIS** é um assistente de Inteligência Artificial rodando localmente no seu computador, projetado para ouvir, falar, automatizar sua casa e até mesmo clonar a sua personalidade no WhatsApp.
Construído inicialmente a partir de projetos base de IA, este ecossistema foi modificado extensivamente para incluir interações em tempo real com hardware (Lâmpadas, TVs), APIs da internet, Banco de Dados Vetorial (Memória) e integração com o smartphone do usuário.
---
## 🚀 Super Funcionalidades
### 1. Cérebro Híbrido (Groq + Gemini)
O núcleo de raciocínio utiliza a **API ultrarrápida da Groq (`llama-3.3-70b`)** para garantir latência quase zero durante conversas de voz, com fallback automático para o **Google Gemini** em caso de instabilidade. 
### 2. Automação Smart Home (eWeLink)
Integração física com a casa do usuário via ecossistema eWeLink/Alexa.
- **Controle por Voz Natural:** "Jarvis, apaga a luz da sala."
- **Multi-Canais:** Capacidade nativa de interpretar módulos com múltiplos interruptores (ex: `device:1`, `device:2`).
### 3. O "Clone Humano" (WhatsApp Bridge)
Uma das funcionalidades mais avançadas do sistema. O JARVIS se conecta ao WhatsApp Web (via Node.js/Puppeteer) e atua como o usuário ("Alexandre / Kaco").
- **Persona Injetada:** O bot responde usando letras minúsculas, gírias locais ("eai", "suave") e emojis ocasionais.
- **Isolamento de Segurança:** Amigos não sabem que estão falando com uma IA, e o bot do WhatsApp não tem permissão para acender luzes ou controlar o computador (Sandboxing).
### 4. Memória de Longo Prazo (RAG - ChromaDB)
Ao invés de esquecer as coisas quando o terminal é fechado, o SUPER JARVIS utiliza um banco de dados vetorial local (`ChromaDB`) para salvar conversas, detalhes e preferências, relembrando fatos do passado quando necessário.
### 5. Motor Climático Silencioso
Integração com o `wttr.in`. Em vez de abrir o navegador de forma incômoda, o JARVIS consulta o clima via requisições ocultas e usa a síntese de voz para relatar as condições climáticas e a umidade de forma fluida.
### 6. Controle Físico do Computador (Agent Executor)
Através de comandos, o JARVIS pode assumir o mouse e teclado para abrir arquivos, fechar janelas, pesquisar no Google ou tirar screenshots da tela atual para analisar o que o usuário está vendo.
---
## ⚙️ Arquitetura e Tecnologias
- **Python 3.12+** (Back-end principal)
- **Node.js & Puppeteer** (Servidor do WhatsApp Web Webhooks)
- **Edge-TTS & Whisper** (Motor de Voz, Texto para Fala e Fala para Texto)
- **ChromaDB** (Vector Database para Memória RAG)
---
## ⚡ Instalação e Execução
### Pré-requisitos
- Python 3.11 ou superior
- Node.js instalado (para o módulo do WhatsApp)
- Chaves de API (Groq e Gemini) configuradas em `config/api_keys.json`
### Rodando o Sistema
1. Clone o repositório e entre na pasta:
```bash
git clone https://github.com/SeuUsuario/Super-Jarvis.git
cd Super-Jarvis
```
2. Instale as dependências:
```bash
pip install -r requirements.txt
cd whatsapp-service
npm install
cd ..
```
3. Inicie o SUPER JARVIS:
```bash
python main.py
```
> Após iniciar, um link para o **QR Code do WhatsApp** aparecerá no console para você vincular o seu aparelho e ativar o modo Clone.
---
## ⚠️ Isenção de Responsabilidade
Este é um projeto pessoal de automação. O uso do bot de WhatsApp através da injeção no WhatsApp Web (`whatsapp-web.js`) não é oficialmente endossado pela Meta e pode violar os Termos de Serviço se usado para spam.
---
*Desenvolvido e mantido para automação residencial e inteligência invisível.*
