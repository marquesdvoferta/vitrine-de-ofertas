
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Vitrine de Ofertas | Achados para Campo, Casa e Lazer</title>
<meta name="description" content="Encontre listas e produtos selecionados para caça esportiva, arco e flecha, pesca, campo, casa, tecnologia e lazer. Acesse nossas indicações no Mercado Livre.">
<meta name="keywords" content="Vitrine de Ofertas, caça esportiva, arco e flecha, besta, carabina de pressão, chumbinho, pesca, produtos rurais, ofertas Mercado Livre">
<meta name="author" content="Vitrine de Ofertas">
<meta name="robots" content="index, follow">
<meta name="theme-color" content="#17251d">
<link rel="canonical" href="https://marquesdvoferta.github.io/">

<meta property="og:type" content="website">
<meta property="og:title" content="Vitrine de Ofertas">
<meta property="og:description" content="Achados selecionados para campo, casa, lazer e tecnologia.">
<meta property="og:url" content="https://marquesdvoferta.github.io/">

<style>
:root {
    --verde: #203b2c;
    --verde-escuro: #14251c;
    --verde-claro: #385c43;
    --dourado: #d7b56d;
    --creme: #f5f1e8;
    --branco: #fff;
    --texto: #26332a;
    --cinza: #6c776f;
    --borda: #e6e9e4;
    --sombra: 0 12px 35px rgba(0,0,0,.12);
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: 90px;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    color: var(--texto);
    line-height: 1.6;

    /* IMAGEM DE FUNDO DO SITE */
    background:
        linear-gradient(rgba(12,24,17,.78), rgba(12,24,17,.88)),
        url("imagemfundo.webp") center center / cover fixed;
}

a {
    text-decoration: none;
    color: inherit;
}

img {
    display: block;
    max-width: 100%;
}

header {
    background: rgba(18,35,25,.96);
    color: white;
    border-bottom: 1px solid rgba(215,181,109,.35);
    position: sticky;
    top: 0;
    z-index: 100;
    backdrop-filter: blur(12px);
}

.topo {
    max-width: 1240px;
    margin: auto;
    padding: 15px 24px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 20px;
}

.logo {
    display: flex;
    align-items: center;
    gap: 12px;
    font-size: 23px;
    font-weight: 800;
    letter-spacing: -.5px;
}

.logo-simbolo {
    width: 43px;
    height: 43px;
    border: 1px solid var(--dourado);
    color: var(--dourado);
    display: grid;
    place-items: center;
    border-radius: 12px;
    font-size: 22px;
}

.logo span {
    color: var(--dourado);
}

.topo-aviso {
    color: #d5ddd6;
    font-size: 11px;
    letter-spacing: 1.5px;
    text-align: right;
}

nav {
    background: rgba(255,255,255,.96);
    box-shadow: 0 3px 15px #00000012;
}

.menu {
    max-width: 1240px;
    margin: auto;
    padding: 12px 24px;
    display: flex;
    align-items: center;
    gap: 28px;
    overflow-x: auto;
    white-space: nowrap;
}

.menu a {
    font-size: 13px;
    font-weight: 700;
    color: #34483a;
}

.menu a:hover {
    color: #a17b36;
}

.container {
    max-width: 1240px;
    margin: auto;
    padding: 32px 24px 55px;
}

/* APRESENTAÇÃO */

.hero {
    min-height: 310px;
    padding: 55px;
    border-radius: 22px;
    color: white;
    display: flex;
    align-items: center;
    position: relative;
    overflow: hidden;
    background:
        linear-gradient(90deg, rgba(15,35,23,.96), rgba(15,35,23,.66)),
        url("imagemfundo.webp") center 45% / cover;
    border: 1px solid rgba(215,181,109,.35);
    box-shadow: var(--sombra);
}

.hero-conteudo {
    max-width: 690px;
    position: relative;
    z-index: 1;
}

.etiqueta {
    color: var(--dourado);
    text-transform: uppercase;
    font-size: 11px;
    letter-spacing: 3px;
    font-weight: bold;
    margin-bottom: 15px;
}

.hero h1 {
    font-family: Georgia, serif;
    font-size: clamp(32px, 5vw, 55px);
    line-height: 1.12;
    margin-bottom: 18px;
}

.hero p {
    color: #e0e7df;
    font-size: 16px;
    max-width: 590px;
    margin-bottom: 26px;
}

