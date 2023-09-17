<html lang="Br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Sua Página de Venda</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://static.vecteezy.com/ti/vetor-gratis/p3/15634808-conexao-hud-circular-com-fundo-de-site-moderno-futurista-de-placa-de-circuito-ou-de-pagina-de-capa-para-conceito-de-tecnologia-e-financas-e-futura-empresa-de-educacao-vetor.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-color: #f0f0f0; /* Cor de fundo de fallback */
        }
        
        header.page-header {
            background-color: #2e6677;
            color: #fff;
            text-align: center;
            padding: 10px;
            background-color: rgba(0, 0, 0, 0.7); /* Cor de fundo com transparência */
            text-shadow: 2px 2px 4px rgba(5, 6, 5, 0.7);
        }
        .page-header h1 {
            font-size: 69px;
            font-family: 'Bebas Neue', cursive;
            color: #FF5733;
            text-transform: uppercase;
            margin: 0;
            padding: 20px; /* Aumentar o espaçamento interno */
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.041);
        }
        .tabs {
            display: flex;
            justify-content: space-between;
            background-color: #16181a9a;
            color: #fff;
            padding: 10px 0;
        }
        .tab {
            flex: 1;
            text-align: center;
            padding: 10px;
            cursor: pointer;
        }
        .tab:hover {
            background-color: #ffffff8f;
        }
        .product-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-top: 7px;
        }
        .product {
            width: calc(20% - 20px);
            margin-right: 20px;
            margin-bottom: 20px;
            padding: 15px;
            background-color: #ffffff6c;
            box-shadow: 0 0px 2px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
            display: inline-block;
            box-sizing: border-box;
            height: 493px; /* Defina a altura fixa desejada para os produtos */
            overflow: hidden; /* Oculta qualquer conteúdo que exceda a altura fixa */
            position: relative;
        }
        
        .product:hover {
            transform: scale(1.05);
        }
        .product img {
            max-width: 90%;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 8px;
        }
        .product-title {
            font-size: 19px;
            margin-bottom: 10px;
            color: #333;
        }
        .product-description {
            margin-bottom: 5px;
            color: hsl(180, 100%, 88%);
            font-size: 16px;
        }
        .buy-button {
            background-color: #013279;
            color: #fff;
            padding: 9px 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            text-decoration: none;
            display: block;
            text-align: center;
        }
        .buy-button:hover {
            background-color: #05041a;
        }
        .logo {
            text-align: center;
            margin-bottom: 20px;
        }
        .logo h1 {
            font-size: 36px;
            color: #333;
        }
        /* Estilos adicionais aqui */
        .spotify-player {
            border-radius: 5px;
            width: 38%;
            height: 80px;
        }
        .product-price {
            font-size: 24px; /* Tamanho da fonte */
            font-weight: bold; /* Deixar em negrito */
            color: #FF5733; /* Cor do texto */
            margin-top: 10px; /* Espaçamento superior */
        }
        /* Estilos para telas pequenas (por exemplo, smartphones) */
@media (max-width: 768px) {
    /* Estilos para telas menores aqui */
}

/* Estilos para telas médias (por exemplo, tablets) */
@media (min-width: 769px) and (max-width: 1024px) {
    /* Estilos para telas médias aqui */
}

/* Estilos para telas grandes (por exemplo, desktops) */
@media (min-width: 1025px) {
    /* Estilos para telas grandes aqui */
}

    </style>
