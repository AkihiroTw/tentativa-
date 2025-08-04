function inicializarMovimentoBotaoNao() {
    const botaoNao = document.querySelectorAll("button")[1];

    document.addEventListener("mousemove", (event) => {
        const posicaoMouseX = event.clientX;
        const posicaoMouseY = event.clibody {
    font-family: Arial, sans-serif;<img w<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Convite</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>vamos fazer uma aposta se vc conseguir clicar no "nao" vc ganha,se nao conseguir sua buceta é minha ❤️</h1>
        <div class="buttons">
            <button onclick="resposta('sim')">Sim</button>
            <button onclick="resposta('nao')">Não</button>
        </div>
        <p id="mensagem"></p>
    </div>

    <!-- Elemento para a animação do coração -->
    <div id="coracao-container">
        <img src="images/coracao.png" id="coracao" alt="Coração">
    </div>

    <!-- Elemento para a animação do Ditto -->
    <img src="images/ditto.png" id="ditto" alt="Ditto" style="display: none; position: absolute; z-index: 9;">

    <!-- Elemento de áudio para tocar a música -->
    <audio id="loveSound" src="sounds/love.mp3"></audio>

    <script src="script.js"></script>
</body>
</html>idth="475" height="475" alt="ditto" src="https://github.com/user-attachments/assets/010b3523-1391-43a6-b402-ec9a39156c96" />

    display: flex;<img width="1024" height="1024" alt="coracao" src="https://github.com/user-attachments/assets/d841af96-8766-41ec-8d23-281014beb252" />

    justify-content: center;[Upload<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Convite</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>vamos fazer uma aposta se vc conseguir clicar no "nao" vc ganha,se nao conseguir sua buceta é minha ❤️</h1>
        <div class="buttons">
            <button onclick="resposta('sim')">Sim</button>
            <button onclick="resposta('nao')">Não</button>
        </div>
        <p id="mensagem"></p>
    </div>

    <!-- Elemento para a animação do coração -->
    <div id="coracao-container">
        <img src="images/coracao.png" id="coracao" alt="Coração">
    </div>

    <!-- Elemento para a animação do Ditto -->
    <img src="images/ditto.png" id="ditto" alt="Ditto" style="display: none; position: absolute; z-index: 9;">

    <!-- Elemento de áudio para tocar a música -->
    <audio id="loveSound" src="sounds/love.mp3"></audio>

    <script src="script.js"></script>
</body>
</html>ing index.html…]()

    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #9606be;
  }
  
  .container {
    text-align: center;
  }
  
  h1 {
    font-size: 24px;
    color: #333;
  }
  
  .buttons {
    margin-top: 20px;
  }
  
  button {
    margin: 5px;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    border: none;
    border-radius: 5px;
    transition: background-color 0.3s;
  }
  
  button:hover {
    background-color: #ef0d0d;
  }
  
  button:nth-child(1) {
    background-color: rgb(53, 0, 128);
    color: rgb(0, 234, 255);
  }
  
  button:nth-child(2) {
    background-color: rgb(55, 9, 124);
    color: rgb(31, 215, 225);
  }
  
  #mensagem {
    margin-top: 20px;
    font-size: 18px;
    color: #555;
  }

#coracao-container {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  display: none; /* Inicialmente oculto */
  z-index: 10;
}

#coracao {
  width: 50px; /* Tamanho inicial pequeno */
  opacity: 0;
  animation: crescer 5s ease forwards;
}

/* Animação para fazer o coração crescer */
@keyframes crescer {
  0% {
    transform: scale(0.5);
    opacity: 0;
  }
  100% {
    transform: scale(10);
    opacity: 1;
  }
}

#ditto {
    width: 100px; /* Ajuste conforme necessário */
    display: none; /* Inicialmente oculto */
}

@keyframes aparecerDiminuir {
    0% {
        transform: scale(0);
        opacity: 0;
    }
    50% {
        transform: scale(1.2); /* Aumenta um pouco */
        opacity: 1; /* Totalmente visível */
    }
    100% {
        transform: scale(0); /* Retorna ao tamanho 0 */
        opacity: 0; /* Torna invisível */
    }
}

