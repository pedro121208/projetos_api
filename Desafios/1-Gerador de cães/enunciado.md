# 🐶 Desafio 1: Gerador de Cães (Dog API)

Vamos começar com algo simples e divertido! A **Dog API** é um serviço gratuito que devolve fotografias aleatórias de cães.

**A sua missão:**
1. Crie uma página com uma imagem padrão (pode ser o ícone de uma pata ou uma imagem em branco) e um botão "Gerar Cão".
2. Ao clicar no botão, utilize a função `fetch()` para consultar o endereço: `https://dog.ceo/api/breeds/image/random`
3. O JSON recebido terá uma propriedade chamada `message` que contém o link (URL) da imagem.
4. Altere o atributo `src` da sua tag `<img>` no HTML para que a nova fotografia apareça no ecrã!