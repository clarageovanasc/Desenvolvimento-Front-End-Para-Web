🚁 Helicópteros de Luxo (Avaliação A1)

Projeto web desenvolvido como avaliação prática (A1) da disciplina de Front-End. O site é uma landing page para uma loja de helicópteros de luxo, integrando localização em tempo real via API e navegação adaptável para dispositivos móveis.

📱 Funcionalidades do Projeto

1. Mapa Interativo (API Leaflet)

O sistema consome a API Leaflet.js para renderizar um mapa dinâmico focado na "Cidade Aeroviária".

Tecnologia: Tiles do OpenStreetMap.

Marcador Personalizado: Pinpoint nas coordenadas exatas da loja (-15.87198, -47.91970) com popup informativo.

Link Externo: Botão para abrir a localização no mapa ampliado.

2. Navegação Responsiva (Mobile-First)

Implementação de um Menu Hambúrguer funcional para dispositivos móveis.

JavaScript: Manipulação do DOM para alternar as classes .show e .active no menu.

Links: Navegação interna para os modelos (Eurocopter, Bell, Mercedes).

3. Layout Semântico

Estrutura HTML5 moderna dividida em seções claras:

<nav>: Barra de navegação com logo e links.

<section id="coluna-section">: Destaque visual do produto.

<section id="map-section">: Área de contato e localização.

<footer>: Redes sociais e direitos autorais.

💻 Destaques do Código

Integração do Mapa

Trecho do código JavaScript responsável por instanciar o mapa e adicionar o marcador:

const cidadeAeroviaria = [-15.87198, -47.91970];
const map = L.map('map').setView(cidadeAeroviaria, 14);

// Camada do OpenStreetMap
L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: 'Mapa da Cidade Aeroviária © OpenStreetMap contributors'
}).addTo(map);

// Marcador com Popup
L.marker(cidadeAeroviaria)
    .addTo(map)
    .bindPopup('<b>Rua Sem Número</b><br>Centro da Cidade Aeroviária.')
    .openPopup();


Menu Mobile (Toggle)

Lógica simples e eficiente para abrir/fechar o menu em telas pequenas:

menuToggle.addEventListener('click', () => {
  menu.classList.toggle('show');       // Mostra a lista de links
  menuToggle.classList.toggle('active'); // Anima o ícone do hambúrguer
});


🛠️ Tecnologias Utilizadas

HTML5: Estrutura da página.

CSS3: Estilização (arquivo estilos.css).

JavaScript (ES6): Interatividade do menu e configurações do mapa.

Leaflet.js: Biblioteca open-source para mapas interativos.

⚙️ Como Executar

Baixe o projeto.

Certifique-se de estar conectado à internet (para carregar o script do Leaflet e os mapas).

Abra o arquivo index.html no navegador.