.botao {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 9px;
    padding: 13px 21px;
    border-radius: 7px;
    font-weight: 800;
    font-size: 13px;
    transition: .2s;
    cursor: pointer;
    border: none;
}

.botao-dourado {
    background: var(--dourado);
    color: #1b2b20;
}

.botao-dourado:hover {
    background: #efd18e;
    transform: translateY(-2px);
}

.botao-verde {
    background: var(--verde);
    color: white;
}

.botao-verde:hover {
    background: var(--verde-claro);
}

/* PAINÉIS E TÍTULOS */

.painel {
    background: rgba(255,255,255,.97);
    border-radius: 18px;
    padding: 30px;
    margin-top: 28px;
    box-shadow: var(--sombra);
}

.titulo-secao {
    display: flex;
    align-items: flex-end;
    justify-content: space-between;
    gap: 15px;
    margin-bottom: 22px;
}

.titulo-secao h2 {
    font-family: Georgia, serif;
    font-size: clamp(23px, 3vw, 31px);
    color: var(--verde);
    line-height: 1.2;
}

.titulo-secao p {
    color: var(--cinza);
    font-size: 13px;
    margin-top: 7px;
}

.linha-dourada {
    width: 55px;
    height: 3px;
    background: var(--dourado);
    margin-top: 12px;
}

/* DESTAQUE CAÇA */

.destaque-caca {
    background: linear-gradient(135deg, #17291e, #294532);
    color: white;
    border: 1px solid rgba(215,181,109,.45);
    border-radius: 20px;
    padding: 32px;
    margin-top: 28px;
    box-shadow: var(--sombra);
}

.cabecalho-caca {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 20px;
    margin-bottom: 25px;
}

.cabecalho-caca h2 {
    font-family: Georgia, serif;
    font-size: clamp(25px, 4vw, 36px);
    color: #fff;
}

.cabecalho-caca p {
    color: #d4dfd5;
    font-size: 14px;
    max-width: 650px;
    margin-top: 9px;
}

.selo-destaque {
    border: 1px solid var(--dourado);
    color: var(--dourado);
    padding: 7px 12px;
    font-size: 10px;
    font-weight: bold;
    letter-spacing: 1px;
    border-radius: 30px;
    white-space: nowrap;
}

.caca-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0,1fr));
    gap: 17px;
}

.caca-card {
    background: white;
    color: var(--texto);
    border-radius: 13px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    min-width: 0;
    transition: .25s;
}

.caca-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 12px 25px #0004;
}

.caca-card img {
    width: 100%;
    height: 190px;
    object-fit: cover;
    background: #e9ece7;
}

.caca-info {
    padding: 17px;
    display: flex;
    flex-direction: column;
    flex: 1;
}

.caca-info h3 {
    font-size: 17px;
    color: var(--verde);
    margin-bottom: 7px;
}

.caca-info p {
    font-size: 12px;
    color: var(--cinza);
    margin-bottom: 16px;
}

.caca-info .botao {
    margin-top: auto;
    width: 100%;
}

.lista-principal {
    margin-top: 22px;
    background: rgba(255,255,255,.09);
    border: 1px solid rgba(215,181,109,.55);
    border-radius: 12px;
    padding: 21px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 20px;
}

.lista-principal strong {
    display: block;
    font-size: 18px;
    color: #fff;
}

.lista-principal p {
    color: #d4dfd5;
    font-size: 12px;
    margin-top: 5px;
}

.aviso-legal {
    color: #d5dfd5;
    font-size: 11px;
    margin-top: 17px;
    line-height: 1.6;
}

/* BUSCA */

.busca {
    display: flex;
    gap: 10px;
    margin: 24px 0 0;
}

.busca input {
    flex: 1;
    min-width: 0;
    padding: 14px 16px;
    border: 1px solid #d8ded8;
    border-radius: 8px;
    font-size: 14px;
    outline-color: var(--verde-claro);
}

.busca button {
    padding: 0 22px;
}

.resultado {
    color: var(--cinza);
    font-size: 12px;
    margin-top: 10px;
}

/* CATEGORIAS */

.categorias {
    display: grid;
    grid-template-columns: repeat(4, minmax(0,1fr));
    gap: 15px;
}

.categoria {
    display: flex;
    align-items: center;
    gap: 13px;
    padding: 17px 13px;
    border: 1px solid var(--borda);
    border-radius: 11px;
    background: #fff;
    transition: .2s;
    min-height: 86px;
}

