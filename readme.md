# 💻 Desafio DIO - Clone Responsivo Discord

Este repositório contém a resolução do desafio de responsividade da DIO, que consiste em recriar a página inicial do Discord com design responsivo para diferentes tamanhos de tela, incluindo desktop e dispositivos móveis como o iPhone.

## 🚀 Tecnologias Utilizadas

* **HTML5:** Estrutura semântica da página.
* **CSS3:** Estilização e responsividade, utilizando `Flexbox` e `Media Queries`.
    * `style.css`: Estilos base para desktop (abordagem Desktop-First).
    * `mobile.css`: Contém as `media queries` para adaptar o layout para telas menores, como tablets e celulares (iPhone).

## ✨ Funcionalidades

* **Design Responsivo:** Layout adaptável para desktop e dispositivos móveis (iPhone).
* **Seções de Conteúdo:** Recriação visual das principais seções da página do Discord, com imagens e textos.
* **Header Interativo:** Seção de cabeçalho com título, descrição e botões.
* **Footer:** Seção de rodapé com o logo do Discord.

## 🛠️ Como Executar o Projeto

Para visualizar o projeto, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/DIO-desafio-responsividade.git](https://github.com/seu-usuario/DIO-desafio-responsividade.git)
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd DIO-desafio-responsividade
    ```
3.  **Abra o arquivo `index.html` no seu navegador.**
    * Você pode simplesmente clicar duas vezes no arquivo `index.html` ou arrastá-lo para a janela do seu navegador.

## 📱 Visualizando a Responsividade

Após abrir o `index.html` no navegador:

1.  **No Desktop:**
    * Redimensione a janela do navegador para ver como o layout se adapta.
    * Use as ferramentas de desenvolvedor (geralmente `F12` ou `Ctrl+Shift+I` / `Cmd+Option+I`) para inspecionar os elementos e ver como as `media queries` são aplicadas.

2.  **Para Dispositivos Móveis (Ex: iPhone):**
    * Nas ferramentas de desenvolvedor, clique no ícone de "Toggle device toolbar" (parece um celular e um tablet).
    * Selecione um preset como "iPhone 13" ou "Responsive" e ajuste a largura para simular o dispositivo.

## 📁 Estrutura de Arquivos

.
├── assets/
│   ├── bg-header.svg
│   ├── discord.svg
│   ├── section1.svg
│   ├── section2.svg
│   ├── section3.svg
│   └── section4.svg
├── docs/                 # Pasta para imagens do README (pré-visualizações)
│   ├── desktop_preview.png
│   └── mobile_preview.png
├── index.html            # Estrutura principal da página
└── style.css             # Estilos CSS base para desktop