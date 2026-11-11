[ChocoMagia_50_Chocolates.html](https://github.com/user-attachments/files/34687645/ChocoMagia_50_Chocolates.html)
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ChocoMagia | Chocolates de Natal</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=Playfair+Display:wght@600;700;800&display=swap');
:root{--marrom:#3b211b;--cacau:#63372b;--creme:#fff8ed;--dourado:#e2bd72;--vermelho:#a62f38;--verde:#244a37;--texto:#39251f}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:var(--creme);color:var(--texto);font-family:'DM Sans',Arial,sans-serif}button,input{font:inherit}button,a{-webkit-tap-highlight-color:transparent}a{text-decoration:none;color:inherit}
.topbar{background:#24120f;color:#f4dca8;text-align:center;padding:10px;font-size:.76rem;letter-spacing:.08em}
header{position:sticky;top:0;z-index:10;background:#fffaf2ed;backdrop-filter:blur(12px);display:flex;align-items:center;justify-content:space-between;padding:17px 7%;border-bottom:1px solid #eadcc8}
.logo{font-family:'Playfair Display',Georgia,serif;font-weight:800;color:var(--marrom);font-size:1.4rem}.logo span{color:var(--vermelho)}nav{display:flex;gap:26px;font-size:.9rem}nav a:hover{color:var(--vermelho)}.cart{border:0;background:var(--marrom);color:white;padding:10px 15px;border-radius:25px;cursor:pointer}.menu{display:none;background:none;border:0;font-size:1.5rem}
.hero{background:radial-gradient(circle at 80% 30%,#754636 0,#4b2922 36%,#2a1513 80%);color:#fff8ed;min-height:530px;padding:70px 8%;display:grid;grid-template-columns:1.1fr .9fr;align-items:center;gap:30px;position:relative;overflow:hidden}
.hero:before{content:"";position:absolute;inset:0;background-image:radial-gradient(#f2d99a 1px,transparent 1px);background-size:28px 28px;opacity:.13;pointer-events:none}
.hero-copy{position:relative;z-index:1}.tag{color:var(--dourado);font-size:.72rem;font-weight:bold;letter-spacing:.2em}.hero h1{font-family:'Playfair Display',Georgia,serif;font-size:clamp(2.8rem,5.5vw,5rem);line-height:1.05;margin:20px 0}.hero h1 em{color:var(--dourado);font-weight:600}.hero p{max-width:480px;line-height:1.8;color:#ead8cf}.btn{display:inline-flex;align-items:center;gap:12px;background:var(--dourado);color:#321b16;padding:14px 20px;border:0;border-radius:4px;font-weight:700;cursor:pointer;transition:.2s}.btn:hover{transform:translateY(-3px);box-shadow:0 9px 24px #0003}.rating{font-size:.82rem;color:#ead8cf;margin-top:28px}.rating b{color:var(--dourado);letter-spacing:.1em}
.art{min-height:340px;display:grid;place-items:center;position:relative}.glow{width:min(33vw,330px);aspect-ratio:1;border-radius:50%;background:radial-gradient(circle,#a16d4c,#6b3b2b 65%,#4b2922);border:1px solid #d5b477;box-shadow:0 0 0 18px #ffffff06,0 0 0 40px #ffffff04}
.gift{position:absolute;width:220px;height:185px;background:#d9b577;border:8px solid #f1d59b;transform:rotate(-8deg);box-shadow:20px 25px 35px #16090677;display:grid;place-items:center;color:var(--marrom);text-align:center}
.gift:before{content:"";position:absolute;top:0;bottom:0;width:25px;background:var(--vermelho)}
.gift-inner{position:relative;background:#f8e5bb;padding:17px 24px;border:1px solid #b58a4b;font-family:'Playfair Display',Georgia,serif;font-size:2rem;line-height:1}
.gift-inner small{display:block;font:700 .5rem 'DM Sans',sans-serif;letter-spacing:.18em;margin-bottom:10px}
.floating{position:absolute;background:#fff8ed;color:var(--marrom);padding:12px 15px;box-shadow:0 10px 30px #0002;font-family:'Playfair Display',serif;transform:rotate(-5deg)}.f1{left:0;top:20%}.f2{right:0;bottom:17%;transform:rotate(5deg)}.f1 small,.f2 small{display:block;font: .65rem 'DM Sans',sans-serif;color:#856d5e;margin-top:4px}.spark{position:absolute;color:var(--dourado);font-size:2rem}.s1{top:8%;right:18%}.s2{bottom:9%;left:15%}
section.products{padding:75px 7%}.heading{text-align:center;max-width:720px;margin:0 auto 32px}.eyebrow{color:var(--vermelho);font-size:.72rem;letter-spacing:.18em;font-weight:700}.heading h2,.about h2,.contact h2{font-family:'Playfair Display',Georgia,serif;font-size:clamp(2rem,4vw,3.3rem);margin:12px 0;color:var(--marrom)}.heading h2 em,.about h2 em,.contact h2 em{color:var(--vermelho)}.heading p{color:#826e62;line-height:1.7}
.tools{display:flex;justify-content:center;gap:10px;flex-wrap:wrap;margin:28px 0}.filter{border:1px solid #ddcbbb;background:transparent;color:var(--marrom);border-radius:30px;padding:9px 16px;cursor:pointer}.filter.active,.filter:hover{background:var(--marrom);color:white;border-color:var(--marrom)}.search{display:block;margin:0 auto 30px;max-width:370px;width:100%;padding:13px 17px;border:1px solid #ddcbbb;border-radius:5px;background:white;outline-color:var(--dourado)}
.grid{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:20px}.card{background:white;border:1px solid #eee3d5;border-radius:8px;overflow:hidden;transition:transform .25s,box-shadow .25s}.card:hover{transform:translateY(-7px);box-shadow:0 18px 35px #43251b16}.product-art{height:185px;display:block;background:#f2e3cf;position:relative;overflow:hidden}.product-art img{width:100%;height:100%;display:block;object-fit:cover;transition:transform .35s}.card:hover .product-art img{transform:scale(1.06)}.product-art:after{content:"";position:absolute;width:115px;height:115px;border:1px solid #d8bd91;border-radius:50%}.product-art .pill{z-index:2}.pill{position:absolute;top:12px;left:12px;background:var(--verde);color:white;border-radius:20px;padding:5px 9px;font-size:.65rem;z-index:2}.card-body{padding:17px}.category{font-size:.67rem;color:var(--vermelho);font-weight:700;text-transform:uppercase;letter-spacing:.12em}.card h3{font-family:'Playfair Display',Georgia,serif;margin:8px 0;font-size:1.12rem}.card p{color:#88766d;font-size:.82rem;line-height:1.5;min-height:39px}.card-bottom{display:flex;align-items:center;justify-content:space-between;gap:8px;margin-top:14px}.price{font-weight:700;color:var(--marrom)}.add{border:0;border-radius:50%;background:var(--marrom);color:white;width:38px;height:38px;font-size:1.25rem;cursor:pointer}.add:hover{background:var(--vermelho)}.count{text-align:center;color:#88766d;font-size:.8rem;margin-top:25px}
.about{background:#efe3d3;padding:70px 9%;display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:center}.about-art{min-height:300px;background:linear-gradient(135deg,#64392c,#321a16);border-radius:8px;display:grid;place-items:center;position:relative;overflow:hidden;color:var(--dourado);font-family:'Playfair Display',Georgia,serif;text-align:center}.about-art:before,.about-art:after{content:"✦";position:absolute;font-size:9rem;opacity:.16}.about-art:before{top:-30px;left:10px}.about-art:after{bottom:-40px;right:10px}.cocoa{font-size:4rem}.about-art strong{display:block;font-size:2rem}.about p,.contact p{line-height:1.8;color:#78645a}.about .btn{margin-top:12px}
.contact{padding:70px 9%;display:grid;grid-template-columns:1fr 1fr;gap:55px;align-items:start}.form{background:white;border:1px solid #eee1d1;border-radius:8px;padding:25px;box-shadow:0 12px 35px #43251b0b}.form label{display:block;font-size:.8rem;font-weight:700;margin:13px 0 7px}.form input,.form textarea{width:100%;border:1px solid #e2d4c5;border-radius:4px;padding:12px;outline-color:var(--dourado)}.form textarea{resize:vertical}.form .btn{margin-top:15px}.status{font-size:.82rem;color:var(--verde);min-height:18px}
footer{background:#24120f;color:#e8d8c9;text-align:center;padding:32px 20px;font-size:.8rem}footer .logo{color:#fff3e0}footer p{color:#c5a99a}
.snow{position:fixed;top:-15px;z-index:30;color:white;pointer-events:none;text-shadow:0 0 5px #fff;animation:fall linear forwards}@keyframes fall{to{transform:translateY(110vh) rotate(360deg);opacity:.15}}
.overlay{position:fixed;inset:0;background:#180c0bd9;z-index:50;display:none;justify-content:flex-end}.overlay.open{display:flex}.cart-panel{background:var(--creme);width:min(420px,100%);height:100%;padding:25px;display:flex;flex-direction:column;box-shadow:-15px 0 40px #0002}.cart-head{display:flex;align-items:center;justify-content:space-between;border-bottom:1px solid #e6d8c7}.cart-head h2{font-family:'Playfair Display',serif}.cart-head button{border:0;background:none;font-size:1.3rem;cursor:pointer}.cart-items{overflow:auto;flex:1;padding:15px 0}.cart-item{display:flex;justify-content:space-between;gap:12px;padding:13px 0;border-bottom:1px solid #e6d8c7}.cart-item small{display:block;color:#88766d;margin-top:5px}.remove{border:0;background:none;color:var(--vermelho);cursor:pointer}.total{display:flex;justify-content:space-between;font-size:1.1rem;padding:17px 0}.checkout{width:100%;justify-content:center}.note{text-align:center;font-size:.72rem;color:#8a766a}.empty{text-align:center;color:#88766d;padding:40px 0}
@media(max-width:950px){.grid{grid-template-columns:repeat(2,minmax(0,1fr))}.hero{padding:60px 6%;}.hero-art{min-height:300px}.about,.contact{padding:55px 6%;gap:30px}}
@media(max-width:650px){.topbar{font-size:.65rem}.header{padding:14px 5%;height:70px}.menu{display:block;order:3}.cart{order:2;padding:8px 11px}.nav{display:none;position:absolute;top:70px;left:0;right:0;background:#fff8ed;padding:20px 7%;flex-direction:column;gap:18px;border-bottom:1px solid #eadcc8}.nav.open{display:flex}.hero{grid-template-columns:1fr;padding:50px 7% 30px}.hero h1{font-size:3.1rem}.hero-art{min-height:300px}.glow{width:250px}.gift{width:180px;height:155px}.gift-inner{font-size:1.7rem}.floating{font-size:.8rem}.f1{left:1%}.f2{right:0}.grid{grid-template-columns:1fr 1fr;gap:12px}.product-art{height:135px}.product-art:after{display:none}.card-body{padding:12px}.card h3{font-size:.98rem}.card p{font-size:.76rem}.card-bottom{align-items:center}.price{font-size:.85rem}.add{width:33px;height:33px}.about,.contact{grid-template-columns:1fr;padding:50px 7%}.about-art{min-height:240px}.heading h2{font-size:2.3rem}section.products{padding:55px 5%}}
@media(max-width:380px){.grid{grid-template-columns:1fr}.product-art{height:180px}.hero h1{font-size:2.7rem}}
@media(prefers-reduced-motion:reduce){*,*::before,*::after{scroll-behavior:auto!important;animation-duration:.01ms!important;transition-duration:.01ms!important}}
</style>
</head>
<body>
<div class="topbar">✦ NATAL COM SABOR DE CHOCOLATE ✦ Presentes feitos para encantar</div>
<header>
  <a class="logo" href="#">🍫 Choco<span>Magia</span></a>
  <nav id="nav"><a href="#inicio">Início</a><a href="#produtos">Chocolates</a><a href="#sobre">Nossa história</a><a href="#contato">Contato</a></nav>
  <button class="cart" id="open-cart">🛍️ Sacola <span id="cart-count">0</span></button>
  <button class="menu" id="menu" aria-label="Abrir menu" aria-expanded="false">☰</button>
</header>
<main>
<section class="hero" id="inicio">
  <div class="hero-copy">
    <span class="tag">✧ COLEÇÃO ESPECIAL DE NATAL ✧</span>
    <h1>Um Natal<br>mais <em>delicioso.</em></h1>
    <p>Presentes de chocolate feitos para compartilhar carinho. Descubra trufas, bombons e caixas especiais que deixam a época mais mágica.</p>
    <a class="btn" href="#produtos">Explorar chocolates <span>↗</span></a>
    <div class="rating"><b>★★★★★</b> Feito com carinho em cada detalhe</div>
  </div>
  <div class="art" aria-label="Ilustração decorativa de uma caixa de chocolates">
    <div class="glow"></div><div class="gift"><div class="gift-inner"><small>UMA DOCE SURPRESA</small>Choco<br>Magia ✦</div></div>
    <div class="floating f1">100% amor<small>em cada pedacinho</small></div><div class="floating f2">Feito à mão ♡<small>para presentear</small></div>
    <span class="spark s1">✦</span><span class="spark s2">✧</span>
  </div>
</section>
<section class="products" id="produtos">
  <div class="heading"><span class="eyebrow">NOSSA VITRINE</span><h2>Escolha sua próxima <em>felicidade</em></h2><p>Do clássico ao recheado, temos um docinho para cada momento especial.</p></div>
  <div class="tools" aria-label="Filtros de produtos">
    <button class="filter active" data-filter="Todos">Todos</button><button class="filter" data-filter="Caixas">Caixas presente</button><button class="filter" data-filter="Trufas">Trufas</button><button class="filter" data-filter="Barras">Barras</button><button class="filter" data-filter="Bombons">Bombons</button>
  </div>
  <input class="search" id="search" type="search" placeholder="🔎 Buscar um chocolate..." aria-label="Buscar chocolates">
  <div class="grid" id="grid"></div><p class="count" id="count"></p>
</section>
<section class="about" id="sobre">
  <div class="about-art"><div><div class="cocoa">✦ ✦</div><strong>Um doce carinho</strong><span>em cada detalhe</span></div></div>
  <div><span class="eyebrow">FEITO COM CARINHO</span><h2>Presentear é uma forma de dizer <em>eu me importo.</em></h2><p>A ChocoMagia é uma loja fictícia criada para celebrar o Natal com criatividade, chocolate e presentes cheios de personalidade.</p><p>Nossa ideia é simples: transformar pequenos gestos em lembranças doces. Escolha seu favorito e monte uma sacola cheia de magia!</p><a class="btn" href="#contato">Fale com a gente ↗</a></div>
</section>
<section class="contact" id="contato">
  <div><span class="eyebrow">FAÇA SEU PEDIDO</span><h2>Vamos deixar seu Natal <em>mais doce?</em></h2><p>Envie sua ideia para uma caixa de presente ou uma seleção de chocolates. Este formulário é demonstrativo e não envia dados para um servidor.</p></div>
  <form class="form" id="contact-form"><label for="name">Seu nome</label><input id="name" name="name" required placeholder="Digite seu nome"><label for="email">Seu e-mail</label><input id="email" name="email" type="email" required placeholder="voce@exemplo.com"><label for="message">O que você gostaria?</label><textarea id="message" name="message" rows="3" required placeholder="Quero uma caixa com..."></textarea><button class="btn" type="submit">Enviar mensagem ↗</button><p class="status" id="status" role="status"></p></form>
</section>
</main>
<footer><a class="logo" href="#inicio">🍫 Choco<span>Magia</span></a><p>Que nunca falte chocolate, carinho e magia no seu Natal. 🎄</p><span>© 2026 ChocoMagia · Site demonstrativo para estudo</span></footer>
<div class="overlay" id="overlay" aria-hidden="true"><aside class="cart-panel" aria-label="Carrinho de compras"><div class="cart-head"><h2>Sua sacola 🛍️</h2><button id="close-cart" aria-label="Fechar carrinho">✕</button></div><div class="cart-items" id="cart-items"><p class="empty">Sua sacola ainda está vazia 🍫</p></div><div class="total"><span>Total</span><strong id="total">R$ 0,00</strong></div><button class="btn checkout" id="checkout">Finalizar pedido ↗</button><p class="note">Demonstração: nenhum pagamento será realizado.</p></aside></div>
<script>
const products = [
  {id:1,name:"Caixa Doce Natal",category:"Caixas",price:49.90,emoji:"🎁",desc:"Seleção de chocolates para presentear.",tag:"Mais amado"},
  {id:2,name:"Trufa de Avelã",category:"Trufas",price:7.50,emoji:"🍫",desc:"Recheio cremoso com toque de avelã.",tag:""},
  {id:3,name:"Barra Cacau 70%",category:"Barras",price:16.90,emoji:"🍫",desc:"Sabor intenso para quem ama cacau.",tag:"Clássico"},
  {id:4,name:"Bombons Dourados",category:"Bombons",price:24.90,emoji:"🍬",desc:"Bombons delicados em caixa presenteável.",tag:""},
  {id:5,name:"Trufa de Morango",category:"Trufas",price:7.50,emoji:"🍓",desc:"Chocolate com um toque frutado.",tag:""},
  {id:6,name:"Kit Noel de Chocolate",category:"Caixas",price:59.90,emoji:"🎄",desc:"Um kit festivo para dividir com a família.",tag:"Edição natalina"},
  {id:7,name:"Barra Crocante",category:"Barras",price:13.90,emoji:"🍫",desc:"Chocolate ao leite com crocantes.",tag:""},
  {id:8,name:"Bombons Coração",category:"Bombons",price:19.90,emoji:"❤️",desc:"Pequenos mimos para pessoas especiais.",tag:""},
  {id:9,name:"Caixa Noite Feliz",category:"Caixas",price:69.90,emoji:"✨",desc:"Uma seleção especial para a noite de Natal.",tag:"Especial"},
  {id:10,name:"Trufa de Caramelo",category:"Trufas",price:8.00,emoji:"🍯",desc:"Caramelo macio com cobertura de chocolate.",tag:""},
  {id:11,name:"Barra de Chocolate Branco",category:"Barras",price:14.90,emoji:"🤍",desc:"Doçura suave e textura aveludada.",tag:""},
  {id:12,name:"Bombons de Café",category:"Bombons",price:22.90,emoji:"☕",desc:"Uma combinação elegante de café e cacau.",tag:""},
  {id:13,name:"Trufa de Limão",category:"Trufas",price:7.90,emoji:"🍋",desc:"Recheio cítrico com cobertura de chocolate.",tag:""},
  {id:14,name:"Barra de Chocolate ao Leite",category:"Barras",price:12.90,emoji:"🍫",desc:"O clássico chocolate ao leite.",tag:"Favorito"},
  {id:15,name:"Bombons de Avelã",category:"Bombons",price:23.90,emoji:"🌰",desc:"Bombons com sabor marcante de avelã.",tag:""},
  {id:16,name:"Caixa Estrela de Natal",category:"Caixas",price:54.90,emoji:"⭐",desc:"Chocolates em uma caixa temática de estrela.",tag:""},
  {id:17,name:"Trufa de Maracujá",category:"Trufas",price:7.90,emoji:"🥭",desc:"Recheio cremoso com toque tropical.",tag:""},
  {id:18,name:"Barra de Chocolate Ruby",category:"Barras",price:18.90,emoji:"🍓",desc:"Chocolate rosado com sabor frutado.",tag:"Novidade"},
  {id:19,name:"Bombons de Coco",category:"Bombons",price:20.90,emoji:"🥥",desc:"Chocolate com recheio suave de coco.",tag:""},
  {id:20,name:"Caixa Laço Dourado",category:"Caixas",price:74.90,emoji:"🎀",desc:"Uma seleção elegante para presentear.",tag:"Premium"},
  {id:21,name:"Trufa de Pistache",category:"Trufas",price:9.50,emoji:"💚",desc:"Creme de pistache envolto em chocolate.",tag:""},
  {id:22,name:"Barra com Amêndoas",category:"Barras",price:17.90,emoji:"🌰",desc:"Chocolate com pedaços de amêndoas.",tag:""},
  {id:23,name:"Bombons de Menta",category:"Bombons",price:21.90,emoji:"🌿",desc:"Chocolate com um frescor de menta.",tag:""},
  {id:24,name:"Caixa Mini Delícias",category:"Caixas",price:34.90,emoji:"🍬",desc:"Pequenas porções de vários sabores.",tag:""},
  {id:25,name:"Trufa de Café",category:"Trufas",price:8.50,emoji:"☕",desc:"Ganache com aroma de café.",tag:""},
  {id:26,name:"Barra de Chocolate Meio Amargo",category:"Barras",price:15.90,emoji:"🍫",desc:"Equilíbrio entre cacau e doçura.",tag:""},
  {id:27,name:"Bombons de Cereja",category:"Bombons",price:24.50,emoji:"🍒",desc:"Bombons com delicado toque de cereja.",tag:""},
  {id:28,name:"Caixa Trenó do Noel",category:"Caixas",price:64.90,emoji:"🛷",desc:"Uma caixa divertida para o Natal.",tag:"Temático"},
  {id:29,name:"Trufa de Paçoca",category:"Trufas",price:7.90,emoji:"🥜",desc:"Sabor brasileiro de amendoim e chocolate.",tag:""},
  {id:30,name:"Barra com Castanha",category:"Barras",price:18.50,emoji:"🥜",desc:"Chocolate com castanhas selecionadas.",tag:""},
  {id:31,name:"Bombons de Doce de Leite",category:"Bombons",price:22.50,emoji:"🍮",desc:"Recheio cremoso de doce de leite.",tag:""},
  {id:32,name:"Caixa Bosque Encantado",category:"Caixas",price:79.90,emoji:"🌲",desc:"Seleção especial inspirada no Natal.",tag:"Premium"},
  {id:33,name:"Trufa de Cookies",category:"Trufas",price:8.50,emoji:"🍪",desc:"Chocolate cremoso com pedaços de biscoito.",tag:""},
  {id:34,name:"Barra de Chocolate com Caramelo",category:"Barras",price:16.50,emoji:"🍯",desc:"Chocolate recheado com caramelo macio.",tag:""},
  {id:35,name:"Bombons de Framboesa",category:"Bombons",price:23.50,emoji:"🫐",desc:"Recheio frutado com cobertura de chocolate.",tag:""},
  {id:36,name:"Caixa Pequeno Noel",category:"Caixas",price:29.90,emoji:"🎅",desc:"Uma lembrança doce e divertida.",tag:""},
  {id:37,name:"Trufa de Doce de Leite",category:"Trufas",price:8.00,emoji:"🍮",desc:"Recheio aveludado de doce de leite.",tag:""},
  {id:38,name:"Barra com Flocos de Arroz",category:"Barras",price:13.50,emoji:"🌾",desc:"Textura leve e crocante em cada pedaço.",tag:""},
  {id:39,name:"Bombons de Baunilha",category:"Bombons",price:20.50,emoji:"🌼",desc:"Recheio suave com aroma de baunilha.",tag:""},
  {id:40,name:"Caixa Celebração",category:"Caixas",price:89.90,emoji:"🥂",desc:"Uma seleção generosa para compartilhar.",tag:"Especial"},
  {id:41,name:"Trufa de Amendoim",category:"Trufas",price:7.50,emoji:"🥜",desc:"Creme de amendoim com chocolate.",tag:""},
  {id:42,name:"Barra com Wafer",category:"Barras",price:14.50,emoji:"🍫",desc:"Camadas crocantes de wafer e chocolate.",tag:""},
  {id:43,name:"Bombons de Laranja",category:"Bombons",price:21.50,emoji:"🍊",desc:"Chocolate com toque cítrico de laranja.",tag:""},
  {id:44,name:"Caixa Magia de Cacau",category:"Caixas",price:69.50,emoji:"✨",desc:"Mix de chocolates para surpreender.",tag:""},
  {id:45,name:"Trufa de Coco",category:"Trufas",price:7.90,emoji:"🥥",desc:"Recheio de coco com cobertura de chocolate.",tag:""},
  {id:46,name:"Barra com Caramelo Salgado",category:"Barras",price:17.50,emoji:"🧂",desc:"Combinação de chocolate e caramelo salgado.",tag:""},
  {id:47,name:"Bombons de Canela",category:"Bombons",price:21.90,emoji:"🌟",desc:"Bombons aromáticos com toque de canela.",tag:""},
  {id:48,name:"Caixa Família Feliz",category:"Caixas",price:99.90,emoji:"🎁",desc:"Uma caixa grande para dividir com todos.",tag:"Mais vendido"},
  {id:49,name:"Trufa de Chocolate Branco",category:"Trufas",price:8.20,emoji:"🤍",desc:"Ganache de chocolate branco.",tag:""},
  {id:50,name:"Barra Natalina com Frutas",category:"Barras",price:19.90,emoji:"🎄",desc:"Chocolate com frutas secas para o Natal.",tag:"Edição natalina"}
];
// Fotografias reais de chocolates (Unsplash). As imagens carregam pela internet.
const chocolatePhotos = {
  Caixas: [
    'https://images.unsplash.com/photo-1549465220-1a8b9238cd48?auto=format&fit=crop&w=700&q=85',
    'https://images.unsplash.com/photo-1511381939415-e44015466834?auto=format&fit=crop&w=700&q=85',
    'https://images.unsplash.com/photo-1549465220-1a8b9238cd48?auto=format&fit=crop&w=700&q=85'
  ],
  Trufas: [
    'https://images.unsplash.com/photo-1606313564200-e75d5e30476c?auto=format&fit=crop&w=700&q=85',
    'https://images.unsplash.com/photo-1548907040-4d42f8f3e1f5?auto=format&fit=crop&w=700&q=85',
    'https://images.unsplash.com/photo-1549007953-2f2dc0b24019?auto=format&fit=crop&w=700&q=85'
  ],
  Barras: [
    'https://images.unsplash.com/photo-1548907040-4d42f8f3e1f5?auto=format&fit=crop&w=700&q=85',
    'https://images.unsplash.com/photo-1606313564200-e75d5e30476c?auto=format&fit=crop&w=700&q=85',
    'https://images.unsplash.com/photo-1511381939415-e44015466834?auto=format&fit=crop&w=700&q=85'
  ],
  Bombons: [
    'https://images.unsplash.com/photo-1549007953-2f2dc0b24019?auto=format&fit=crop&w=700&q=85',
    'https://images.unsplash.com/photo-1606313564200-e75d5e30476c?auto=format&fit=crop&w=700&q=85',
    'https://images.unsplash.com/photo-1548907040-4d42f8f3e1f5?auto=format&fit=crop&w=700&q=85'
  ]
};
const productPhoto = p => { const photos = chocolatePhotos[p.category] || chocolatePhotos.Trufas; return photos[(p.id - 1) % photos.length]; };
const money = n => n.toLocaleString('pt-BR',{style:'currency',currency:'BRL'});
let filter = 'Todos';
let cart = [];
const grid = document.querySelector('#grid');
function renderProducts(){
 const q = document.querySelector('#search').value.trim().toLocaleLowerCase('pt-BR');
 const list = products.filter(p => (filter==='Todos'||p.category===filter) && (p.name.toLocaleLowerCase('pt-BR').includes(q)||p.desc.toLocaleLowerCase('pt-BR').includes(q)));
 grid.innerHTML = list.length ? list.map(p=>`<article class="card"><div class="product-art"><img src="${productPhoto(p)}" alt="Fotografia de chocolate para ${p.name}" loading="lazy" onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1606313564200-e75d5e30476c?auto=format&fit=crop&w=700&q=85';">${p.tag?`<span class="pill">${p.tag}</span>`:''}</div><div class="card-body"><span class="category">${p.category}</span><h3>${p.name}</h3><p>${p.desc}</p><div class="card-bottom"><span class="price">${money(p.price)}</span><button class="add" data-add="${p.id}" aria-label="Adicionar ${p.name} à sacola">+</button></div></div></article>`).join('') : '<p class="empty" style="grid-column:1/-1">Nenhum chocolate encontrado. Tente outra busca 🍫</p>';
 document.querySelector('#count').textContent = `Mostrando ${list.length} de ${products.length} chocolates`;
}
document.querySelectorAll('.filter').forEach(b=>b.addEventListener('click',()=>{document.querySelectorAll('.filter').forEach(x=>x.classList.remove('active'));b.classList.add('active');filter=b.dataset.filter;renderProducts()}));
document.querySelector('#search').addEventListener('input',renderProducts);
grid.addEventListener('click',e=>{const b=e.target.closest('[data-add]');if(!b)return;const p=products.find(x=>x.id===Number(b.dataset.add));cart.push(p);renderCart();b.textContent='✓';setTimeout(()=>{if(b.isConnected)b.textContent='+'},700)});
function renderCart(){
 document.querySelector('#cart-count').textContent=cart.length;
 document.querySelector('#total').textContent=money(cart.reduce((sum,p)=>sum+p.price,0));
 document.querySelector('#cart-items').innerHTML=cart.length?cart.map((p,i)=>`<div class="cart-item"><div><strong>${p.emoji} ${p.name}</strong><small>${money(p.price)}</small></div><button class="remove" data-remove="${i}">Remover</button></div>`).join(''):'<p class="empty">Sua sacola ainda está vazia 🍫</p>';
}
document.querySelector('#cart-items').addEventListener('click',e=>{const b=e.target.closest('[data-remove]');if(!b)return;cart.splice(Number(b.dataset.remove),1);renderCart()});
const overlay=document.querySelector('#overlay');
function openCart(){overlay.classList.add('open');overlay.setAttribute('aria-hidden','false')}
function closeCart(){overlay.classList.remove('open');overlay.setAttribute('aria-hidden','true')}
document.querySelector('#open-cart').addEventListener('click',openCart);document.querySelector('#close-cart').addEventListener('click',closeCart);
overlay.addEventListener('click',e=>{if(e.target===overlay)closeCart()});
document.querySelector('#checkout').addEventListener('click',()=>alert(cart.length?`Seu pedido de demonstração ficou em ${money(cart.reduce((s,p)=>s+p.price,0))}. Nenhum pagamento foi realizado.`:'Adicione algum chocolate à sua sacola primeiro!'));
document.querySelector('#menu').addEventListener('click',()=>{const nav=document.querySelector('#nav');nav.classList.toggle('open');document.querySelector('#menu').setAttribute('aria-expanded',nav.classList.contains('open'))});
document.querySelectorAll('#nav a').forEach(a=>a.addEventListener('click',()=>{document.querySelector('#nav').classList.remove('open');document.querySelector('#menu').setAttribute('aria-expanded','false')}));
document.querySelector('#contact-form').addEventListener('submit',e=>{e.preventDefault();document.querySelector('#status').textContent=`Obrigado, ${document.querySelector('#name').value.trim()}! Sua mensagem de demonstração foi registrada na página.`;e.target.reset()});
function snow(){const flake=document.createElement('span');flake.className='snow';flake.textContent=Math.random()>.5?'❄':'✦';flake.style.left=Math.random()*100+'vw';flake.style.fontSize=(8+Math.random()*12)+'px';flake.style.opacity=(.35+Math.random()*.6).toFixed(2);flake.style.animationDuration=(6+Math.random()*7)+'s';document.body.appendChild(flake);setTimeout(()=>flake.remove(),14000)}
renderProducts();renderCart();setInterval(snow,450);
</script>
</body>
</html>