.categoria:hover {
    border-color: var(--dourado);
    transform: translateY(-3px);
    box-shadow: 0 7px 18px #0000000d;
}

.categoria-icone {
    width: 43px;
    height: 43px;
    border-radius: 10px;
    background: #edf2eb;
    display: grid;
    place-items: center;
    font-size: 22px;
    flex-shrink: 0;
}

.categoria strong {
    display: block;
    color: var(--verde);
    font-size: 13px;
    line-height: 1.3;
}

.categoria small {
    display: block;
    color: var(--cinza);
    font-size: 10px;
    margin-top: 4px;
}

/* DESTAQUES */

.produtos {
    display: grid;
    grid-template-columns: repeat(3, minmax(0,1fr));
    gap: 17px;
}

.produto {
    border: 1px solid var(--borda);
    border-radius: 12px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    background: white;
}

.produto-imagem {
    height: 150px;
    display: grid;
    place-items: center;
    background: #edf1eb;
    font-size: 54px;
}

.produto-info {
    padding: 17px;
    flex: 1;
}

.produto-info span {
    color: #94702f;
    text-transform: uppercase;
    font-weight: bold;
    font-size: 10px;
    letter-spacing: 1px;
}

.produto-info h3 {
    color: var(--verde);
    font-size: 16px;
    margin: 7px 0;
}

.produto-info p {
    color: var(--cinza);
    font-size: 12px;
    margin-bottom: 12px;
}

.produto > a {
    border-radius: 0;
    width: 100%;
}

/* INFORMAÇÕES */

.informacoes {
    color: #344239;
    font-size: 13px;
}

.informacoes h3 {
    color: var(--verde);
    font-size: 16px;
    margin: 20px 0 7px;
}

.informacoes p {
    margin-bottom: 10px;
}

.informacoes ul {
    padding-left: 20px;
}

.informacoes li {
    margin: 5px 0;
}

.transparencia {
    margin-top: 20px;
    padding: 16px;
    background: #f3f5ef;
    border-left: 4px solid var(--dourado);
    border-radius: 6px;
}

/* RODAPÉ */

footer {
    background: #13231a;
    color: white;
    padding: 35px 24px 20px;
    border-top: 1px solid rgba(215,181,109,.4);
}

.rodape {
    max-width: 1240px;
    margin: auto;
    display: grid;
    grid-template-columns: 2fr 1fr 1fr;
    gap: 30px;
}

.rodape h3 {
    color: var(--dourado);
    font-family: Georgia, serif;
    margin-bottom: 12px;
}

.rodape p, .rodape a {
    color: #c8d1ca;
    font-size: 12px;
}

.rodape a {
    display: block;
    margin: 7px 0;
}

.rodape a:hover {
    color: var(--dourado);
}

.rodape-final {
    max-width: 1240px;
    margin: 25px auto 0;
    padding-top: 18px;
    border-top: 1px solid #ffffff25;
    color: #aab6ac;
    font-size: 11px;
    text-align: center;
}

.oculto {
    display: none !important;
}

/* RESPONSIVIDADE */

@media(max-width: 900px) {
    .categorias {
        grid-template-columns: repeat(2, minmax(0,1fr));
    }

    .caca-grid {
        grid-template-columns: repeat(2, minmax(0,1fr));
    }

    .produtos {
        grid-template-columns: repeat(2, minmax(0,1fr));
    }
}

