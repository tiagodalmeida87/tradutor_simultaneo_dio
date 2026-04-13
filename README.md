# 🎙️ Conversando por Voz com NVIDIA Nemotron 3 + Whisper

Projeto desenvolvido como parte de um desafio de Bootcamp, com foco em **Inteligência Artificial aplicada à comunicação por voz**, integrando tecnologias modernas de **Speech-to-Text, NLP e Text-to-Speech**.

---

## 📌 Sobre o Projeto

Este projeto implementa um sistema capaz de:

- Captar áudio do usuário 🎤  
- Converter fala em texto (Speech-to-Text)  
- Processar e gerar respostas com IA 🤖  
- Converter texto em voz (Text-to-Speech) 🔊  

A solução utiliza o modelo **Whisper (OpenAI)** para reconhecimento de fala e o **NVIDIA Nemotron 3** para geração de respostas inteligentes, criando uma experiência completa de interação por voz.

---

## 🧠 Conceitos Aplicados

- Reconhecimento Automático de Fala (ASR)
- Processamento de Linguagem Natural (NLP)
- Integração de APIs de IA
- Conversão multimodal (voz ↔ texto)
- Sistemas inteligentes conversacionais

---

![code_resposta](https://github.com/tiagodalmeida87/tradutor_simultaneo_dio/blob/main/prints/pergutna%2Bresposta_caseIA.jpg)
###### conversao_pergunta_em_resposta_text
---

## ⚙️ Arquitetura da Solução

```mermaid
graph TD
A[🎤 Entrada de Áudio] --> B[Whisper - Speech to Text]
B --> C[NVIDIA Nemotron 3 - Processamento]
C --> D[gTTS - Text to Speech]
D --> E[🔊 Saída de Áudio]
```

---

## 🧩 Etapas do Desenvolvimento

### 1️⃣ Captura de Áudio

- Utilização da Web API MediaDevices para gravação no navegador
- Integração com Python para armazenamento do áudio

### 2️⃣ Reconhecimento de Fala (Whisper)

- Transcrição de áudio para texto
- Suporte a múltiplos idiomas
- Alta precisão mesmo com ruídos e sotaques

### 3️⃣ Integração com NVIDIA Nemotron 3

- Processamento da entrada do usuário
- Geração de respostas inteligentes

### 4️⃣ Conversão de Texto em Voz

- Uso da biblioteca gTTS
- Geração de áudio no idioma desejado

---

## 🎯 Funcionalidades

- Conversação por voz em tempo real  
- Tradução entre idiomas  
- Respostas inteligentes com IA  
- Experiência completa de áudio  

---

## 💡 Possíveis Aplicações

- Assistentes virtuais  
- Automação residencial  
- Acessibilidade  
- Educação  
- Tradução simultânea  

---

## ▶️ Como Executar

Acesse e execute o projeto pelo [Google Colab](https://colab.research.google.com/drive/1tRJztEWqbb-t33paun8vo4kQd5tHMbqm?usp=sharing)

---

## 🚀 Tecnologias Utilizadas

- Python
- JavaScript (Web API MediaDevices)
- Whisper (OpenAI)
- NVIDIA Nemotron 3 API
- gTTS (Google Text-to-Speech)
- Machine Learning / IA

---

## 🧑‍💻 Autor

Feito por [Tiago Almeida](https://github.com/tiagodalmeida87) 🧑‍💻
Analista de Dados | BI | Machine Learning  

---

## 📢 Considerações Finais

Projeto focado na construção de soluções de IA conversacional integrando múltiplas tecnologias modernas.
