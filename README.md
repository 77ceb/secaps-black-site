<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Secaps Black Oficial</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Arial, sans-serif;
    background: linear-gradient(180deg, #0a0a0a, #111);
    color: #eaeaea;
    scroll-behavior: smooth;
}

/* HEADER */
header {
    background: #0a0a0a;
    border-bottom: 1px solid #1f1f1f;
    text-align: center;
    padding: 20px;
    font-size: 18px;
    letter-spacing: 2px;
    color: #3ddc97;
    font-weight: 600;
}

/* CONTAINER */
.container {
    max-width: 1100px;
    margin: auto;
    padding: 30px 20px;
}

/* HERO */
.hero {
    text-align: center;
    margin-top: 30px;
}

.hero img {
    max-width: 380px;
    width: 100%;
    margin-bottom: 20px;
}

.hero h1 {
    font-size: 38px;
    font-weight: 700;
    color: #ffffff;
    margin-bottom: 10px;
    text-shadow: 0 0 10px rgba(61,220,151,0.3);
}

.hero h1 span {
    color: #3ddc97;
}

.hero p {
    color: #aaa;
    font-size: 17px;
}

/* BOTÃO */
.btn {
    display: inline-block;
    margin-top: 25px;
    background: #3ddc97;
    color: #000;
    padding: 14px 28px;
    border-radius: 6px;
    text-decoration: none;
    font-weight: 600;
    transition: 0.3s;
}

.btn:hover {
    background: #2bbf80;
    transform: translateY(-2px);
}

/* SEÇÕES */
.section {
    margin-top: 70px;
}

.section h2 {
    font-size: 26px;
    margin-bottom: 15px;
    color: #fff;
    border-left: 4px solid #3ddc97;
    padding-left: 10px;
}

/* BENEFÍCIOS */
.benefits {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}

.benefit {
    background: #141414;
    padding: 18px;
    border-radius: 8px;
    border: 1px solid #1f1f1f;
    text-align: center;
    color: #ccc;
}

/* IMAGENS */
.section img {
    width: 100%;
    border-radius: 10px;
    margin-top: 10px;
}

/* PRODUTOS */
.products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
}

.product {
    background: #141414;
    padding: 20px;
    border-radius: 10px;
    border: 1px solid #1f1f1f;
    text-align: center;
    transition: 0.3s;
}

.product:hover {
    border-color: #3ddc97;
    transform: translateY(-5px);
}

.product img {
    max-width: 180px;
    margin-bottom: 10px;
}

/* COMPOSIÇÃO */
.composicao {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

/* FOOTER */
footer {
    margin-top: 60px;
    padding: 25px;
    text-align: center;
    color: #777;
    font-size: 14px;
    border-top: 1px solid #1f1f1f;
}

/* RESPONSIVO */
@media (max-width: 600px) {
    .hero h1 {
        font-size: 28px;
    }
}
</style>
</head>

<body>

<header>
SECAPS BLACK
</header>

<div class="container">

<!-- HERO -->
<div class="hero">
    <img src="imagens/produto1.jpeg" alt="Secaps Black Cápsulas">
    
    <h1>Transforme seu corpo com <span>Secaps Black</span></h1>
    
    <p>Mais energia, menos inchaço e controle total da sua fome</p>

    <a href="https://pay.hest.com.br/6eb26dea-7c28-4a85-ba84-ab5e7688ba3b" class="btn" target="_blank">
        Comprar agora
    </a>
</div>

<!-- SOBRE -->
<div class="section">
    <h2>Sobre o produto</h2>
    <p>
        Secaps Black é um suplemento que auxilia no emagrecimento, promovendo
        saciedade, energia e aceleração do metabolismo de forma equilibrada.
    </p>
</div>

<!-- BENEFÍCIOS -->
<div class="section">
    <h2>Benefícios</h2>

    <div class="benefits">
        <div class="benefit">Acelera o metabolismo</div>
        <div class="benefit">Reduz retenção de líquido</div>
        <div class="benefit">Mais saciedade</div>
        <div class="benefit">Mais energia</div>
        <div class="benefit">Auxilia na queima de gordura</div>
    </div>
</div>

<!-- COMPOSIÇÃO -->
<div class="section">
    <h2>Composição</h2>

    <div class="composicao">
        <img src="imagens/composicao1.jpeg" alt="Composição do produto 1" style="max-width:500px;">
        <img src="imagens/composicao2.jpeg" alt="Composição do produto 2" style="max-width:500px;">
    </div>
</div>

<!-- PRODUTOS -->
<div class="section">
    <h2>Produtos</h2>

    <div class="products">

        <div class="product">
            <img src="imagens/produto1.jpeg" alt="Secaps Black Cápsulas">
            <h3>Secaps Black Cápsulas</h3>
            <a href="https://pay.hest.com.br/6eb26dea-7c28-4a85-ba84-ab5e7688ba3b" class="btn" target="_blank">
                Comprar
            </a>
        </div>

        <div class="product">
            <img src="imagens/produto3.jpeg" alt="Secaps Black Chá">
            <h3>Secaps Black Chá</h3>
            <a href="#" class="btn">Comprar</a>
        </div>

    </div>
</div>

<!-- FINAL -->
<div class="section" style="text-align:center;">
    <h2>Comece agora</h2>
    <a href="https://pay.hest.com.br/6eb26dea-7c28-4a85-ba84-ab5e7688ba3b" class="btn" target="_blank">
        Garantir meu produto
    </a>
</div>

</div>

<footer>
© 2026 Secaps Black - Todos os direitos reservados
</footer>

</body>
</html>