@media(max-width: 600px) {
    .topo {
        padding: 12px 16px;
    }

    .logo {
        font-size: 19px;
    }

    .topo-aviso {
        font-size: 9px;
    }

    .menu {
        padding: 11px 16px;
        gap: 20px;
    }

    .container {
        padding: 18px 13px 35px;
    }

    .hero {
        min-height: 300px;
        padding: 30px 22px;
        background-position: center;
    }

    .hero h1 {
        font-size: 34px;
    }

    .hero p {
        font-size: 14px;
    }

    .painel {
        padding: 20px 15px;
        margin-top: 18px;
    }

    .destaque-caca {
        padding: 20px 14px;
        margin-top: 18px;
    }

    .cabecalho-caca {
        display: block;
    }

    .selo-destaque {
        display: inline-block;
        margin-top: 12px;
    }

    .caca-grid {
        grid-template-columns: repeat(2, minmax(0,1fr));
        gap: 10px;
    }

    .caca-card img {
        height: 125px;
    }

    .caca-info {
        padding: 11px;
    }

    .caca-info h3 {
        font-size: 13px;
    }

    .caca-info p {
        font-size: 10px;
    }

    .caca-info .botao {
        padding: 10px 5px;
        font-size: 11px;
    }

    .lista-principal {
        display: block;
        padding: 16px;
    }

    .lista-principal .botao {
        width: 100%;
        margin-top: 13px;
    }

    .categorias {
        grid-template-columns: 1fr 1fr;
        gap: 9px;
    }

    .categoria {
        padding: 11px 8px;
        gap: 8px;
        min-height: 75px;
    }

    .categoria-icone {
        width: 34px;
        height: 34px;
        font-size: 18px;
    }

    .categoria strong {
        font-size: 11px;
    }

    .categoria small {
        font-size: 9px;
    }

    .produtos {
        grid-template-columns: 1fr 1fr;
        gap: 10px;
    }

    .produto-imagem {
        height: 105px;
    }

    .produto-info {
        padding: 12px;
    }

    .produto-info h3 {
        font-size: 13px;
    }

    .produto-info p {
        font-size: 10px;
    }

    .produto .botao {
        font-size: 11px;
        padding: 11px 5px;
    }

    .busca {
        gap: 6px;
    }

    .busca input {
        padding: 12px 9px;
        font-size: 12px;
    }

    .busca button {
        padding: 0 12px;
        font-size: 11px;
    }

    .rodape {
        grid-template-columns: 1fr;
        gap: 22px;
    }
}

@media(prefers-reduced-motion: reduce) {
    html { scroll-behavior: auto; }
    * { transition: none !important; }
}
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "name": "Vitrine de Ofertas",
  "url": "https://marquesdvoferta.github.io/",
  "description": "Vitrine independente de produtos e listas de ofertas para campo, casa, lazer e tecnologia.",
  "inLanguage": "pt-BR"
}
</script>
</head>

<body>

<header>
    <div class="topo">
        <a href="#inicio" class="logo">
            <div class="logo-simbolo">✦</div>
            <div>Vitrine <span>de Ofertas</span></div>
        </a>
        <div class="topo-aviso">CURADORIA INDEPENDENTE DE PRODUTOS</div>
    </div>
</header>

<nav aria-label="Menu principal">
    <div class="menu">
        <a href="#inicio">Início</a>
        <a href="#caca">Lista de caça</a>
        <a href="#categorias">Categorias</a>
        <a href="#destaques">Achados</a>
        <a href="#sobre">Sobre a vitrine</a>
    </div>
</nav>

