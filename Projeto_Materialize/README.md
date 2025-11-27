🎨 Landing Page com Materialize CSS

Projeto desenvolvido para explorar o uso de Frameworks CSS, focando na agilidade de desenvolvimento e padronização visual. O objetivo foi criar uma Landing Page moderna com efeito Parallax e design totalmente responsivo.

🚀 Funcionalidades Implementadas

O código utiliza diversos componentes interativos do Materialize:

[x] Efeito Parallax: Imagens de fundo com rolagem assíncrona para profundidade visual.

[x] Navbar Responsiva: Menu que se adapta automaticamente para Mobile (Sidenav com ícone de hambúrguer) e Desktop.

[x] Grid System: Uso de colunas (col s12 m4) para alinhar ícones e textos de forma fluida.

[x] Ícones: Integração com a biblioteca Google Material Icons.

[x] Footer: Rodapé estruturado com links e informações de copyright.

💻 Exemplo de Código (Grid System)

O layout foi construído pensando no conceito Mobile First. Veja como as colunas se comportam:

<!-- No celular ocupa 12 colunas (s12), no tablet/desktop ocupa 4 (m4) -->
<div class="col s12 m4">
    <div class="icon-block">
        <h2 class="center brown-text"><i class="material-icons">flash_on</i></h2>
        <h5 class="center">Velocidade</h5>
        <p class="light">Texto descritivo...</p>
    </div>
</div>


🛠️ Tecnologias Utilizadas

HTML5: Estrutura semântica.

Materialize CSS: Framework visual (Minified CSS).

JavaScript / jQuery: Para ativação dos scripts de animação (Parallax e Sidenav).

Google Fonts: Tipografia e Ícones.

⚙️ Como Executar

Baixe a pasta do projeto.

Certifique-se de que as pastas css, js e imagens estão no mesmo local do index.html.

Abra o arquivo index.html em qualquer navegador moderno.

Projeto desenvolvido na disciplina de Desenvolvimento Front-End.
