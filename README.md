<!DOCTYPE html>
<html lang="lt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalėdinis Sveikinimas</title>
    <style>
        body {
            background-color: #f2f2f2;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        
        header {
            background-color: #622F22;
            color: white;
            padding: 20px 0;
        }
        
        h1 {
            font-size: 3em;
            margin: 0;
        }

        .content {
            margin-top: 50px;
        }

        .table-container {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 30px;
            display: inline-block;
            margin-top: 20px;
            width: 80%;
            max-width: 800px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            padding: 15px;
            text-align: center;
            border: 1px solid #ddd;
        }

        th {
            background-color: #622F22;
            color: white;
        }

        td {
            font-size: 1.2em;
            background-color: #f9f9f9;
        }

        .greeting {
            font-size: 1.5em;
            color: #622F22;
            margin-top: 20px;
        }

        .images-container {
            margin-top: 30px;
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        .images-container img {
            border-radius: 10px;
            width: 150px;
            height: 150px;
            object-fit: cover;
        }

        footer {
            background-color: #622F22;
            color: white;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Kalėdinis Sveikinimas</h1>
    </header>

    <div class="content">
        <div class="table-container">
            <table>
                <tr>
                    <th colspan="2">Kalėdiniai linkėjimai</th>
                </tr>
                <tr>
                    <td>Linkiu Tau</td>
                    <td><strong>Šiltų ir laimingų švenčių!</strong></td>
                </tr>
                <tr>
                    <td>Praleisti šias Kalėdas</td>
                    <td><strong>su artimaisiais ir draugais</strong></td>
                </tr>
                <tr>
                    <td>Ir įgyvendinti</td>
                    <td><strong>visus ateinančių metų norus!</strong></td>
                </tr>
            </table>
        </div>

        <div class="greeting">
            <p>Linksmų ir taikių Kalėdų bei laimingų Naujųjų metų!</p>
        </div>

        <div class="images-container">
            <img src="https://www.w3schools.com/w3images/christmas.jpg" alt="Kalėdų eglutė">
            <img src="https://www.w3schools.com/w3images/snowman.jpg" alt="Sniego senis">
            <img src="https://www.w3schools.com/w3images/gift.jpg" alt="Dovanos">
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Kalėdinis Sveikinimas | Sukūrė Jūsų Vardas</p>
    </footer>
</body>
</html>
