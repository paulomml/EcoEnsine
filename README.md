<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>EcoEnsina</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Times New Roman", sans-serif;
        }
        body {
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            overflow-x: hidden; /* Impede rolagem horizontal */
        }
        .container {
            width: 100%;
            max-width: 1440px; /* Limita a largura do site */
            background-color: white;
        }
        .header {
            background-color: white;
            padding: 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 100%;
            max-width: 1440px; /* Mantém a largura fixa */
        }
        .logo {
            width: 100px;
            height: auto;
        }
        .menu-container {
            flex-grow: 1;
            display: flex;
            justify-content: center;
        }
        nav {
            display: flex;
            gap: 40px; /* Ajustei o espaçamento do menu */
        }
        nav a {  
            text-decoration: none;
            color: #ffffff;
            font-size: 16px;
            background-color: #004210;
            padding: 15px 30px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
            white-space: nowrap; /* Evita que os botões se quebrem em várias linhas */
        }
        nav a:hover {
            background-color: #002a08;
        }
        .hero {
            position: relative;
            width: 100%;
            max-width: 1440px;
            height: 400px;
            background-image: url('https://img.freepik.com/fotos-gratis/arranjo-de-folhas-de-palmeira-verde-3d_23-2149015443.jpg');
            background-size: cover;
            background-position: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
        }
        .hero h1 {
            font-size: 40px;
            background: rgba(0, 0, 0, 0.5);
            padding: 10px 20px;
            border-radius: 10px;
        }
        .hero p {
            font-size: 20px;
            margin-top: 10px;
            color: white;
        }
        .content {
            padding: 40px;
            text-align: center;
            max-width: 1440px;
            margin: auto; /* Centraliza o conteúdo */
        }
        .content h2 {
            color: #ffffff;
            margin-bottom: 20px;
            font-size: 28px;
            background-color: #002f05;
            padding: 10px;
            text-align: center;
            max-width: 90%;
            margin: auto;
        }
        .content p {
            font-size: 20px;
            color: #000000;
            line-height: 1.6;
            font-family: Roboto;
            max-width: 90%;
            margin: auto;
            text-align: justify;
        }
        .image-top-right {
            width: 80px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <img src="c:\Users\paulo\Downloads\Logo EcoEnsina-Photoroom.png" alt="Logo EcoEnsina" class="logo">   
            <div class="menu-container">
                <nav>
                    <a href="#" onclick="location.reload();">Home</a>
                    <a href="#por-que">Por que?</a>
                    <a href="#modo">Modo</a>
                    <a href="#quem">Quem?</a>
                </nav>
            </div>
            <img src="c:\Users\paulo\Downloads\images-removebg-preview.png" alt="Imagem no canto superior direito" class="image-top-right">
        </header>

        <section class="hero">
            <h1>EcoEnsina</h1>
            <p>Aprenda hoje, preserve para sempre</p>
        </section>

        <section id="por-que" class="content">
            <h2>Por que criamos o EcoEnsina?</h2>
            <b><p>A EcoEnsina nasceu da necessidade urgente de promover a educação ambiental, a sustentabilidade e a consciência climática. Em um mundo onde os impactos ambientais se tornam cada vez mais evidentes, entendemos que a informação e o conhecimento são ferramentas essenciais para a transformação. Queremos capacitar indivíduos e comunidades para adotarem práticas sustentáveis e ajudarem na preservação do meio ambiente.</p></b>
            <b><p>O que queremos promover aos nossos usuários:</p></b>
            <p><b>1º Inspiração para mudanças globais</b> – Acreditamos que pequenas mudanças individuais geram um grande impacto coletivo na luta contra as mudanças climáticas</p>
            <p><b>2º Educação transformadora</b> – Auxiliamos estudantes, professores e o público geral a compreenderem a importância do meio ambiente e da sustentabilidade</p>
            <p><b>3º Engajamento comunitário</b> – Criamos um espaço de troca para incentivar iniciativas sustentáveis e fortalecer a conexão entre as pessoas e o planeta.</p>
            <p><b>4º Acesso à informação confiável</b> – Oferecemos conteúdos educativos baseados em ciência para combater a desinformação ambiental.</p>
            <p><b>5º Soluções práticas e aplicáveis</b> – Ensinamos maneiras simples e eficientes de reduzir impactos ambientais no dia a dia.</p>
        </section>

        <section id="modo" class="content">
            <h2>Modo de Ação</h2>
            <b><p>A EcoEnsina desenvolve suas atividades por meio de um compromisso profundo com a educação, conscientização e engajamento de todos os indivíduos em torno das questões ambientais. Com uma abordagem inovadora e acessível, promovemos o aprendizado sobre sustentabilidade e preservação do meio ambiente, utilizando métodos interativos e eficazes que facilitam a compreensão de temas complexos. Nosso objetivo é transformar o conhecimento adquirido em ações práticas e sustentáveis, que gerem impacto positivo tanto na sociedade quanto no meio ambiente, contribuindo para a construção de um futuro mais equilibrado e responsável.</p></b>
            <b><p>1º Produção de Conteúdo Educativo:</p></b>
                <p>Artigos e guias sobre meio ambiente e sustentabilidade.</p>
                <p>Vídeos educativos e infográficos explicativos.</p>
                <p>Cursos e palestras para aprofundamento em temas ambientais.</p>
            <b><p>2º Incentivo a Práticas Sustentáveis</p></b>
                <p>Dicas para redução do consumo de plástico e desperdício de alimentos.</p>
                <p>Incentivo ao consumo consciente e economia circular.</p>
                <p>Divulgação de projetos e soluções ambientais inovadoras.</p>
            <b><p>3º Conscientização e Engajamento Comunitário</p></b>
                <p>Fóruns e debates sobre emergências climáticas e preservação ambiental.</p>
                <p>Parcerias com escolas, empresas e ONGs para ações educativas.</p>
                <p>Mobilização para campanhas ecológicas e eventos sustentáveis.</p>
            <b><p>Nosso Compromisso</p></b>
            <p>A EcoEnsina busca impactar pessoas, comunidades e organizações, criando um movimento coletivo pela preservação do planeta. Nosso modo de ação é educativo, acessível e prático, sempre incentivando mudanças que fazem a diferença!
                Junte-se a nós nessa missão!
                🌍💚</p>
        </section>

        <section id="quem" class="content">
            <h2>Quem Somos</h2>
            <b><p>Somos alunos da EEEP Maria de Jesus Rodrigues Alves, unidos com o propósito de promover o projeto EcoEnsina. Nosso objetivo é disseminar o conhecimento sobre sustentabilidade e educação ambiental, conscientizando a comunidade sobre a importância de práticas que preservem o nosso planeta. Com dedicação e empenho, buscamos inspirar e engajar pessoas a adotarem ações sustentáveis no dia a dia, para um futuro mais equilibrado e responsável.

                Nosso time é composto por jovens comprometidos com a causa, incluindo:
            </p></b>
                <p><b>Paulo Raí Lopes de Melo</b>, um aluno dedicado e apaixonado por questões ambientais. Ele tem se destacado no desenvolvimento de estratégias para engajar a comunidade local e criar campanhas educativas eficazes sobre preservação ambiental.</p>
                
                <p><b>Ana Luysa</b>, que possui um forte senso de responsabilidade e liderança. Sua habilidade em pensar fora da caixa é essencial para o desenvolvimento de novas abordagens e soluções que tornam a sustentabilidade acessível a todos.Sua paixão por educar e compartilhar informações sobre como todos podem contribuir para a proteção do meio ambiente a torna uma voz fundamental na nossa missão.</p>
                
                <p><b>Maria Eduarda</b>, que traz uma perspectiva criativa e inovadora ao projeto. Sua habilidade em pensar fora da caixa é essencial para o desenvolvimento de novas abordagens e soluções que tornam a sustentabilidade acessível a todos.</p>
                
                <p><b>Emilly Martins</b>, uma estudante que se dedica a estudar o impacto das pequenas ações no meio ambiente. Seu interesse por pesquisa e análise ambiental tem sido crucial para a criação de conteúdos e materiais educativos, ajudando a ampliar o alcance de nossas ações.
                
                <p>Juntos, buscamos impactar positivamente nossa comunidade e além, criando um legado de conscientização e mudança em prol do meio ambiente.</p>
        </section>
    </div>
</body>
</html>