<main class="container">

    <!-- APRESENTAÇÃO -->
    <section class="hero" id="inicio">
        <div class="hero-conteudo">
            <div class="etiqueta">Vitrine de Ofertas • Seleção especial</div>
            <h1>Encontre o que combina com seu estilo de vida.</h1>
            <p>
                Uma vitrine independente com listas e sugestões de produtos
                para quem gosta de campo, natureza, casa, lazer e tecnologia.
                Explore as categorias e encontre seus próximos achados.
            </p>
            <a href="#caca" class="botao botao-dourado">
                Explorar lista em destaque →
            </a>
        </div>
    </section>

    <!-- CAÇA EM PRIMEIRO LUGAR -->
    <section class="destaque-caca" id="caca">

        <div class="cabecalho-caca">
            <div>
                <div class="etiqueta">Seleção em destaque</div>
                <h2>Caça, arco e flecha</h2>
                <p>
                    Acesse a lista de produtos selecionados no Mercado Livre
                    e explore equipamentos, acessórios e artigos relacionados.
                    Esta é a área principal da nossa vitrine.
                </p>
            </div>
            <span class="selo-destaque">LISTA EM DESTAQUE</span>
        </div>

        <div class="caca-grid">

            <article class="caca-card">
                <img src="arco.png" alt="Arco e flecha" loading="lazy">
                <div class="caca-info">
                    <h3>Arco e flecha</h3>
                    <p>Equipamentos e acessórios para prática esportiva e recreativa.</p>
                    <a class="botao botao-verde"
                       href="https://meli.la/2YBisqP"
                       target="_blank"
                       rel="nofollow sponsored noopener noreferrer">
                        Ver produtos
                    </a>
                </div>
            </article>

            <article class="caca-card">
                <img src="besta.jfif" alt="Besta e acessórios" loading="lazy">
                <div class="caca-info">
                    <h3>Besta</h3>
                    <p>Confira produtos e acessórios disponíveis na lista.</p>
                    <a class="botao botao-verde"
                       href="https://meli.la/2YBisqP"
                       target="_blank"
                       rel="nofollow sponsored noopener noreferrer">
                        Ver produtos
                    </a>
                </div>
            </article>

            <article class="caca-card">
                <img src="chumbinho.jfif" alt="Chumbinhos e acessórios" loading="lazy">
                <div class="caca-info">
                    <h3>Chumbinhos e acessórios</h3>
                    <p>Consulte os anúncios e confira as especificações dos produtos.</p>
                    <a class="botao botao-verde"
                       href="https://meli.la/2YBisqP"
                       target="_blank"
                       rel="nofollow sponsored noopener noreferrer">
                        Ver produtos
                    </a>
                </div>
            </article>

        </div>

        <div class="lista-principal">
            <div>
                <strong>🛒 Acesse a lista de caça no Mercado Livre</strong>
                <p>Veja os produtos reunidos na lista principal da Vitrine de Ofertas.</p>
            </div>
            <a class="botao botao-dourado"
               href="https://meli.la/2YBisqP"
               target="_blank"
               rel="nofollow sponsored noopener noreferrer">
                ACESSAR LISTA →
            </a>
        </div>

        <p class="aviso-legal">
            Conteúdo destinado à divulgação de produtos. Verifique a legislação
            aplicável, os requisitos de idade, as regras de aquisição e as
            condições de uso dos equipamentos. Respeite as normas de segurança
            e as orientações dos fabricantes.
        </p>
    </section>

    <!-- BUSCA -->
    <section class="painel">
        <div class="titulo-secao">
            <div>
                <h2>O que você está procurando?</h2>
                <p>Pesquise uma categoria para encontrar o assunto desejado.</p>
                <div class="linha-dourada"></div>
            </div>
        </div>

        <form class="busca" id="formBusca">
            <input type="search" id="campoBusca"
                   placeholder="Ex.: pesca, notebook, ferramentas, casa..."
                   aria-label="Pesquisar categorias">
            <button class="botao botao-verde" type="submit">Buscar</button>
        </form>
        <p class="resultado" id="resultadoBusca" aria-live="polite"></p>
    </section>

    <!-- CATEGORIAS -->
    <section class="painel" id="categorias">
        <div class="titulo-secao">
            <div>
                <h2>Explore outras categorias</h2>
                <p>Mais opções para casa, campo, tecnologia, lazer e rotina.</p>
                <div class="linha-dourada"></div>
            </div>
        </div>

        <div class="categorias" id="listaCategorias">

            <a class="categoria" data-palavras="notebook computador informática tecnologia laptop"
               href="https://meli.la/1njpbSM" target="_blank" rel="nofollow sponsored noopener noreferrer">
                <span class="categoria-icone">💻</span>
                <span><strong>Notebooks</strong><small>Informática e tecnologia</small></span>
            </a>

            <a class="categoria" data-palavras="eletrodomésticos cozinha casa"
               href="https://meli.la/2jKEBe1" target="_blank" rel="nofollow sponsored noopener noreferrer">
                <span class="categoria-icone">🍳</span>
                <span><strong>Eletrodomésticos</strong><small>Produtos para casa</small></span>
            </a>

            <a class="categoria" data-palavras="natal decoração enfeites"
               href="https://meli.la/1vBQJKs" target="_blank" rel="nofollow sponsored noopener noreferrer">
                <span class="categoria-icone">🎄</span>
                <span><strong>Enfeites de Natal</strong><small>Decoração</small></span>
            </a>

            <a class="categoria" data-palavras="pesca pescaria vara anzol molinete"
               href="https://meli.la/2eDHdYS" target="_blank" rel="nofollow sponsored noopener noreferrer">
                <span class="categoria-icone">🎣</span>
                <span><strong>Pescaria</strong><small>Artigos e acessórios</small></span>
            </a>

            <a class="categoria" data-palavras="pintura tinta reforma acabamento casa"
               href="https://meli.la/1uRP5Jz" target="_blank" rel="nofollow sponsored noopener noreferrer">
                <span class="categoria-icone">🖌️</span>
                <span><strong>Pintura e acabamentos</strong><small>Reforma e construção</small></span>
            </a>

            <a class="categoria" data-palavras="brinquedos crianças infantil jogos"
               href="https://meli.la/333DnWa" target="_blank" rel="nofollow sponsored noopener noreferrer">
                <span class="categoria-icone">🧸</span>
                <span><strong>Brinquedos</strong><small>Jogos e presentes</small></span>
            </a>

            <a class="categoria" data-palavras="revenda produtos negócio comércio empreendedor"
               href="https://meli.la/26pngPX" target="_blank" rel="nofollow sponsored noopener noreferrer">
                <span class="categoria-icone">📦</span>
                <span><strong>Produtos para revenda</strong><small>Pequenos negócios</small></span>
            </a>

            <a class="categoria" data-palavras="material escolar mochila caderno caneta escola"
               href="https://meli.la/2bcp9T1" target="_blank" rel="nofollow sponsored noopener noreferrer">
                <span class="categoria-icone">🎒</span>
                <span><strong>Material escolar</strong><small>Estudo e organização</small></span>
            </a>

            <a class="categoria" data-palavras="tv televisão celular smartphone eletrônicos"
               href="https://meli.la/1cz7b71" target="_blank" rel="nofollow sponsored noopener noreferrer">
                <span class="categoria-icone">📱</span>
                <span><strong>TV e celulares</strong><small>Eletrônicos</small></span>
            </a>

            <a class="categoria" data-palavras="caminhada musculação academia esporte fitness"
               href="https://meli.la/1oX9Gak" target="_blank" rel="nofollow sponsored noopener noreferrer">
                <span class="categoria-icone">🏃</span>
                <span><strong>Caminhada e musculação</strong><small>Atividade física</small></span>
            </a>

            <a class="categoria" data-palavras="rural roça campo fazenda ferramentas agricultura quintal"
               href="https://meli.la/1V523ii" target="_blank" rel="nofollow sponsored noopener noreferrer">
                <span class="categoria-icone">🌱</span>
                <span><strong>Achados rurais</strong><small>Campo e quintal</small></span>
            </a>

        </div>

        <p class="resultado oculto" id="semResultado">
            Nenhuma categoria encontrada. Tente pesquisar por outro termo.
        </p>
    </section>

    <!-- OUTROS ACHADOS -->
    <section class="painel" id="destaques">
        <div class="titulo-secao">
            <div>
                <h2>Mais achados para descobrir</h2>
                <p>Algumas sugestões para continuar explorando a vitrine.</p>
                <div class="linha-dourada"></div>
            </div>
        </div>

        <div class="produtos">

            <article class="produto">
                <div class="produto-imagem">💻</div>
                <div class="produto-info">
                    <span>Tecnologia</span>
                    <h3>Notebooks e computadores</h3>
                    <p>Opções para estudar, trabalhar e realizar tarefas do dia a dia.</p>
                </div>
                <a class="botao botao-verde" href="https://meli.la/1njpbSM" target="_blank" rel="nofollow sponsored noopener noreferrer">Ver ofertas</a>
            </article>

            <article class="produto">
                <div class="produto-imagem">🎣</div>
                <div class="produto-info">
                    <span>Lazer</span>
                    <h3>Equipamentos de pescaria</h3>
                    <p>Artigos e acessórios para quem gosta de pescar.</p>
                </div>
                <a class="botao botao-verde" href="https://meli.la/2eDHdYS" target="_blank" rel="nofollow sponsored noopener noreferrer">Ver ofertas</a>
            </article>

            <article class="produto">
                <div class="produto-imagem">🌾</div>
                <div class="produto-info">
                    <span>Campo</span>
                    <h3>Produtos rurais</h3>
                    <p>Ferramentas e itens úteis para campo, roça e quintal.</p>
                </div>
                <a class="botao botao-verde" href="https://meli.la/1V523ii" target="_blank" rel="nofollow sponsored noopener noreferrer">Ver ofertas</a>
            </article>

            <article class="produto">
                <div class="produto-imagem">🍳</div>
                <div class="produto-info">
                    <span>Casa</span>
                    <h3>Eletrodomésticos</h3>
                    <p>Produtos para cozinha e praticidade na rotina doméstica.</p>
                </div>
                <a class="botao botao-verde" href="https://meli.la/2jKEBe1" target="_blank" rel="nofollow sponsored noopener noreferrer">Ver ofertas</a>
            </article>

            <article class="produto">
                <div class="produto-imagem">🧸</div>
                <div class="produto-info">
                    <span>Infantil</span>
                    <h3>Brinquedos e jogos</h3>
                    <p>Ideias de presentes e opções para diferentes idades.</p>
                </div>
                <a class="botao botao-verde" href="https://meli.la/333DnWa" target="_blank" rel="nofollow sponsored noopener noreferrer">Ver ofertas</a>
            </article>

            <article class="produto">
                <div class="produto-imagem">📦</div>
                <div class="produto-info">
                    <span>Empreendedorismo</span>
                    <h3>Produtos para revenda</h3>
                    <p>Explore opções para pesquisar e avaliar oportunidades de comércio.</p>
                </div>
                <a class="botao botao-verde" href="https://meli.la/26pngPX" target="_blank" rel="nofollow sponsored noopener noreferrer">Ver ofertas</a>
            </article>

        </div>
    </section>

    <!-- SOBRE -->
    <section class="painel" id="sobre">
        <div class="titulo-secao">
            <div>
                <h2>Sobre a Vitrine de Ofertas</h2>
                <p>Uma página independente para organizar indicações de produtos.</p>
                <div class="linha-dourada"></div>
            </div>
        </div>

        <div class="informacoes">
            <p>
                A Vitrine de Ofertas reúne listas e sugestões de produtos
                em diferentes categorias. A proposta é facilitar a pesquisa
                de quem procura artigos para campo, casa, lazer, tecnologia,
                estudos e atividades do dia a dia.
            </p>

            <h3>Como funcionam os links?</h3>
            <p>
                Alguns links desta página são links de afiliados. Isso significa
                que podemos receber uma comissão quando uma compra qualificada
                é realizada por meio deles, sem custo adicional para o comprador.
            </p>

            <h3>Somos o Mercado Livre?</h3>
            <p>
                Não. A Vitrine de Ofertas é independente e não representa
                oficialmente o Mercado Livre. Não realizamos vendas, pagamentos,
                entregas ou atendimento dos produtos anunciados.
            </p>

            <div class="transparencia">
                <strong>Transparência e segurança:</strong>
                os preços, estoques, condições de pagamento e prazos podem mudar.
                Confira sempre as informações diretamente no anúncio e compre
                pelos canais oficiais da plataforma.
            </div>
        </div>
    </section>

