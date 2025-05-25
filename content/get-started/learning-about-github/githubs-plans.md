<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Carta de Amor</title>
    <style>
        body {
            background: #ffe4ec;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .carta {
            background: white;
            border-radius: 16px;
            box-shadow: 0 4px 16px rgba(0,0,0,0.1);
            padding: 40px 60px;
            text-align: center;
        }
        .te-amo {
            color: #e75480;
            font-size: 2em;
            margin: 10px 0;
            font-family: 'Comic Sans MS', cursive, sans-serif;
        }
        button {
            background: #e75480;
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 8px;
            font-size: 1em;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background: #c13b5c;
        }
    </style>
</head>
<body>
    <div class="carta">
        <div class="te-amo">Te amo</div>
        <button onclick="mostrarTeAmo()">Haz clic aquí</button>
        <div id="muchos-te-amo"></div>
    </div>
    <script>
        function mostrarTeAmo() {
            const contenedor = document.getElementById('muchos-te-amo');
            for (let i = 0; i < 20; i++) {
                const div = document.createElement('div');
                div.className = 'te-amo';
                div.textContent = 'Te amo';
                contenedor.appendChild(div);
            }
        }
    </script>
</body>
</html>
  
 


 



