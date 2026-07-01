<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Blog de Tecnologia</title>
    
    <style>
        /* --- ESTILIZAÇÃO (CSS) --- */
        
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
            color: #333;
        }

        header {
            text-align: center;
            margin-bottom: 30px;
        }

        .blog-container {
            max-width: 1000px;
            margin: 0 auto;
        }

        /* DESAFIOS DE CSS (FLEXBOX) */

        /* 1. Altera a propriedade flex-direction para exibir em linha (row) */
        .post-card {
            display: flex;
            flex-direction: row; /* Elementos (imagem e texto) um ao lado do outro */
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            margin-bottom: 20px;
            overflow: hidden;
            
            /* 2. Ajuste para que cada card ocupe 100% da largura da página/container */
            flex: 1 1 100%; 
        }

        /* Ajustes da Imagem dentro do card */
        .post-image {
            width: 300px;
            height: auto;
            object-fit: cover;
        }

        /* Área de texto do card */
        .post-content {
            padding: 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            flex: 1;
        }

        h2 {
            margin-top: 0;
            color: #111;
        }

        h2 small {
            font-size: 0.6em;
            color: #666;
            font-weight: normal;
        }

        /* Classe obrigatória do desafio */
        .artigo-fonte {
            font-size: 0.85em;
            color: #888;
            font-style: italic;
        }

        /* 3. Utilizando align-self para quebrar o alinhamento padrão */
        .read-more-btn {
            background-color: #007acc;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 4px;
            cursor: pointer;
            margin-top: 10px;
            
            /* Faz o botão se alinhar sozinho ao final (direita) do bloco */
            align-self: flex-end; 
        }

        .read-more-btn:hover {
            background-color: #005999;
        }
    </style>
</head>
<body>

    <header>
        <h1>TechBlog</h1>
        <p>Acompanhe as últimas novidades do mundo tech</p>
    </header>

    <main class="blog-container">
        <article class="post-card">
            
            <img src="https://picsum.photos/300/200" alt="Imagem ilustrativa de tecnologia" class="post-image">
            
            <div class="post-content">
                <h2>Inteligência Artificial em 2026<br>
                <small>Como os novos modelos assistentes mudaram nossa rotina</small></h2>
                
                <p>Os novos modelos de <strong>redes neurais autoregressivas</strong> alcançaram um nível de autonomia surpreendente, transformando a programação de software e a criação de conteúdo em tarefas muito mais colaborativas.</p>
                
                <p class="artigo-fonte">Fonte: TechChronicles TechNews</p>
                
                <button class="read-more-btn">Ler mais</button>
            </div>

        </article>
    </main>

</body>
</html>
