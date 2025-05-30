# Thiago de Souza da Silv
CODIGO HTML 
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conexão Campo e Cidade</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Conexão Campo e Cidade</h1>
            <p>O encontro entre a tranquilidade rural e a agitação urbana.</p>
        </div>
    </header>

    <section class="content">
        <div class="container">
            <div class="card">
                <h2>Vida no Campo</h2>
                <p>A vida no campo é marcada pela simplicidade e tranquilidade. Aqui, as pessoas vivem em contato direto com a natureza, cultivando alimentos e vivendo de maneira mais pausada.</p>
            </div>
            <div class="card">
                <h2>Vida na Cidade</h2>
                <p>A cidade é marcada pela correria e pelos avanços tecnológicos. Concentra grandes indústrias, comércio e serviços que moldam a vida urbana.</p>
            </div>
            <div class="card">
                <h2>A Conexão</h2>
                <p>Com a tecnologia, a conexão entre o campo e a cidade nunca foi tão forte. O campo fornece alimentos e recursos para as cidades, enquanto a cidade oferece tecnologia e inovação para melhorar a vida no campo.</p>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>Conexão Campo e Cidade | Todos os direitos reservados</p>
        </div>
    </footer>
</body>
</html>

CODIGO CSS
/* Resetando estilos padrão */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

/* Container geral */
.container {
    width: 80%;
    margin: 0 auto;
}

/* Cabeçalho */
header {
    background: #4CAF50;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2em;
}

/* Seções de conteúdo */
.content {
    padding: 40px 0;
}

.card {
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    padding: 20px;
    margin-bottom: 20px;
    transition: transform 0.3s ease-in-out;
}

.card:hover {
    transform: scale(1.05);
}

.card h2 {
    color: #4CAF50;
    font-size: 1.8em;
    margin-bottom: 10px;
}

.card p {
    font-size: 1.1em;
    line-height: 1.6;
}

/* Rodapé */
footer {
    background: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}

footer p {
    font-size: 1em;
}

/* Responsividade */
@media (max-width: 768px) {
    .container {
        width: 95%;
    }

    .card {
        padding: 15px;
    }

    header h1 {
        font-size: 2em;
    }
}
