<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo de Vídeos</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Catálogo de Vídeos</h1>
    </header>
    <main>
        <section id="videos">
            <article class="video">
                <h2>Introdução ao VSCode</h2>
                <p>Um vídeo sobre como começar a usar o VSCode.</p>
                <video controls>
                    <source src="caminho/para/o/video1.mp4" type="video/mp4">
                    Seu navegador não suporta a tag de vídeo.
                </video>
            </article>
            <article class="video">
                <h2>Configuração do Ambiente</h2>
                <p>Dicas para configurar seu ambiente de desenvolvimento no VSCode.</p>
                <video controls>
                    <source src="caminho/para/o/video2.mp4" type="video/mp4">
                    Seu navegador não suporta a tag de vídeo.
                </video>
            </article>
            <article class="video">
                <h2>Extensões Úteis</h2>
                <p>Extensões recomendadas para melhorar sua produtividade no VSCode.</p>
                <video controls>
                    <source src="caminho/para/o/video3.mp4" type="video/mp4">
                    Seu navegador não suporta a tag de vídeo.
                </video>
            </article>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Seu Nome. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

main {
    padding: 20px;
}

.video {
    margin-bottom: 20px;
    background: #fff;
    padding: 10px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

video {
    max-width: 100%;
    height: auto;
    display: block;
    margin-top: 10px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
Passo 4: Testa
