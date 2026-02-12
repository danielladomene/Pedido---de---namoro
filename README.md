# Pedido---de---namoro
<!DOCTYPE html><html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <title>Pedido de Namoro</title>
  <meta name="Gabriela" content="width=device-width, initial-scale=1.0" />
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      text-align: center;
      color: #333;
    }.card {
  background: white;
  padding: 30px;
  border-radius: 20px;
  max-width: 500px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.2);
  animation: fadeIn 1s ease;
}

h1 {
  color: #e91e63;
}

p {
  line-height: 1.6;
  margin-bottom: 25px;
}

.buttons {
  display: flex;
  gap: 15px;
  justify-content: center;
  flex-wrap: wrap;
}

button {
  padding: 12px 25px;
  font-size:
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Um pedido especial...</title>
    <style>
        body {
            background-color: #ffebee;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
            text-align: center;
        }

        .container {
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            max-width: 400px;
            width: 90%;
        }

        img {
            max-width: 100%;
            border-radius: 15px;
            margin-bottom: 20px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        h1 {
            color: #d32f2f;
            font-size: 1.8rem;
            margin-bottom: 30px;
        }

        .buttons {
            display: flex;
            justify-content: space-around;
            align-items: center;
            gap: 20px;
        }

        button {
            padding: 15px 30px;
            font-size: 1.2rem;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            transition: transform 0.2s;
        }

        #btn-sim {
            background-color: #4caf50;
            color: white;
        }

        #btn-nao {
            background-color: #f44336;
            color: white;
            position: relative;
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="foto-casal.jpg" alt="Nossa Foto">
        
        
        <h1> Eu n sou a pessoa mais legal do mundo, e tenho muitos defeitos, mais quero mudar oq puder para te ver feliz, e oq não conseguir mudar espero que você entenda que estou tentando, eu sou completamente apaixonada por vc, não te conheço pessoalmente mais eu sei que o amor que sinto por vc ultrapassa qualquer distância, me desculpa se algum dia fizer algo que vc não goste, mais saiba que foi tentando acertar. 
E tentando te fazer a mulher mais feliz no mundo.
 Eu já te amo tanto. Obrigada por existir e obrigada por estar aqui, obrigada por querer dividir a vida e eu sou loucamente apaixonada por vc e que espero que cada dia vire um amor incondicional❤️.
 I love you.
 
Quer namorar comigo?

</h1>

        <div class="buttons">
            <button id="btn-sim" onclick="aceitou()">SIM!</button>
            <button id="btn-nao" onmouseover="foge(this)" onclick="foge(this)">Não</button>
        </div>
    </div>

    <script>
        function aceitou() {
            // Redireciona para o seu WhatsApp com a mensagem pronta
            const numero = "5544999915008";
            const mensagem = "Eu aceito! ❤️";
            window.location.href = `https://wa.me/${numero}?text=${encodeURIComponent(mensagem)}`;
        }

        function foge(botao) {
            // Faz o botão "Não" fugir do mouse ou do clique
            const x = Math.random() * (window.innerWidth - botao.offsetWidth);
            const y = Math.random() * (window.innerHeight - botao.offsetHeight);
            
            botao.style.position = "absolute";
            botao.style.left = x + "px";
            botao.style.top = y + "px";
        }
    </script>

</body>
</html>