</head>
<body>
    <header class="page-header">
        <h1 style="font-size: 72px; font-weight: bold; color: #FF5733; text-transform: uppercase; text-shadow: 3px 3px 5px rgba(5, 6, 5, 0.7);">Compras Online</h1>
    </header>
    
    <!-- Adicione o player do Spotify no canto esquerdo do topo da página -->
    <iframe class="spotify-player" src="https://open.spotify.com/embed/playlist/5HeGcD3F9k02tiXGjnnCVe?utm_source=generator&theme=0" frameborder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

    <p style="text-align: center; margin-top: 10px; font-weight: bold; color: #fffefe;">Todos os produtos do site são produtos afiliados à lojas com entregas em todo o território Brasileiro.</p>

    
    <div class="tabs">
        <div class="tab" onclick="showProducts('inicio')">👜Inicio</div>
        <div class="tab" onclick="showProducts('utilitarios')">🖇️Utilitários</div>
        <div class="tab" onclick="showProducts('academia')">🏋️‍♂️Academia</div>
        <div class="tab" onclick="showProducts('celulares')">📱Celulares</div>
        <a href="https://calistenico.github.io/cursos/" target="_blank">💡Cursos</a>
        <div class="tab" onclick="showProducts('diversos')">🛠️em construção🛠️</div>
    </div>
    
    <!-- Produtos -->
    <div class="product-list">
        <div class="product inicio">
            <img src="https://a-static.mlcdn.com.br/800x560/drone-e88-pro-com-camera-dupla-4k-full-hd-wifi-bag-eachine/yourbrand/ab0f153e28bb11ee82bd4201ac18502e/ba3f3b2dbbd73990e240016485a03064.jpeg" alt="Produto 1">
            <h2 class="product-title">Drone E88 Pro Com Câmera</h2>
            <p class="product-description">Câmera Dupla 4k Full Hd Wifi + Bag - Eachine</p>
            <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/drone-e88-pro-com-camera-dupla-4k-full-hd-wifi-bag-eachine/p/gee5b50bde/cf/drcm/" class="buy-button">Comprar</a>
            <p class="product-price">R$ 209,99</p>
        </div>
        
        <div class="product inicio">
            <img src="https://a-static.mlcdn.com.br/800x560/notebook-asus-vivobook-15-intel-core-i5-8gb-256gb-ssd-156-windows-11-x1500ea-ej3669w/magazineluiza/236969100/928f265c7de4b89b6c5d8e182c1a1400.jpg" alt="Produto 2">
            <h2 class="product-title">Notebook Asus Vivobook 15 Intel Core i5 8GB</h2>
            <p class="product-description">256GB SSD 15,6” Windows 11</p>
            <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/notebook-asus-vivobook-15-intel-core-i5-8gb-256gb-ssd-156-windows-11-x1500ea-ej3669w/p/236969100/in/note/" class="buy-button">Comprar</a>
            <p class="product-price">R$ 2.519,10</p>
        </div>
        
        <div class="product inicio">
            <img src="https://a-static.mlcdn.com.br/800x560/notebook-hp-intel-core-i3-8gb-256gb-ssd-156-windows-11-256-g9/magazineluiza/237612600/df27aed794efdc381c97f0924a6dd705.jpg" alt="Produto 3">
            <h2 class="product-title">Notebook HP Intel Core i3 8GB</h2>
            <p class="product-description">256GB SSD 15,6” - Windows 11 256 G9</p>
            <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/notebook-hp-intel-core-i3-8gb-256gb-ssd-156-windows-11-256-g9/p/237612600/in/note/" class="buy-button">Comprar</a>
            <p class="product-price">R$ 2.339,10</p>
        </div>
        <!-- Adicione mais produtos conforme necessário -->
            
            <div class="product inicio">
                <img src="https://a-static.mlcdn.com.br/800x560/impressora-multifuncional-hp-deskjet-ink-advantage-2774-thermal-inkjet-colorida-wi-fi-usb/magazineluiza/135301200/0b79be11f1cbb43e27294897322b72d5.jpg" alt="Produto 4">
                <h2 class="product-title">Impressora Multifuncional HP</h2>
                <p class="product-description">Deskjet Ink Advantage - 2774 Thermal Inkjet Colorida Wi-Fi USB</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/impressora-multifuncional-hp-deskjet-ink-advantage-2774-thermal-inkjet-colorida-wi-fi-usb/p/135301200/in/ipmf/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 296,67</p>
            </div>
            
            <div class="product inicio">
                <img src="https://a-static.mlcdn.com.br/800x560/ring-light-de-mesa-blogueira-portatil-luminaria-de-led-6-polegadas-tripe-de-16-cm-right/webeletronicos/ring252/ab3242a91f2e9e71d1da0581fec2c0bc.jpeg" alt="Produto 4">
                <h2 class="product-title">Ring Light de Mesa Blogueira Portátil</h2>
                <p class="product-description">Luminária De Led 6 Polegadas + Tripé De 16 Cm Right</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/ring-light-de-mesa-blogueira-portatil-luminaria-de-led-6-polegadas-tripe-de-16-cm-right/p/bc966fgega/te/lzsf/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 47,41</p>
            </div>
            
            <div class="product inicio">
                <img src="https://a-static.mlcdn.com.br/800x560/smart-watch-inteligente-w59-pro-relogio-masculino-feminino-android-watch-9-bluetooth-ios-2023/importsth/w59branco/6c1efd3b97dae0bf9e806cdb8faabf2e.jpeg" alt="Produto 4">
                <h2 class="product-title">Smart Watch Inteligente W59 Pro</h2>
                <p class="product-description">Relógio Masculino Feminino Android Watch 9 Bluetooth iOS 2023</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/smart-watch-inteligente-w59-pro-relogio-masculino-feminino-android-watch-9-bluetooth-ios-2023/p/bab5g24he5/te/smtw/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 270,00</p>
            </div>
            
            <div class="product inicio">
                <img src="https://a-static.mlcdn.com.br/800x560/carregador-portatil-20000-mah-power-bank-3em1-bateria-portable-charger/lojamagazinezerox/16010550087/03e9197776cdf3a7c566cf7e45143008.jpeg" alt="Produto 4">
                <h2 class="product-title">Carregador Portátil 20000 mah Power Bank</h2>
                <p class="product-description">3em1 Bateria - Portable Charger</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/carregador-portatil-20000-mah-power-bank-3em1-bateria-portable-charger/p/hj086gd56g/te/accp/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 158,70</p>
            </div>
            
            <div class="product inicio">
                <img src="https://a-static.mlcdn.com.br/800x560/jogo-de-panelas-eirilar-antiaderente-de-aluminio-grafite-14-pecas-especial/magazineluiza/235128200/3593fc92689b0a99b3f512e3f0ec5f50.jpg" alt="Produto 4">
                <h2 class="product-title">Jogo de Panelas Eirilar Antiaderente</h2>
                <p class="product-description">de Alumínio - Grafite 14 Peças Especial</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/jogo-de-panelas-eirilar-antiaderente-de-aluminio-grafite-14-pecas-especial/p/235128200/ud/cjpn/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 296,64</p>
            </div>
            
            <div class="product inicio">
                <img src="https://a-static.mlcdn.com.br/800x560/fritadeira-eletrica-sem-oleo-air-fryer-mondial-new-pratic-af-31-preta-35l-com-timer/magazineluiza/236479400/fed9f79e3ae2933812f99b8a3527c92d.jpg" alt="Produto 4">
                <h2 class="product-title">Fritadeira Elétrica sem Óleo</h2>
                <p class="product-description">Air Fryer Mondial - New Pratic AF-31 Preta 3,5L com Timer</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/fritadeira-eletrica-sem-oleo-air-fryer-mondial-new-pratic-af-31-preta-35l-com-timer/p/236479400/ep/frel/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 296,64</p>
            </div>
            
            <div class="product inicio">
                <img src="https://a-static.mlcdn.com.br/800x560/kit-kt-105-b-mondial-com-liquidificador-batedeira-espremedor/magazineluiza/023004200/1a6a4b1f8d50cf9fb7074195a63847d6.jpg" alt="Produto 4">
                <h2 class="product-title">Kit KT-105-B Mondial com Liquidificador Batedeira - Espremedor</h2>
                <p class="product-description">Para quem procura mais praticidade na cozinha, o kit de eletroportáteis é o ideal,</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/kit-kt-105-b-mondial-com-liquidificador-batedeira-espremedor/p/023004200/ep/elkp/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 248,64</p>
            </div>
            
            <div class="product inicio">
                <img src="https://a-static.mlcdn.com.br/800x560/cafeteira-nescafe-dolce-gusto-genio-s-basic-branca-automatica-110v-nescafe-dolce-gusto/nescafedolcegustooficial/b54bd6742413c85c707780988d01c728/8ec3dcad75e6f77a2b8b8ad9702bf8e0.jpeg" alt="Produto 4">
                <h2 class="product-title">Cafeteira Nescafe Dolce Gusto Genio</h2>
                <p class="product-description">S Basic Branca Automática (110v) - Nescafé Dolce Gusto</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/cafeteira-nescafe-dolce-gusto-genio-s-basic-branca-automatica-110v-nescafe-dolce-gusto/p/be24942g85/ep/ceac/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 390,51</p>
            </div>
            
            <div class="product inicio">
                <img src="https://a-static.mlcdn.com.br/800x560/escova-secadora-mondial-golden-rose-1200w-ceramica-turmalina/magazineluiza/236598400/76925a6a00f1a24c7f67394d70e18ef9.jpg" alt="Produto 4">
                <h2 class="product-title">Escova Secadora Mondial</h2>
                <p class="product-description">Golden Rose 1200W - Cerâmica Turmalina</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/escova-secadora-mondial-golden-rose-1200w-ceramica-turmalina/p/236598400/pf/esse/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 118,87</p>
            </div>
            
            <div class="product inicio">
                <img src="https://a-static.mlcdn.com.br/800x560/secador-de-cabelos-mondial-max-travel-sc-10-bivolt-1200w/loibrasil/13354/5ae2726103727eeb11d15b93f9492923.jpeg" alt="Produto 4">
                <h2 class="product-title">Secador de Cabelos Mondial Max Travel</h2>
                <p class="product-description">SC-10 Bivolt 1200w</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/secador-de-cabelos-mondial-max-travel-sc-10-bivolt-1200w/p/eaa1h5g6d5/pf/psec/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 62,99</p>
            </div>
            
            <div class="product inicio">
                <img src="https://a-static.mlcdn.com.br/800x560/kit-invigo-nutri-enrich-shampoo-condicionador-mascara-e-oil-reflections-wella-professionals/beautypack/12443933843/b3468767fe94927848a400ff4134075f.jpeg" alt="Produto 4">
                <h2 class="product-title">Kit Invigo Nutri Enrich</h2>
                <p class="product-description">Shampoo, Condicionador, Máscara e Oil Reflections - Wella Professionals</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/kit-invigo-nutri-enrich-shampoo-condicionador-mascara-e-oil-reflections-wella-professionals/p/gj82d53fa1/pf/kipr/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 228,00</p>
            </div>
            
            <div class="product inicio">
                <img src="https://a-static.mlcdn.com.br/800x560/bebe-conforto-cosco-1-posicao-wizz-0-a-13kg/magazineluiza/236178300/983b47136fb9f6432845f147c4d347da.jpg" alt="Produto 4">
                <h2 class="product-title">Bebê Conforto Cosco</h2>
                <p class="product-description">1 Posição Wizz 0 a 13kg</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/bebe-conforto-cosco-1-posicao-wizz-0-a-13kg/p/236178300/bb/bcft/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 315,24</p>
            </div>
            
            <!-- Celulares -->
            
            <div class="product celulares">
                <img src="https://a-static.mlcdn.com.br/800x560/smartphone-samsung-galaxy-m14-5g-128gb-4gb-ram-tela-infinita-de-6-6-dual-chip/samsung/4370/9f642072f7f55bf75c2c13cf1f381ec2.jpeg" alt="Produto 4">
                <h2 class="product-title">Smartphone Samsung Galaxy M14 5G</h2>
                <p class="product-description">128GB, 4GB RAM, Tela Infinita de 6.6" Dual Chip</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/smartphone-samsung-galaxy-m14-5g-128gb-4gb-ram-tela-infinita-de-6-6-dual-chip/p/aa1k3ckcg1/te/galx/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 934,15</p>
            </div>
            
            <div class="product celulares">
                <img src="https://a-static.mlcdn.com.br/800x560/smartphone-samsung-galaxy-m54-5g-256gb-8gb-ram-tela-infinita-de-6-7-dual-chip/samsung/4431/937659c4f4b9839fae31e21ad7a817db.jpeg" alt="Produto 4">
                <h2 class="product-title">Smartphone Samsung Galaxy M54 5G, 256GB</h2>
                <p class="product-description">8GB RAM, Tela Infinita de 6.7" Dual Chip</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/smartphone-samsung-galaxy-m54-5g-256gb-8gb-ram-tela-infinita-de-6-7-dual-chip/p/ega70e5b5j/te/galx/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 1.699,15</p>
            </div>
            
            <div class="product celulares">
                <img src="https://a-static.mlcdn.com.br/800x560/iphone-13-apple-128gb-azul-tela-6-1-camera-dupla-12mp-selfie-12mp-mlpk3br-a/kabum/388376/6b2c6ecfc310b147ca16b3e1d42d8660.jpeg" alt="Produto 4">
                <h2 class="product-title">Iphone 13 Apple 128GB Azul</h2>
                <p class="product-description">Tela 6.1", Câmera Dupla 12MP + Selfie 12MP</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/iphone-13-apple-128gb-azul-tela-6-1-camera-dupla-12mp-selfie-12mp-mlpk3br-a/p/fg4f12a5j7/te/ip13/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 4.464,99</p>
            </div>
            
            <div class="product celulares">
                <img src="https://a-static.mlcdn.com.br/800x560/apple-iphone-13-128gb-meia-noite/lojaiplace/220842/ebfcd9151db97c8a0dae82bf8c80457d.jpeg" alt="Produto 4">
                <h2 class="product-title">Apple iPhone 13 128GB</h2>
                <p class="product-description">128GB - Meia-noite</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/apple-iphone-13-128gb-meia-noite/p/jaf036k5a9/te/ip13/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 5.166,00</p>
            </div>
            

            <div class="product celulares">
                <img src="https://a-static.mlcdn.com.br/800x560/smartphone-samsung-galaxy-a03-core-32gb-cobre-octa-core-4G-2gb-ram-65-cam-8mp-selfie-5mp/magazineluiza/235402300/3567e90e407fe2f3165950e295411d6a.jpg" alt="Produto 2">
                <h2 class="product-title">Smartphone Samsung Galaxy A03 Core 32GB</h2>
                <p class="product-description">Cobre Octa-Core 4G 2GB RAM 6,5” Câm. 8MP + Selfie 5MP</p>
                <p class="product-price">R$ 599,00</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/smartphone-samsung-galaxy-a03-core-32gb-cobre-octa-core-4g-2gb-ram-65-cam-8mp-selfie-5mp/p/235402300/te/ga03/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product celulares">
                <img src="https://a-static.mlcdn.com.br/800x560/smartphone-samsung-galaxy-a14-128gb-prata-4G-octa-core-4gb-ram-66-cam-tripla-selfie-13mp-dual-chip/magazineluiza/236721300/a7de84679d7776257846bcfe4255e77c.jpg" alt="Produto 3">
                <h2 class="product-title">Smartphone Samsung Galaxy A14 128GB</h2>
                <p class="product-description">Prata 4G Octa-Core 4GB RAM 6,6" Câm. Tripla + Selfie 13MP Dual Chip</p>
                <p class="product-price">R$ 879,00</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/smartphone-samsung-galaxy-a14-128gb-prata-4g-octa-core-4gb-ram-66-cam-tripla-selfie-13mp-dual-chip/p/236721300/te/ga14/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product celulares">
                <img src="https://a-static.mlcdn.com.br/800x560/smartphone-samsung-galaxy-a23-128gb-preto-5g-octa-core-4gb-ram-66-cam-quadrupla-selfie-8mp/magazineluiza/236591600/117d334db8b0f246cf5ff79f63059bc3.jpg" alt="Produto 4">
                <h2 class="product-title">Smartphone Samsung Galaxy A23 128GB</h2>
                <p class="product-description">Preto 5G Octa-Core 4GB RAM 6,6” Câm. Quádrupla + Selfie 8MP</p>
                <p class="product-price">R$ 1.259,10</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/smartphone-samsung-galaxy-a23-128gb-preto-5g-octa-core-4gb-ram-66-cam-quadrupla-selfie-8mp/p/236591600/te/ga23/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product celulares">
                <img src="https://a-static.mlcdn.com.br/800x560/smartphone-samsung-galaxy-a34-128gb-preto-5g-octa-core-6gb-ram-66-cam-tripla-selfie-13mp-dual-chip/magazineluiza/236822000/ae9f6793ae5b65eed65659776d7b94d5.jpg" alt="Produto 4">
                <h2 class="product-title">Smartphone Samsung Galaxy A34 128GB</h2>
                <p class="product-description">Preto 5G Octa-Core 6GB RAM 6,6" Câm. Tripla + Selfie 13MP Dual Chip</p>
                <p class="product-price">R$ 1.799,10</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/smartphone-samsung-galaxy-a34-128gb-preto-5g-octa-core-6gb-ram-66-cam-tripla-selfie-13mp-dual-chip/p/236822000/te/galx/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product celulares">
                <img src="https://a-static.mlcdn.com.br/800x560/smartphone-samsung-galaxy-a54-128gb-preto-5g-octa-core-8gb-ram-64-cam-tripla-selfie-32mp-dual-chip/magazineluiza/236822300/71ab6f0517a5a6b0c1cdb403e7c5473d.jpg" alt="Produto 1">
                <h2 class="product-title">Smartphone Samsung Galaxy A54 128GB</h2>
                <p class="product-description">Preto 5G Octa-Core 8GB RAM 6,4" Câm. Tripla + Selfie 32MP Dual Chip</p>
                <p class="product-price">R$ 1.799,10</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/smartphone-samsung-galaxy-a54-128gb-preto-5g-octa-core-8gb-ram-64-cam-tripla-selfie-32mp-dual-chip/p/236822300/te/galx/" class="buy-button">Comprar</a>
            </div>
            
            <!-- utilitarios -->
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/serra-tico-tico-850w-3000rpm-20mm-ws3772-wesco/barataoferramentas1/ws3772-220v/c232a630e27a36188f9662e1c87742df.jpeg" alt="Produto 4">
                <h2 class="product-title">Serra Tico Tico 850w 3000rpm</h2>
                <p class="product-description">3000rpm 20mm Base ajustável para cortes angulares</p>
                <p class="product-price">R$ 319,99</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/serra-tico-tico-850w-3000rpm-20mm-ws3772-wesco/p/da9c0h7a36/fs/fttc/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/grampeador-de-tapeceiro-alta-pressao-profissional-com-caixa-de-grampos-gorillaz/tmacessorios/469/88f6917ec120329bbd609932c79b8147.jpeg" alt="Produto 4">
                <h2 class="product-title">Grampeador De Tapeceiro Alta Pressão Profissional</h2>
                <p class="product-description">Profissional Com Caixa de Grampos - Gorillaz</p>
                <p class="product-price">R$ 56,61</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/grampeador-de-tapeceiro-alta-pressao-profissional-com-caixa-de-grampos-gorillaz/p/cg6d967a3c/fs/gpml/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/serra-circular-7-1-4-black-decker-cs1350p-1-350w/mundoautomacao/007092-000001/107cf7972721fe57580c8d5971d085a1.jpeg" alt="Produto 4">
                <h2 class="product-title">Serra Circular 7 1/4 Black Decker</h2>
                <p class="product-description">Black Decker CS1350P 1.350W</p>
                <p class="product-price">R$ 548,10</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/serra-circular-7-1-4-black-decker-cs1350p-1-350w/p/aaega38hjk/fs/fcir/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/caixa-de-ferramentas-sanfonada-7-gavetas-50cm-presto-91802/atlasferramentaseparafusos/15851534876/f0335f246032205f6edcf7d8afd79c94.jpg" alt="Produto 4">
                <h2 class="product-title">Caixa de Ferramentas Sanfonada</h2>
                <p class="product-description">Caixa de Ferramentas Sanfonada 7 Gavetas 50cm PRESTO</p>
                <p class="product-price">R$ 177,50</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/caixa-de-ferramentas-sanfonada-7-gavetas-50cm-presto-91802/p/fb0219315f/fs/cbdf/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/camera-ip-lampada-wifi-full-hd-visao-noturna-yoosee-jortan/lojasmkstore/15961204863/fe91e012ae93e87e4503332f80216690.jpeg" alt="Produto 4">
                <h2 class="product-title">Câmera Ip Lâmpada Wifi Full Hd</h2>
                <p class="product-description">Visão Noturna Yoosee - Jortan</p>
                <p class="product-price">R$ 58,41</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/camera-ip-lampada-wifi-full-hd-visao-noturna-yoosee-jortan/p/hec66c9ef7/cj/caip/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/camera-externa-ip-prova-d-agua-infravermelho-externa-wifi-hd-ip-camera/clicamundo/185p/233407a53aebfd9c194b8c859b110300.jpeg" alt="Produto 4">
                <h2 class="product-title">Câmera Externa Ip Prova D'água Infravermelho</h2>
                <p class="product-description">Externa Wifi Hd - IP CAMERA</p>
                <p class="product-price">R$ 140,80</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/camera-externa-ip-prova-d-agua-infravermelho-externa-wifi-hd-ip-camera/p/khcj29451j/cj/caip/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/fita-led-5m-ultra-rgb-2835-fonte-controle-dubai-iluminacao/dubaiimportadoraedistribuidora/822325/f7e0c8d27153cd29e4a220e4820518bd.jpeg" alt="Produto 4">
                <h2 class="product-title">Fita Led 5m Ultra Rgb</h2>
                <p class="product-description">Rgb 2835 + Fonte + Controle - Dubai - Iluminação</p>
                <p class="product-price">R$ 23,74</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/fita-led-5m-ultra-rgb-2835-fonte-controle-dubai-iluminacao/p/dk5efe62g7/cj/fted/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/kit-completo-mecanismo-descarga-para-caixa-acoplada-globalplastic/bronzauttoferr/6924739/ec5bee9355e824e2c1f846f56997556a.jpeg" alt="Produto 4">
                <h2 class="product-title">Kit Completo Mecanismo Descarga</h2>
                <p class="product-description">Para Caixa Acoplada Globalplastic</p>
                <p class="product-price">R$ 58,41</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/kit-completo-mecanismo-descarga-para-caixa-acoplada-globalplastic/p/jafjhc1kd2/cj/mcca/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/pilha-alcalina-aa-pequena-duracell-16-unidades/magazineluiza/220300400/9e9d00b40e7510de7420914729198a81.jpg" alt="Produto 4">
                <h2 class="product-title">Pilha Alcalina AA Pequena Duracell</h2>
                <p class="product-description">16 unidades</p>
                <p class="product-price">R$ 69,99</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/pilha-alcalina-aa-pequena-duracell-16-unidades/p/220300400/cj/ilha/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/kit-ferramentas-nell-142-pecas-com-maleta/magazineluiza/227731800/71c45ac8eebd8679b864007df364e2f5.jpg" alt="Produto 4">
                <h2 class="product-title">Kit Ferramentas Nell 142 Peças</h2>
                <p class="product-description">com Maleta</p>
                <p class="product-price">R$ 76,41</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/kit-ferramentas-nell-142-pecas-com-maleta/p/227731800/fs/fjgf/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/kit-jogo-de-ferramentas-129-pecas-c-maleta-completo-sparta/ddmaquinas/38851/431d7e0d1e23d0e587c59a03d18ed1b9.jpeg" alt="Produto 4">
                <h2 class="product-title">Kit Jogo De Ferramentas 129 Peças</h2>
                <p class="product-description"> C/ Maleta Completo - Sparta</p>
                <p class="product-price">R$ 98,00</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/kit-jogo-de-ferramentas-129-pecas-c-maleta-completo-sparta/p/fa5b4h4hea/fs/fjgf/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/jogo-de-ferramentas-46-pecas-com-soquetes-titanium-kit-chave/ddmaquinas/64112/b96664cbc2c860c6d2420e3bfe20c2d3.jpeg" alt="Produto 4">
                <h2 class="product-title">Jogo De Ferramentas 46 Peças</h2>
                <p class="product-description">Com Soquetes Titanium + Kit Chave</p>
                <p class="product-price">R$ 53,21</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/jogo-de-ferramentas-46-pecas-com-soquetes-titanium-kit-chave/p/gdh8g58g91/fs/fjgf/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/kit-ferramentas-c-200-pcs-titanium-linha-profissional/destaksorocaba/19546/4f105fcaa1eb521fe87dcb034444f721.jpeg" alt="Produto 4">
                <h2 class="product-title">Kit Ferramentas C/200 Pçs</h2>
                <p class="product-description">Titanium Linha Profissional</p>
                <p class="product-price">R$ 78,90</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/kit-ferramentas-c-200-pcs-titanium-linha-profissional/p/kb4kj8eg1c/fs/fjgf/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/kit-ferramentas-de-bits-fenda-e-soquetes-41-pecas-titanium/ddmaquinas/75444/ea791a5e50546021ad9842084bd5632a.jpeg" alt="Produto 4">
                <h2 class="product-title">Kit Ferramentas De Bits</h2>
                <p class="product-description"> Fenda E Soquetes 41 Peças Titanium</p>
                <p class="product-price">R$ 20,81</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/kit-ferramentas-de-bits-fenda-e-soquetes-41-pecas-titanium/p/fedbbbdj6f/fs/fjgf/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/tablet-mirage-7-polegadas-quad-core-32gb-preto-2018/obaboxtecnologia/16331/d08dc5560c2d0bd426ced0840be1e1c1.jpeg" alt="Produto 4">
                <h2 class="product-title">Tablet Mirage 7 Polegadas</h2>
                <p class="product-description">Quad Core 32GB Preto - 2018</p>
                <p class="product-price">R$ 303,91</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/tablet-mirage-7-polegadas-quad-core-32gb-preto-2018/p/hcjjf64kfh/tb/tbtm/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/geladeira-brastemp-frost-free-duplex-375-litros-cor-branca-brm44hb/whirlpool/2004473/af1abd69d23ade569c872eda21d62403.jpeg" alt="Produto 4">
                <h2 class="product-title">Geladeira Brastemp Frost Free 375 Litros</h2>
                <p class="product-description">Branca 220V</p>
                <p class="product-price">R$ 2.849,05</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/geladeira-brastemp-frost-free-duplex-375-litros-cor-branca-brm44hb/p/548997600/ed/refr/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/fogao-4-bocas-de-piso-itatiaia-star-acendimento-automatico-bivolt-branco-ou-preto/techshop/fogita00009/8c8ddc0c24e1ca1cef748f8626bad23a.jpeg" alt="Produto 4">
                <h2 class="product-title">Fogão 4 Bocas De Piso Itatiaia Star Acendimento Automático</h2>
                <p class="product-description">Branco ou Preto</p>
                <p class="product-price">R$ 689,35</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/fogao-4-bocas-de-piso-itatiaia-star-acendimento-automatico-bivolt-branco-ou-preto/p/hjf881277h/ed/fg4b/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/cervejeira-eos-bierhaus-100-litros-black-glass-frost-free-ece120-110v/frigelar2/kit8867/14a53f7ce85f01f0b8c06158caa7f7be.jpeg" alt="Produto 4">
                <h2 class="product-title">Cervejeira EOS Bierhaus 100 Litros</h2>
                <p class="product-description">Black Glass Frost Free ECE120 110V</p>
                <p class="product-price">R$ 1.847,31</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/cervejeira-eos-bierhaus-100-litros-black-glass-frost-free-ece120-110v/p/bb7c7eckg1/ed/cedo/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/lavadora-de-roupas-electrolux-lac12-12kg-cesto-inox-12-programas-de-lavagem/magazineluiza/010557100/06a573c6264c67fd51ad6cf618a7e744.jpg" alt="Produto 4">
                <h2 class="product-title">Máquina de Lavar Roupas Electrolux 12kg</h2>
                <p class="product-description"> 12Kg Cesto Inox 12 Programas de Lavagem</p>
                <p class="product-price">R$ 1.907,26</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/lavadora-de-roupas-electrolux-lac12-12kg-cesto-inox-12-programas-de-lavagem/p/010557100/ed/lava/" class="buy-button">Comprar</a>
            </div>
            
            <div class="product utilitarios">
                <img src="https://a-static.mlcdn.com.br/800x560/forno-eletrico-de-embutir-44l-decorato-mueller-110v-preto/multmaxx/13142/bfb706e9ad9e509e855dcfd1c32cb721.jpeg" alt="Produto 4">
                <h2 class="product-title">Forno Elétrico De Embutir 44l Brastemp</h2>
                <p class="product-description">Grill</p>
                <p class="product-price">R$ 1.059,90</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/forno-eletrico-de-embutir-44l-decorato-mueller-220v-preto/p/ekeh1079c1/ed/frne/" class="buy-button">Comprar</a>
            </div>
            





              <!-- Academia -->
            
              <div class="product academia">
                <img src="https://a-static.mlcdn.com.br/1500x1500/radiofrequencia-foton-ems-eletroporacao-mesoterapia-rejuvene/pool/9885508256/91c169214218c1685978db00d5f3a841.jpeg" alt="Produto 4">
                <h2 class="product-title">Radiofrequência Fóton Ems Eletroporação</h2>
                <p class="product-description">Eletroporação Mesoterapia Rejuvene</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/radiofrequencia-foton-ems-eletroporacao-mesoterapia-rejuvene/p/ddck781985/cp/medc/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 229,00</p>
            </div>
            
            <div class="product academia">
                <img src="https://a-static.mlcdn.com.br/800x560/bomba-de-encher-bolas-de-futebol-futsal-futevolei-basquete-boia-colete-bogu/bogustore/15906118497/0b7e4de285b591f0b33ceee9f31f6d3c.jpeg" alt="Produto 4">
                <h2 class="product-title">Bomba De Encher Bolas</h2>
                <p class="product-description">Bolas de Futebol Futsal Futevôlei Basquete Boia Colete</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/bomba-de-encher-bolas-de-futebol-futsal-futevolei-basquete-boia-colete-bogu/p/jbfk1hgah8/es/bdrb/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 6,71</p>
            </div>
            
            <div class="product academia">
                <img src="https://a-static.mlcdn.com.br/800x560/kit-11-extensor-elastico-treino-em-casa-kit-5-mini-band-resistance-belt/utilcomvariedades/15472841779/067504ed53af93bd9c6e108fe0677bca.jpeg" alt="Produto 4">
                <h2 class="product-title">Kit 11 Extensor Elástico Treino Em Casa</h2>
                <p class="product-description"> Kit 5 Mini Band - RESISTANCE BELT</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/kit-11-extensor-elastico-treino-em-casa-kit-5-mini-band-resistance-belt/p/jhj958327b/es/ktee/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 42,66</p>
            </div>
            
            
            <div class="product academia">
                <img src="https://a-static.mlcdn.com.br/800x560/aparelho-massagem-muscular-4-eletrodos-therapy-machine-utimix/wwmvariedades/18219/b824b91e6ce9f994f365878c6a014d5a.jpeg" alt="Produto 4">
                <h2 class="product-title">Aparelho Massagem Muscular</h2>
                <p class="product-description">4 Eletrodos Therapy Machine - Utimix</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/aparelho-massagem-muscular-4-eletrodos-therapy-machine-utimix/p/jhg16401cc/es/tnfm/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 38,40</p>
            </div>
            
            <div class="product academia">
                <img src="https://a-static.mlcdn.com.br/800x560/jump-profissional-com-aro-de-reforco-suporta-ate-180-kg-i4/i4store/ef9c16fc2ce611ecb1f64201ac185049/c6a65685f6ed338e92faf1d3a6b53afc.jpeg" alt="Produto 4">
                <h2 class="product-title">Jump Profissional </h2>
                <p class="product-description">Com Aro De Reforço Suporta Até 180 Kg</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/jump-profissional-com-aro-de-reforco-suporta-ate-180-kg-i4/p/fff4c4kkk8/es/tdac/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 219,99</p>
            </div>
            
            <div class="product academia">
                <img src="https://a-static.mlcdn.com.br/800x560/bicicleta-aluminio-aro-29-ksw-shimano-tz-24-vel-ltx-krw20/krwbikes/krw20-azul-preto-19/72e4249ca0eff21fba19fbf3dc7016ed.jpeg" alt="Produto 4">
                <h2 class="product-title">Bicicleta Alumínio Aro 29</h2>
                <p class="product-description">Ksw Shimano TZ 24 Vel Ltx KRW20</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/bicicleta-aluminio-aro-29-ksw-shimano-tz-24-vel-ltx-krw20/p/fkc7967e77/es/elbk/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 926,10</p>
            </div>
            
            <div class="product academia">
                <img src="https://a-static.mlcdn.com.br/800x560/tenis-adidas-breaknet-feminino/netshoes/nqq-4379-028-34/2ba09ac1bb02f4186ecca5da914b6239.jpeg" alt="Produto 4">
                <h2 class="product-title">Tênis Adidas Breaknet</h2>
                <p class="product-description">tenis femenino</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/tenis-adidas-breaknet-feminino/p/abh13d740k/es/tees/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 197,99</p>
            </div>
            
            <div class="product academia">
                <img src="https://a-static.mlcdn.com.br/800x560/tenis-adidas-breaknet-masculino/netshoes/nqq-4378-026-43/0e9c9361870f224a5676bf8611609e11.jpeg" alt="Produto 4">
                <h2 class="product-title">Tênis Adidas Breaknet</h2>
                <p class="product-description">tenis masculino</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/tenis-adidas-breaknet-masculino/p/fb5007ga8a/es/tees/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 197,99</p>
            </div>
            
            <div class="product academia">
                <img src="https://a-static.mlcdn.com.br/800x560/colchao-de-ar-inflavel-de-casal-com-vinil-aveludado-confortavel-resistente-compacto-belfix/autoequip1/15851961547/4c2b5a24d14c53db1854ec8485371c72.jpeg" alt="Produto 4">
                <h2 class="product-title">Colchão de Ar Inflável de Casal </h2>
                <p class="product-description">Com Vinil Aveludado Confortável Resistente Compacto - Belfix</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/colchao-de-ar-inflavel-de-casal-com-vinil-aveludado-confortavel-resistente-compacto-belfix/p/kjkccce468/es/coif/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 127,92</p>
            </div>
            
            <div class="product academia">
                <img src="https://a-static.mlcdn.com.br/800x560/joelheira-compressao-protecao-ajustavel-fitness-cross-acp-variedades/acpvariedadesltda-me/1104/f4d39546beab3bd9959b96fb70c6eb68.jpeg" alt="Produto 4">
                <h2 class="product-title">Joelheira Compressão Proteção Ajustável Fitness</h2>
                <p class="product-description">Fitness Cross - ACP VARIEDADES</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/joelheira-compressao-protecao-ajustavel-fitness-cross-acp-variedades/p/bck89h5060/es/jlps/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 28,43</p>
            </div>
            
            <div class="product academia">
                <img src="https://a-static.mlcdn.com.br/800x560/lona-de-salto-para-cama-elastica-305-m-ou-310-m-canguri-quadricolor-nacional/mamibrinquedos/1667/131fbe29b3b392a7702191478f65eb47.jpeg" alt="Produto 4">
                <h2 class="product-title">Lona de Salto Para Cama Elástica</h2>
                <p class="product-description">3,05 m ou 3,10 m Canguri Quadricolor Nacional</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/lona-de-salto-para-cama-elastica-305-m-ou-310-m-canguri-quadricolor-nacional/p/kh3j697hka/es/lcel/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 455,87</p>
            </div>
            
            <div class="product academia">
                <img src="https://a-static.mlcdn.com.br/800x560/silicone-spray-para-lubrificar-esteiras-natural-fitness/naturalfitnessartesportivos/9393692697/689eda9c887d1aad6fe41f16595db03d.jpeg" alt="Produto 4">
                <h2 class="product-title">Silicone Spray Para Lubrificar Esteiras</h2>
                <p class="product-description">Natural Fitness</p>
                <a href="https://www.parceiromagalu.com.br/magazinedropshippingon/silicone-spray-para-lubrificar-esteiras-natural-fitness/p/dh56082368/es/lest/" class="buy-button">Comprar</a>
                <p class="product-price">R$ 22,39</p>
            </div>
            




                    
            
            <section class="contact">
                <h2 class="section-title">Contato</h2>
                <p>Entre em contato conosco nas redes sociais:</p>
                <ul class="social-links">
                <li><a href="https://www.instagram.com/o_tal_do_pirata_ofc" target="_blank">Instagram</a></li>
                <li><a href="https://wa.me/48999626351" target="_blank">WhatsApp</a></li>
                <li><a href="https://www.facebook.com/" target="_blank">Facebook</a></li>
                </ul>
             </section>
 
            



            <!-- Adicione mais produtos conforme necessário -->
            
        </div>

    <script>
        function showProducts(category) {
            const products = document.querySelectorAll('.product');
            products.forEach(product => {
                if (product.classList.contains(category)) {
                    product.style.display = 'block';
                } else {
                    product.style.display = 'none';
                }
            });
        }

        showProducts('inicio');
    </script>
</body>
</html>
