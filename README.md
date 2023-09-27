<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Minimalista</title>
    <style>
        body {
            background-color: #000;
            color: #fff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: #333;
            padding: 20px;
            text-align: center;
        }
        
        h1 {
            font-size: 36px;
        }
        
        .post {
            background-color: #222;
            padding: 20px;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            transition: transform 0.2s;
        }
        
        .post:hover {
            transform: scale(1.02);
        }
        
        .post h2 {
            font-size: 24px;
        }
        
        .post p {
            font-size: 18px;
        }
        
        footer {
            background-color: #333;
            text-align: center;
            padding: 10px;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mi Blog Minimalista</h1>
    </header>
    
    <div class="post">
        <h2>Post 1</h2>
        <p>Este es el contenido del primer post. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </div>
    
    <div class="post">
        <h2>Post 2</h2>
        <p>Este es el contenido del segundo post. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </div>
    
    <footer>
        © 2023 Mi Blog Minimalista
    </footer>

    <script>
        // Puedes agregar aquí tu JavaScript personalizado
    </script>
</body>
</html>
