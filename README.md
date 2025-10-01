# Projeto Podcast Gerado por I.A.s

![License](https://img.shields.io/badge/license-MIT-blue.svg)

ℹ️ **NOTE:** Este é o repositório do projeto desenvolvido durante um desafio de projeto da plataforma DIO.

O objetivo principal deste projeto é demonstrar a criação de um podcast de forma automatizada, utilizando uma esteira de prompts em diversas ferramentas de Inteligência Artificial para gerar cada etapa do processo criativo.

---

## 💻 Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes ferramentas:

* **[Gemini](https://gemini.google.com/):** Para geração dos roteiros e das artes de capa.
* **[ElevenLabs](https://elevenlabs.io/):** Para síntese de voz e geração do áudio do podcast.
* **[Canva](https://www.canva.com/):** Para a finalização das capas, adicionando títulos e outros elementos gráficos.
* **[CapCut](https://www.capcut.com/):** Para edição e tratamento do áudio, incluindo a adição de trilhas sonoras de fundo.

---

## ✨ Como Foi Feito?

O processo criativo foi dividido em etapas, cada uma utilizando uma ferramenta de IA específica para otimizar a produção:

1.  **📄 Roteiro:** O script completo do podcast foi gerado através de prompts no **Gemini**.
2.  **🎤 Áudio:** O roteiro gerado foi inserido na **ElevenLabs** para criar a narração com voz sintética.
3.  **🎨 Artes da Capa:** As imagens base para a capa do episódio foram criadas no **Gemini** a partir de descrições detalhadas.
4.  **✍️ Finalização da Capa:** A arte gerada foi importada para o **Canva**, onde o título e outros textos foram adicionados para finalizar o design.
5.  **🎧 Edição Final:** Por fim, o áudio foi editado no **CapCut** para tratar ruídos, ajustar o ritmo e adicionar músicas de fundo.

---

## 🛠️ Instruções de Execução

Para replicar este projeto, você pode seguir o passo a passo abaixo, utilizando os prompts fornecidos no link do Notion.

➡️ **Materiais:** [Link para os Prompts no Notion](SEU_LINK_AQUI)

Siga as etapas:

🤖 **1. Geração do Roteiro**
* Acesse o Notion e utilize os prompts de **roteiro** no **Gemini** para criar o script do seu podcast.

🤖 **2. Geração do Áudio**
* Copie o roteiro gerado e cole no **ElevenLabs** para transformar o texto em áudio.

🤖 **3. Criação das Artes**
* Utilize os prompts de **artes** no **Gemini** para gerar as imagens de capa para o seu episódio.

🤖 **4. Finalização das Capas**
* Importe as imagens geradas para o **Canva** e adicione o título do episódio e outros elementos visuais que desejar.

🤖 **5. Edição do Podcast**
* Use o **CapCut** (ou outro editor de sua preferência) para juntar o áudio gerado com uma trilha sonora e fazer os cortes necessários.

---

## 📂 Guia de Arquivos do Projeto

Aqui estão os caminhos para visualizar as capas e os áudios gerados durante o processo:

### 🎨 Capas dos Episódios

- Imagens geradas e finalizadas:
	- `assets/img/capa-ep01.png` — Capa do episódio 01
	- `assets/img/capa-podcast.png` — Capa geral do podcast
	- `assets/img/IA-lice.png` — Arte temática IA

- Documentação das capas:
	- `capas/capas.md` — Descrição e histórico das capas criadas

### 🎧 Áudios do Podcast

- Áudios gerados:
	- `audios/audio-generated.mp3` — Áudio gerado pela IA (voz sintética)
	- `audios/audio-edited.mp3` — Áudio final editado (com trilha e cortes)

---

## 📑 Outros Materiais

- Prompts e resultados:
	- `prompts/prompts-and-results.md` — Exemplos de prompts utilizados e resultados obtidos