<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Minha Página com Imagem e Estilo</title>
    
    <style>
        /* Estilo do corpo da página (Desafio 2) */
        body {
            background-color: #1a1a2e; /* Fundo escuro */
            color: #e2e8f0;            /* Texto claro e confortável */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            max-width: 600px;          /* Limita a largura para melhor leitura */
            margin: 40px auto;         /* Centraliza a página */
            padding: 20px;
            line-height: 1.6;
        }

        /* Estilo dos títulos */
        h1 {
            color: #00adb5;            /* Azul ciano */
            text-align: center;
            border-bottom: 2px solid #00adb5;
            padding-bottom: 10px;
        }

        h2 {
            color: #ff2e63;            /* Rosa/coral */
            margin-top: 30px;
        }

        /* Estilo dos parágrafos */
        p {
            text-align: justify;
        }

        /* --- ESTILO DA IMAGEM (Desafio 3) --- */
        img {
            display: block;            /* Faz a imagem se comportar como um bloco */
            max-width: 100%;           /* Garante que ela nunca morda ou passe do limite da tela */
            height: auto;              /* Mantém a proporção correta de altura e largura */
            border-radius: 8px;        /* Deixa as pontas da imagem arredondadas e modernas */
            margin: 20px auto;         /* Cria espaço nas linhas e centraliza a imagem */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3); /* Adiciona uma sombra suave */
        }
    </style>
</head>
<body>

    <h1>Minha Nova Identidade</h1>
    
    <p>Esta página não segue mais o padrão sem graça de fundo branco e texto preto! Agora ela usa CSS dentro da tag style para ganhar cores personalizadas e uma tipografia muito mais moderna.</p>

    <h2>Explorando Estilos</h2>
    <p>O segredo aqui é testar combinações. Um fundo escuro precisa de letras bem claras para manter a leitura confortável. Se o fundo for claro, use letras bem escuras.</p>

    <h2>Ilustrando o Conteúdo</h2>
    <p>Abaixo, adicionei uma imagem que se conecta com o tema tecnológico e moderno do nosso layout. Veja como ela se ajusta perfeitamente ao tamanho do texto:</p>

    <img 
        src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?q=80&w=600" 
        alt="Notebook aberto em uma mesa escura exibindo linhas de código em uma tela iluminada, representando o desenvolvimento da página"
    >

    <p>Repare que a imagem possui um atributo chamado <code>alt</code>. Ele serve para descrever o que está na imagem caso ela não carregue ou para que leitores de tela leiam para pessoas com deficiência visual, garantindo a acessibilidade.</p>

</body>
</html>
