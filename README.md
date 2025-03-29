<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorteio de Óculos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        input, button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #28a745;
            color: white;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Participe do Sorteio de um Óculos!</h2>
        <form id="sorteioForm">
            <input type="text" id="nome" placeholder="Nome" required>
            <input type="email" id="email" placeholder="E-mail" required>
            <input type="tel" id="celular" placeholder="Celular" required>
            <button type="submit">Participar</button>
        </form>
    </div>
    <script>
        document.getElementById("sorteioForm").addEventListener("submit", function(event) {
            event.preventDefault();
            alert("Cadastro realizado com sucesso!");
        });
    </script>
</body>
</html>