</main>

<footer>
    <div class="rodape">
        <div>
            <h3>Vitrine de Ofertas</h3>
            <p>
                Achados e sugestões para quem gosta de campo, natureza,
                casa, lazer e tecnologia.
            </p>
            <p style="margin-top:10px">
                Site independente de divulgação de produtos e afiliados.
            </p>
        </div>

        <div>
            <h3>Navegação</h3>
            <a href="#inicio">Página inicial</a>
            <a href="#caca">Lista em destaque</a>
            <a href="#categorias">Categorias</a>
            <a href="#destaques">Mais achados</a>
        </div>

        <div>
            <h3>Informações</h3>
            <a href="#sobre">Sobre a vitrine</a>
            <a href="#sobre">Aviso de afiliados</a>
            <a href="#sobre">Transparência</a>
        </div>
    </div>

    <div class="rodape-final">
        © 2026 Vitrine de Ofertas. Site independente.
        Mercado Livre é uma marca de seu respectivo proprietário.
    </div>
</footer>

<script>
const campoBusca = document.getElementById("campoBusca");
const formulario = document.getElementById("formBusca");
const categorias = document.querySelectorAll(".categoria");
const resultado = document.getElementById("resultadoBusca");
const semResultado = document.getElementById("semResultado");

formulario.addEventListener("submit", function(event) {
    event.preventDefault();
    filtrarCategorias();
});

campoBusca.addEventListener("input", filtrarCategorias);

function filtrarCategorias() {
    const termo = campoBusca.value
        .trim()
        .toLocaleLowerCase("pt-BR");

    let encontrados = 0;

    categorias.forEach(function(categoria) {
        const palavras = (
            categoria.innerText + " " +
            categoria.dataset.palavras
        ).toLocaleLowerCase("pt-BR");

        const corresponde = palavras.includes(termo);

        categoria.classList.toggle("oculto", !corresponde);

        if (corresponde) encontrados++;
    });

    if (!termo) {
        resultado.textContent = "";
        semResultado.classList.add("oculto");
        return;
    }

    resultado.textContent = encontrados === 1
        ? "Encontramos 1 categoria."
        : "Encontramos " + encontrados + " categorias.";

    semResultado.classList.toggle("oculto", encontrados !== 0);
}
</script>

</body>
</html>
