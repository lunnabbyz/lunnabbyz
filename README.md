<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assets/style.css">
    <title>Flashcard</title>
    <style>
        body{
            background-color: bisque;
            font-family: Bai Jamjuree;
        }
        footer {
            background-color: black;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
            height: 2rem;
        }
        footer p {
            text-align: center;
            font-size: 0.6rem;
            margin-top: 0.5rem;
        }
        #container {
            display: flex;
        }
        .cartao {
            margin: 1rem 1rem;
            background-color: aqua;
            height: 20rem;
            flex-grow: 1;
            flex-basis: caic(33% - 6rem); 
        }
        .cartao__conteudo {
            text-align: center;
            background-color: aquamarine;
            height: 100%;
        }
        .cartao__conteudo h3 {
            background-color: tomato;
            text-align: left;
            padding: 0.5rem;
            position: absolute;
            margin: 0.6rem;
            border-radius: 0.6rem;
            font-size: 1vw;
        }
    </style>
</head>
<body>
    <main>
        <section id="container">
            <article class="cartao">
                <div class="cartao__conteudo">
                <h3>Programação</h3>
                <div class="cartao__conteudo__pergunta">
                   <p>O que é JavaScript?<p/>
                </div>
                <div class="cartao__conteudo__resposta">
                   <p>O JavaScript é uma linguagem de programação<p/>
                </div>
                </div>
            </article>
           <article class="cartao">
                <div class="cartao__conteudo">
                <h3>Programação</h3>
                <div class="cartao__conteudo__pergunta">
                    <p>O que é CSS?<p/>
                </div>
                <div class="cartao__conteudo__resposta">
                    <p>O CSS é uma linguagem de estilização.<p/>
                </div>
                </div>
            </article>
    </section>

    </main>
    <footer>
        <p>Projeto desenvolvido pela Alura, sem fins lucrativos</p>
    </footer>
</body>
  <html>
