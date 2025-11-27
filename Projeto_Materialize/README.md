🎨 Landing Page: Materialize Parallax

Projeto desenvolvido na disciplina de Desenvolvimento Front-End, explorando o poder dos Frameworks CSS.

📖 Sobre o Projeto

Este projeto consiste em uma Landing Page Responsiva desenvolvida com o framework Materialize CSS. O foco principal foi a implementação do efeito Parallax (rolagem com profundidade) e a utilização de componentes pré-estilizados para acelerar o desenvolvimento de interfaces modernas e adaptáveis.

O layout segue o conceito Mobile First, garantindo uma experiência fluida em dispositivos móveis antes de adaptar para desktops.

🚀 Funcionalidades & Componentes

O código explora diversos recursos interativos e visuais do Materialize:

$$x$$

 Efeito Parallax: Imagens de fundo com rolagem assíncrona, criando imersão visual.

$$x$$

 Navbar Responsiva: Menu de navegação que se transforma automaticamente:

Desktop: Links horizontais à direita.

Mobile: Menu "hambúrguer" lateral (Sidenav) com ativação via JavaScript.

$$x$$

 Grid System Fluido: Sistema de colunas (col s12 m4) para alinhamento de conteúdo.

$$x$$

 Cards & Ícones: Apresentação de serviços/vantagens utilizando Google Material Icons.

$$x$$

 Footer Semântico: Rodapé estruturado com links de navegação e copyright.

📂 Estrutura de Arquivos

A organização do projeto segue as boas práticas de separação de responsabilidades:

Projeto_Materialize/
│
├── css/
│   ├── materialize.min.css  # Estilos Core do Framework
│   └── estilos.css          # Personalizações (Custom CSS)
│
├── js/
│   ├── materialize.min.js   # Scripts Core (Sidenav, Parallax)
│   └── configuracoes.js     # Inicialização dos componentes (jQuery)
│
├── imagens/
│   ├── imagen01.jpg
│   ├── imagen02.jpg
│   └── ...
│
└── index.html               # Estrutura Semântica Principal


💻 Exemplo de Código (Grid System)

O layout utiliza classes utilitárias para controlar a largura dos elementos em diferentes telas:

<!-- Comportamento Responsivo:
     s12 = Ocupa 12 colunas (100%) em telas pequenas (Small)
     m4  = Ocupa 4 colunas (33%) em telas médias/grandes (Medium+) -->

<div class="row">
    <div class="col s12 m4">
        <div class="icon-block">
            <h2 class="center brown-text"><i class="material-icons">flash_on</i></h2>
            <h5 class="center">Alta Performance</h5>
            <p class="light">Carregamento otimizado utilizando minificação CSS.</p>
        </div>
    </div>
    <!-- ... outros blocos ... -->
</div>


🛠️ Tecnologias Utilizadas

HTML5: Estruturação semântica do conteúdo.

Materialize CSS: Framework front-end baseado no Material Design do Google.

JavaScript / jQuery: Manipulação do DOM e inicialização de componentes dinâmicos.

Google Fonts: Tipografia e Ícones vetoriais.

⚙️ Como Executar Localmente

Clone o repositório ou baixe o ZIP dos arquivos.

Mantenha a estrutura de pastas (css, js, imagens) inalterada para não quebrar os caminhos.

Abra o arquivo index.html em seu navegador de preferência (Chrome, Firefox, Edge).

Dica: Para visualizar o site em modo mobile, pressione F12 e ative o modo de dispositivo (Ctrl+Shift+M).
