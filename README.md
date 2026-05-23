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
Uma das funcionalidades mais avançadas do sistema. O JARVIS se conecta ao WhatsApp Web (via Node.js/Puppeteer) e atua como o usuário ("Seu Nome / Apelido").
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
