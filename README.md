# 🤖 SUPER JARVIS

### O Assistente Pessoal Definitivo com IA.

---

# ✨ Sobre o Projeto

O **SUPER JARVIS** é um assistente de Inteligência Artificial executado localmente no computador do usuário, projetado para:

- 🎙️ Ouvir e conversar por voz
- 🧠 Memorizar informações e preferências
- 🏠 Automatizar dispositivos Smart Home
- 💬 Clonar personalidade no WhatsApp
- 🖥️ Controlar fisicamente o computador

O projeto evoluiu a partir de bases de IA open-source e foi amplamente modificado para integrar:

- Hardware doméstico
- APIs externas
- Banco de memória vetorial (RAG)
- Controle em tempo real
- Automação invisível e contextual

---

# 🚀 Funcionalidades

---

## 🧠 1. Cérebro Híbrido (Groq + Gemini)

O sistema utiliza a API ultrarrápida da **Groq (`llama-3.3-70b`)** como núcleo principal de raciocínio, garantindo respostas quase instantâneas em conversas por voz.

Caso haja instabilidade, o sistema realiza fallback automático para o **Google Gemini**.

### ⚡ Recursos

- ⚡ Latência extremamente baixa
- 🔄 Fallback automático
- 🎤 Conversação fluida em tempo real

---

## 🏠 2. Automação Smart Home (eWeLink)

Integração completa com o ecossistema **eWeLink / Alexa** para controle físico da casa.

### 🎙️ Exemplos

```txt
"Jarvis, apaga a luz da sala."
"Jarvis, liga a TV."
```

### ⚙️ Recursos

- 🎙️ Controle por voz natural
- 💡 Suporte a dispositivos multi-canais
- 🔌 Compatível com interruptores inteligentes

### 🔌 Exemplo Multi-Canal

```txt
device:1
device:2
```

---

## 💬 3. Clone Humano no WhatsApp

Uma das funcionalidades mais avançadas do projeto.

O SUPER JARVIS conecta-se ao **WhatsApp Web** utilizando:

- Node.js
- Puppeteer
- whatsapp-web.js

E passa a agir como o próprio usuário.

### 🧠 Características

- 🧠 Persona personalizada
- 😎 Uso de gírias locais
- 😊 Emojis ocasionais
- 🔒 Sistema isolado (sandbox)

### 🔒 Segurança

O módulo do WhatsApp **não possui permissão** para:

- controlar luzes
- acessar o computador
- executar automações críticas

Isso evita riscos de segurança.

---

## 🧠 4. Memória de Longo Prazo (RAG + ChromaDB)

O SUPER JARVIS utiliza **ChromaDB** como banco de dados vetorial local para armazenar:

- Conversas
- Preferências
- Informações importantes
- Contexto histórico

Assim, o sistema consegue lembrar fatos mesmo após reinicializações.

### 📚 Recursos

- 🧠 Memória persistente
- 🔍 Recuperação contextual
- 📚 Aprendizado contínuo

---

## 🌦️ 5. Motor Climático Silencioso

Integração com o serviço `wttr.in`.

O clima é consultado silenciosamente via requisições HTTP, sem abrir navegador.

### 🌡️ Recursos

- 🌡️ Temperatura atual
- 💧 Umidade do ar
- ☁️ Condições climáticas
- 🔊 Resposta por voz natural

---

## 🖥️ 6. Controle Físico do Computador (Agent Executor)

O SUPER JARVIS pode controlar:

- 🖱️ Mouse
- ⌨️ Teclado
- 🪟 Janelas
- 🌐 Navegador
- 📁 Arquivos locais

Além disso, consegue capturar screenshots da tela para interpretar visualmente o contexto do usuário.

### 💻 Exemplos

```txt
"Jarvis, pesquisa no Google."
"Jarvis, fecha essa janela."
"Jarvis, abre meu projeto."
```

---

# ⚙️ Arquitetura e Tecnologias

## 🖥️ Back-end

- Python 3.12+

## 🎤 Voz e IA

- Edge-TTS
- Whisper
- Groq API
- Google Gemini

## 🧠 Memória

- ChromaDB

## 💬 WhatsApp

- Node.js
- Puppeteer
- whatsapp-web.js

---

# 📂 Estrutura do Projeto

```bash
SUPER-JARVIS/
│
├── main.py
├── requirements.txt
├── config/
│   └── api_keys.json
│
├── whatsapp-service/
│   ├── package.json
│   └── ...
│
├── memory/
├── automation/
├── voice/
└── agents/
```

---

# ⚡ Instalação e Execução

---

## 📋 Pré-requisitos

Antes de começar, você precisará de:

- Python 3.11+
- Node.js instalado
- Conta Groq
- Conta Google Gemini
- APIs configuradas

---

## 🔑 Configuração das APIs

Configure suas chaves no arquivo:

```bash
config/api_keys.json
```

### 📄 Exemplo

```json
{
  "groq_api_key": "SUA_CHAVE",
  "gemini_api_key": "SUA_CHAVE"
}
```

---

## 📥 Clone o Repositório

```bash
git clone https://github.com/SeuUsuario/Super-Jarvis.git
cd Super-Jarvis
```

---

## 📦 Instale as Dependências

### Python

```bash
pip install -r requirements.txt
```

### WhatsApp Service

```bash
cd whatsapp-service
npm install
cd ..
```

---

## ▶️ Execute o Sistema

```bash
python main.py
```

---

# 📱 Vincular WhatsApp

Após iniciar o sistema:

1. Um QR Code aparecerá no terminal
2. Escaneie usando o WhatsApp
3. O modo Clone será ativado

---

# 🔒 Segurança

O projeto utiliza isolamento de módulos para evitar acessos indevidos entre:

- WhatsApp Bot
- Automação residencial
- Controle físico do PC

Isso reduz riscos de execução acidental de comandos críticos.

---

# ⚠️ Aviso Legal

Este é um projeto experimental e pessoal de automação residencial.

O uso de bibliotecas como:

- `whatsapp-web.js`
- Puppeteer
- automações no WhatsApp Web

não é oficialmente suportado pela Meta e pode violar os Termos de Serviço se utilizado para:

- spam
- automação abusiva
- envio massivo de mensagens

Use com responsabilidade.

---

# 🧩 Futuras Expansões

- 📷 Visão computacional em tempo real
- 🧠 Agentes autônomos multi-tarefas
- 🛰️ Integração com dispositivos IoT avançados
- 📱 Aplicativo mobile próprio
- ☁️ Sincronização entre dispositivos

---

# 👨‍💻 Autor
Projeto By FatihMakes
Avanços e Integraçoes By Kaco
Projeto desenvolvido para automação invisível, inteligência contextual e interação humano-máquina avançada.

---

# ⭐ SUPER JARVIS

> “Não é apenas um assistente.  
> É uma extensão inteligente do usuário.”
