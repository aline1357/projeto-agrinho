<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Processo de Alimentos</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Processo de Alimentos</h1>
        <nav>
            <ul>
                <li><a href="#plantio">Plantio</a></li>
                <li><a href="#colheita">Colheita</a></li>
                <li><a href="#embalagem">Embalagem</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="plantio">
            <h2>Plantio</h2>
            <img src="img/plantio.jpg" alt="Plantio" class="imagem-processo">
            <p>O plantio é o primeiro passo no processo de cultivo de alimentos. Aqui, as sementes são colocadas no solo para começar a crescer.</p>
        </section>

        <section id="colheita">
            <h2>Colheita</h2>
            <img src="img/colheita.jpg" alt="Colheita" class="imagem-processo">
            <p>A colheita é quando os alimentos são retirados do campo, prontos para serem processados e distribuídos.</p>
        </section>

        <section id="embalagem">
            <h2>Embalagem</h2>
            <img src="img/embalagem.jpg" alt="Embalagem" class="imagem-processo">
            <p>A embalagem é essencial para manter os alimentos frescos e protegidos durante o transporte até o mercado.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Projeto de Alimentos. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

### style.css
```css
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header {
    background: #4CAF50;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 40px;
}

.imagem-processo {
    max-width: 100%;
    height: auto;
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #f1f1f1;
    position: relative;
    bottom: 0;
    width: 100%;
}

