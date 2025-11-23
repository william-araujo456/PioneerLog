# Projeto Base de Conhecimento - Pioneiros da Ciência da Computação

Olá, seja bem-vindo(a)! 👋

Este projeto é uma página web interativa que funciona como uma base de conhecimento sobre os pioneiros e pioneiras da ciência da computação, desenvolvido durante as aulas da Imersão Dev com Google Gemini da Alura. Para a sua construção, foi utilizada a extensão Gemini Code Assist no Visual Studio Code, auxiliando no desenvolvimento do código. As informações sobre cada personalidade são carregadas dinamicamente a partir de um arquivo de dados, permitindo uma fácil manutenção e expansão do conteúdo.

## 🚀 Linguagens e Funcionalidades

*   **HTML:** Responsável pela estrutura semântica da página, organizando o conteúdo como títulos, parágrafos e os contêineres onde as informações são exibidas.

*   **CSS:** Utilizado para estilização da página e cards, tornando a apresentação visualmente agradável, coesa e responsiva para diferentes tamanhos de tela.

*   **JavaScript:** É o principal responsável pela interatividade e dinamismo da página. Suas funções no projeto incluem:
    *   Leitura de dados do arquivo `data.json` de forma assíncrona.
    *   Gerar e inserir dinamicamente os cards de cada pioneiro no HTML.
    *   Manipular eventos, como a implementação de futuras funcionalidades de busca ou filtro por tags.

*   **JSON:** Formato de arquivo escolhido para armazenar e organizar os dados dos pioneiros ( imagem, nome, período, descrição e tags.) de forma estruturada, leve e de fácil leitura.