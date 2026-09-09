# 💌 Retrospectiva Polaroid – Declare seu Amor com Estilo!

<p align="center">
  <a href="https://jimmykiedis.github.io/Duarda/">
    <img src="https://img.shields.io/badge/❤️%20Live%20Demo-FF4B4B?style=for-the-badge" alt="Live Demo">
  </a>
  <br>
  <em>Clique na imagem para acessar a demonstração.</em>
</p>

---

Este é um mini-projeto em HTML, CSS e JavaScript criado para **declarar seu amor de um jeito especial**! 🥰  
Você pode mostrar fotos em estilo *polaroid*, adicionar uma música de fundo 🎵 e incluir mensagens ou recordações que marcaram a história de vocês. Tudo em uma vibe nostálgica e única! 📸✨

---

## 🎯 Objetivo

Este projeto foi feito com o coração ❤️ para ser um **presente interativo e emocional**, ideal para:

- Datas especiais: aniversário de namoro, casamento, dia dos namorados etc.
- Pedidos de namoro ou casamento
- Declarações espontâneas de amor
- Presentes criativos para quem você ama

---

## ✨ Funcionalidades

- Exibição de fotos em estilo polaroid
- Efeito de "revelação" ao clicar na imagem
- Navegação com botões ⬅️ ➡️ para avançar/voltar fotos
- Possibilidade de adicionar uma música de fundo ❤️🎶
- Totalmente personalizável com suas mensagens e lembranças

---

## 🛠 Como utilizar o repositório

1. Clone ou baixe este repositório.

```bash
git clone https://github.com/jimmykiedis/Duarda.git
cd EscapeButtonPrank
```

2. Coloque suas imagens na pasta `contents/` (ex: `roll1.png`, `roll2.png`, etc.).
3. (Opcional) Adicione uma música de fundo no HTML usando `<audio>`.
4. Personalize as mensagens ou adicione textos em balões, abaixo das fotos, etc.
5. Abra o `index.html` no navegador e curta a magia. ✨

---

## 🏗️ Estratégia de implementação

A aplicação é estruturada principalmente com **HTML, CSS e JavaScript**, utilizando elementos convencionais do DOM para construir e controlar a experiência interativa.

### Interface (HTML/CSS)

Responsável pela estrutura e apresentação dos elementos da página, como:

- Galeria de fotos em formato polaroid.
- Exibição de imagens e mensagens.
- Botões de navegação entre as fotos.
- Controle de reprodução e pausa da música.
- Animações e efeitos visuais.
- Elementos decorativos, como corações flutuantes.

### Lógica e interação (JavaScript)

O JavaScript controla toda a dinâmica da aplicação, incluindo:

- Carregamento das imagens a partir de um arquivo `JSON`.
- Carregamento das mensagens a partir de um arquivo `TXT`.
- Sincronização entre cada imagem e sua respectiva mensagem.
- Navegação entre as fotos por botões e gestos de arrastar.
- Interação por mouse e dispositivos touch.
- Alternância entre a frente e o verso do polaroid.
- Controle da reprodução da música de fundo.
- Criação dinâmica de corações e efeitos visuais.
- Atualização do conteúdo da página sem a necessidade de recarregá-la.

Essa abordagem mantém a aplicação simples e organizada, separando o **conteúdo personalizável**, armazenado em arquivos externos, da **lógica responsável pela interação e apresentação da experiência**.

---

## 🛠️ Tecnologias

* HTML5
* CSS3
* JavaScript (Vanilla)
* Fetch API
* JSON
* Web Audio API / HTMLAudioElement
* DOM API
* Touch Events API

---

## 💡 Estrutura sugerida
```
/
├── index.html
├── style.css
├── script.js
└── contents/
    ├── roll1.png
    ├── roll2.png
    └── music.mp3 (opcional)
```

---

## ❤️ Dica especial

> Se o amor fosse código, esse projeto seria um commit inesquecível no repositório do coração. 💾💘

---

## 📄 Licença

Sinta-se à vontade para usar, editar e compartilhar! Espalhe amor por onde for. 🫡