#ditto {
    width: 100px; /* Ajuste conforme necessário */
    height: 100px; /* Ajuste conforme necessário */
    display: none; /* Inicialmente oculto */
    position: absolute;
    z-index: 20; /* Para garantir que fique sobre outros elementos */
    animation: aparecerDiminuir 4s forwards; /* Animação de 2 segundos */
}

@keyframes transformarBotaoNao {
    0% {
        background-color: red; /* Cor inicial */
    }
    50% {
        background-color: orange; /* Cor durante a animação */

    }
    100% {
        background-color: green; /* Cor final */
    }
}

.transformar {
    animation: transformarBotaoNao 2s forwards; /* Dura 2 segundos */
}
entY;

        botaoNao.addEventListener("mouseover", () => {
            const maxWidth = window.innerWidth - botaoNao.offsetWidth;
            const maxHeight = window.innerHeight - botaoNao.offsetHeight;

            let novaPosicaoX;
            let novaPosicaoY;

            do {
                novaPosicaoX = Math.random() * maxWidth;
                novaPosicaoY = Math.random() * maxHeight;
            } while (
                Math.abs(novaPosicaoX - posicaoMouseX) < 100 && 
                Math.abs(novaPosicaoY - posicaoMouseY) < 100
            );

            botaoNao.style.position = "absolute";
            botaoNao.style.left = `${novaPosicaoX}px`;
            botaoNao.style.top = `${novaPosicaoY}px`;
        });
    });
}

function resposta(opcao) {
    const mensagem = document.getElementById("mensagem");
    const loveSound = document.getElementById("loveSound");
    const coracaoContainer = document.getElementById("coracao-container");
    const ditto = document.getElementById("ditto");
    const botaoNao = document.querySelectorAll("button")[1];

    if (opcao === 'sim') {
        // Toca a música
        loveSound.play();
        // Exibe e anima o coração
        coracaoContainer.style.display = "block";

        // Aguarda o fim da animação e da música para abrir o link
        setTimeout(() => {
            window.open("https://wa.me/5563991036533?text=Oiie.%20E%20ai,%20vamo%20pra%20onde?%20Que%20horas?", "_self");
            coracaoContainer.style.display = "none";
            //location.reload(); // Reinicia a página
        }, 5000); // 5 segundos para a animação
        mensagem.textContent = ""; // Limpa a mensagem

    } else {
        // (O restante do código para a opção "não" permanece inalterado)

        const rect = botaoNao.getBoundingClientRect();

        const dittoWidth = 100; // Largura do Ditto
        const dittoHeight = 100; // Altura do Ditto
        
        ditto.style.left = `${rect.left + (rect.width / 2) - (dittoWidth / 2)}px`;
        ditto.style.top = `${rect.top + (rect.height / 2) - (dittoHeight / 2)}px`;
        ditto.style.display = "block"; // Mostra o Ditto

        // Inicia a animação
        ditto.classList.add("animar");

        setTimeout(() => {
            botaoNao.textContent = "Sim"; 
            botaoNao.style.backgroundColor = "green"; // Muda a cor para verde
            botaoNao.classList.add("transformar"); // Adiciona a classe de transformação ao botão
        }, 1000); // 1 segundo de delay

        setTimeout(() => {
            ditto.style.display = "none"; // Oculta o Ditto após 2 segundos
            botaoNao.classList.remove("transformar"); // Remove a transformação do botão

            setTimeout(() => {
                loveSound.play();
                coracaoContainer.style.display = "block";

                setTimeout(() => {
                    window.open("https://wa.me/5563991036533?text=Oiie.%20E%20ai,%20vamo%20pra%20onde?%20Que%20horas?", "_self");
                    coracaoContainer.style.display = "none"; // Oculta o coração após a animação
                    //location.reload(); // Reinicia a página
                }, 5000); // 5 segundos para a animação
            }, 0); // 1 segundo após o fim da animação do Ditto
        }, 3000); // 3 segundos para mostrar o Ditto
    }
}

// Chama a função para inicializar o movimento do botão "Não"
inicializarMovimentoBotaoNao();
