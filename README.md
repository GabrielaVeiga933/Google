# Google (Bootstrap)

Este é um projeto de recriação simples da *página inicial do Google, feito apenas com **HTML + Bootstrap via CDN*.  
A ideia foi demonstrar domínio de *grid, utilitários, formulários e componentes do Bootstrap*, sem usar CSS ou JS extra além do necessário.

## 🚀 Tecnologias usadas
- *HTML5* (estrutura semântica: <header>, <main>, <footer>)
- *Bootstrap 5.3* via CDN (grid, flexbox, utilitários de espaçamento, tipografia e botões)
- *JavaScript inline básico* (event.preventDefault()) para evitar refresh da página no envio do formulário

## 📱 Responsividade
- *Mobile (≤576px):* links do rodapé empilham em coluna.
- *Tablet/Desktop:* rodapé fica em 2 colunas, links lado a lado.
- Conteúdo principal centralizado vertical e horizontalmente em qualquer viewport.

## 🧩 Estrutura
- *Header:* navbar simples com links “Gmail” e “Imagens” alinhados à direita.
- *Main:* logo fake (feito com spans coloridos) + barra de pesquisa (form-control rounded-pill) + dois botões (btn btn-light).
- *Footer:* dividido em 2 colunas de links, responsivo com grid.

## ♿ Acessibilidade
- Campo de busca com **label oculto (visually-hidden).
- Uso de **aria-label** para descrever o input de pesquisa.
- Ordem de tabulação natural e coerente.

## 🎮 Como testar
1. Baixe/clonar este repositório.
2. Abra o arquivo index.html no navegador.
3. Digite algo no campo de busca e clique nos botões → nada será enviado (graças ao event.preventDefault()).

