<!DOCTYPE html>
<html>
<head>
    <title>Mudar Cor de Fundo</title>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script>
        $(document).ready(function(){
            $("#mudarCorBtn").click(function(){
                var cores = ["red", "blue", "green", "yellow", "purple", "orange"];
                var corAleatoria = cores[Math.floor(Math.random() * cores.length)];
                $("body").css("background-color", corAleatoria);
            });
        });
    </script>
</head>
<body>
    <button id="mudarCorBtn">Mudar Cor</button>
</body>
</html>
