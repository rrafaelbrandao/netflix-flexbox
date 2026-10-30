# 🎬 Netflix Flexbox

## 🚀 Sobre o projeto

O **Netflix Flexbox** é um projeto prático de desenvolvimento front-end inspirado na experiência de navegação da Netflix. Ele reúne páginas de entrada, login, seleção de perfil, catálogo, detalhes de título e reprodução em uma interface temática e responsiva.

O projeto foi desenvolvido com **HTML5 e CSS3**, com foco em estrutura semântica, organização visual e uso de **Flexbox** para alinhar e distribuir os elementos.

> Este é um projeto educacional de demonstração, sem integração com os serviços ou a conta real da Netflix.

## ✨ Páginas e recursos

- **Página inicial:** apresenta a marca, links de navegação, chamada de assinatura e uma seleção de títulos em alta.
- **Login:** formulário visual com campos de e-mail e senha, opção para lembrar do usuário e links de apoio.
- **Seleção de perfil:** exibe quatro perfis para continuar a navegação.
- **Catálogo:** reúne destaques e categorias de filmes, com opções para abrir detalhes ou assistir.
- **Detalhes:** apresenta informações de *Stranger Things*, botões de ação e sugestões de títulos.
- **Assistir:** inclui um player incorporado do YouTube, metadados e uma fileira de conteúdos relacionados.
- **Navegação entre páginas:** links HTML conectam as telas em um fluxo simples, da página inicial à reprodução.
- **Interações visuais:** efeitos de hover, transições e estados de foco ajudam a indicar elementos interativos.
- **Layout responsivo:** folhas de estilo incluem adaptações para telas de celular e tablet.

## 🛠️ Tecnologias

- **HTML5** para a estrutura e o conteúdo das páginas.
- **CSS3** para estilos, layouts com Flexbox, transições e media queries.
- **Google Fonts (Inter)** para a tipografia.
- **YouTube Embed** como player incorporado na página de reprodução.

Não há dependências de frameworks de interface ou JavaScript no projeto.

## 📁 Estrutura do projeto

```text
netflix-flexbox/
├── index.html
├── pages/
│   ├── login.html
│   ├── profiles.html
│   ├── home.html
│   ├── details.html
│   └── watch.html
├── css/
│   ├── style.css
│   ├── login.css
│   ├── profiles.css
│   ├── home.css
│   ├── details.css
│   └── watch.css
└── assets/
    ├── icons/
    └── images/
        ├── poster-horizontal/
        └── poster-vertical/
```

## ▶️ Como executar

1. Baixe ou clone este repositório.
2. Abra a pasta do projeto no editor de sua preferência.
3. Abra `index.html` diretamente no navegador ou use uma extensão como **Live Server** no VS Code.

A página `watch.html` carrega um vídeo incorporado do YouTube e requer conexão com a internet para exibi-lo. As fontes do Google também são carregadas externamente; sem conexão, o navegador usará a fonte alternativa definida no CSS.

## 🧭 Fluxo de navegação

```text
index.html → login.html → profiles.html → home.html → details.html → watch.html
```

## ✍️ Autor

Desenvolvido por **Rafael Brandão Nunes** como projeto prático para estudo e demonstração de habilidades em desenvolvimento front-end.
