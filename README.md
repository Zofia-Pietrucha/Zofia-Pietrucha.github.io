<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Przykładowa Strona HTML</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 20px;
        }

        h1, h2, p {
            color: #333;
        }

        a {
            color: #007bff;
            text-decoration: none;
        }

        table {
            border-collapse: collapse;
            width: 100%;
            margin-top: 20px;
        }

        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }

        th {
            background-color: #f2f2f2;
        }

        img {
            max-width: 100%;
            height: auto;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <h1>Strona HTML z Elementami</h1>

    <h2>Paragrafy:</h2>
    <p>To jest przykładowy paragraf.</p>
    <p>Kolejny paragraf z <a href="https://placekitten.com/">linkiem</a>.</p>

    <h2>Tabela:</h2>
    <table>
        <thead>
            <tr>
                <th>Nagłówek 1</th>
                <th>Nagłówek 2</th>
                <th>Nagłówek 3</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Wartość 1</td>
                <td>Wartość 2</td>
                <td>Wartość 3</td>
            </tr>
            <tr>
                <td>Wartość 4</td>
                <td>Wartość 5</td>
                <td>Wartość 6</td>
            </tr>
        </tbody>
    </table>

    <h2>Obrazek:</h2>
    <img src="https://placekitten.com/400/300" alt="Kitten Image">

</body>
</html>
