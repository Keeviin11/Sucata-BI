<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Sucata de Pneus Power BI</title>
    
    <!-- Ícone no navegador -->
    <link rel="icon" href="https://cdn-icons-png.flaticon.com/512/619/619153.png" type="image/png">

    <!-- Fonte moderna -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html, body {
            height: 100%;
            background-color: #000;
            font-family: 'Poppins', sans-serif;
            color: #ccc;
        }

        header {
            background-color: #111;
            padding: 16px 32px;
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 2px 10px rgba(255, 215, 0, 0.05);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 100;
        }

        header h1 {
            color: #FFD700;
            font-size: 1.8rem;
            font-weight: 600;
            text-shadow: 0 0 8px rgba(255, 215, 0, 0.4);
            text-align: center;
        }

        main {
            padding-top: 80px; /* espaço para o header */
            height: calc(100vh - 80px);
            width: 100%;
        }

        iframe {
            width: 95%;
            height: 95%;
            border: none;
        }

        footer {
            background-color: #111;
            color: #666;
            font-size: 0.9rem;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>📊 Sucata de Pneus Power BI 📊</h1>
    </header>

    <main>
        <iframe 
            title="Relatório Power BI" 
            src="https://app.powerbi.com/view?r=eyJrIjoiZDdjNzZiMWUtYjUwMy00MDI2LTk2YzItNjE2OTYzMWYwMzAyIiwidCI6ImIyZmE0MzA0LWVmNDgtNGVkMy1iZThkLWZiNDQ2NDYxMDUzOCJ9"
            allowFullScreen="true">
        </iframe>
    </main>



    <footer>
        © 2025 | Desenvolvido por [Kevin]
    </footer>

</body>
</html>

