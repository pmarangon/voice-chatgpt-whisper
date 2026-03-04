

# Voice-ChatGPT-Whisper 🎙️🤖

## 📌 Descrição
Projeto prático desenvolvido no **Bootcamp DIO Bradesco - GenAI & Dados**, com foco em Inteligência Artificial aplicada à comunicação por voz.  
A solução combina **Whisper (OpenAI)** para transcrição de áudio, **ChatGPT (OpenAI API)** para processamento de linguagem natural e **gTTS (Google Text-to-Speech)** para síntese de voz.  

O objetivo é permitir que o usuário faça perguntas por voz e receba respostas também em voz, criando uma experiência interativa e fluida.

---

## 🚀 Tecnologias Utilizadas
- **Python 3.10+**
- **Google Colab**
- **OpenAI Whisper**
- **OpenAI ChatGPT API**
- **Google Text-to-Speech (gTTS)**
- **JavaScript (MediaDevices API)** para captura de áudio no navegador

---

## 🛠️ Estrutura do Projeto
1. **Gravação de áudio**  
   Captura do áudio do usuário via navegador (JavaScript + MediaDevices API).  

2. **Reconhecimento de fala (Whisper)**  
   Transcrição do áudio em texto, com suporte a múltiplos idiomas.  

3. **Integração com ChatGPT**  
   Envio da transcrição para o modelo de linguagem e recebimento da resposta.  

4. **Conversão da resposta em voz (gTTS)**  
   Síntese da resposta em áudio e reprodução para o usuário.  

---

## 📂 Estrutura de Pastas
```
voice-chatgpt-whisper/
│── notebooks/        # Código fonte em Google Colab
│── src/              # Scripts Python
│── js/               # Código JavaScript para captura de áudio
│── assets/           # Arquivos auxiliares (áudio, imagens, etc.)
│── README.md         # Documentação do projeto
```

---

## ▶️ Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/voice-chatgpt-whisper.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure sua chave da API da OpenAI:
   ```bash
   export OPENAI_API_KEY="sua_chave_aqui"
   ```
4. Execute o notebook no Google Colab ou localmente:
   - `notebooks/voice_chatgpt_whisper.ipynb`

---

## 🌍 Possibilidades de Expansão
- Assistente virtual inteligente  
- Aplicações de acessibilidade (ex.: integração com LIBRAS)  
- Automação residencial com comandos de voz  
- Tradução em tempo real  



O bloco de notas está disponível para consulta em: https://colab.research.google.com/drive/1zGr9TCuVftHZ5XR5lFQDMm5pG0Yy6fJw?usp=sharing
