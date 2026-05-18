# Nano Banana Camera Tool 🍌

Ferramenta web para reposicionamento de câmera em imagens usando IA generativa.

## O que faz

Você faz upload de qualquer foto e controla virtualmente a câmera — mudando o ângulo horizontal, vertical e a distância — e o Google Gemini gera a imagem na nova perspectiva.

## Tecnologias

- **Google Gemini Image API** — geração da nova perspectiva
- **JavaScript** — implementação vanilla
- **HTML/CSS** — interface de controles

## Modelos suportados

| Modelo | Qualidade | Velocidade |
|--------|-----------|------------|
| Gemini 3 Pro Image | ⭐⭐⭐ Melhor | Mais lento |
| Gemini 3.1 Flash Image | ⭐⭐ Boa | Rápido |
| Gemini 2.5 Flash Image | ⭐ Básica | Muito rápido |

## Controles

- **Yaw** — ângulo horizontal (-180° a 180°)
- **Pitch** — ângulo vertical (-90° a 90°)
- **Distância** — do close-up extremo ao plano aberto

## Como usar

1. Cole sua chave da [Google AI Studio](https://aistudio.google.com/apikey)
2. Selecione o modelo desejado
3. Faça upload de uma imagem
4. Ajuste os controles de câmera
5. Clique em **Gerar nova câmera**
6. Baixe o resultado

## Autor

**João Pedro Félix Barbosa**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/ofelix-jpedro)

## ⚠️ Sobre a autoria

> ⚠️ **Sobre a autoria:** esse projeto foi desenvolvido com auxílio significativo de IA generativa. Eu estruturei o problema, defini a arquitetura, iterei sobre as soluções e validei o funcionamento em ambiente real — mas não sou autor do código linha a linha.
