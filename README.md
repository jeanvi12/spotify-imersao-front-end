# 🎵 Spotify Clone

<img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExbGN0MDhkZDgyaTNldzM2eXFkNmd5NDdrczN3OXhzaGJjNjZlM2FmbyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/10YpWPBU7GAYwM/giphy.gif" width="150" alt="gato com fones dançando">

Um clone da interface principal do Spotify desenvolvido durante a Imersão Front-End da Alura.

## 📋 Sobre o Projeto

Este projeto é uma réplica visual e funcional da interface do Spotify, incluindo a navegação lateral, exibição de playlists e funcionalidade de busca de artistas.

## 🚀 Tecnologias Utilizadas

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="20" height="20"/> **HTML5** - Estruturação da página

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="20" height="20"/> **CSS3** - Estilização completa com arquivos modularizados

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="20" height="20"/> **JavaScript** - Interatividade e consumo de API

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original-wordmark.svg" width="20" height="20"/> **API REST** - Consumo de dados de artistas via fetch API

😉**Font Awesome** - Ícones utilizados na interface

## ✨ Funcionalidades

- **Navegação Lateral** - Menu lateral com acesso a Início, Busca e Biblioteca
- **Seções de Playlists** - Exibição de cards de playlists categorizados
- **Barra de Busca** - Pesquisa de artistas em tempo real
- **Layout Responsivo** - Adaptação para diferentes tamanhos de tela
- **Visualização de Artistas** - Exibição de dados dos artistas ao pesquisar
- **Indeia importande**❗- Os artistas que estão dentro da API fake são: Foo Fighters, Michael Jackson,
 Emicida, Chitãozinho e Xororó, Mc Coringa, Arlindo Cruz e Caetano Veloso

## 🔍 Como Funciona

O usuário pode navegar pelas playlists disponíveis na página principal. Ao digitar o nome de um artista na barra de pesquisa, o sistema faz uma requisição à API, retornando e exibindo os dados do artista correspondente, incluindo nome e imagem.

## 🧩 Estrutura do Projeto

```
└── 📁 spotify-clone
    ├── 📄 index.html             # Estrutura principal da página
    ├── 📄 script.js              # Lógica de busca e exibição
    ├── 📁 api-artists            # API local de artistas
    │   └── 📄 artists.json       # Dados dos artistas
    └── 📁 src
        ├── 📁 assets             # Imagens e ícones
        └── 📁 styles             # Arquivos CSS
            ├── 📄 reset.css
            ├── 📄 vars.css
            ├── 📄 sidebar-footer.css
            ├── 📄 main-content.css
            └── 📄 media-queries.css
```

## 💻 Como Executar

1. Clone o repositório
2. Inicie um servidor JSON para a API de artistas:
   ```
   npx json-server --watch api-artists/artists.json --port 3000
   ```
3. Abra o arquivo `index.html` em seu navegador

## 🎓 Aprendizados

Projeto desenvolvido durante a Imersão Front-End da Alura, com foco em:
- Estruturação semântica com HTML
- Estilização modular com CSS
- Manipulação do DOM com JavaScript
- Consumo de APIs com fetch
- Layouts responsivos

---

🚧 Projeto para fins educacionais, desenvolvido como parte do treinamento da Alura.
