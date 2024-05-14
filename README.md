<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GPL - Gully Premier League</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, gold, blue);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            width: 100%;
            position: fixed;
            top: 0;
        }

        main {
            padding: 1em;
            max-width: 800px;
            background-color: rgba(255, 255, 255, 0.8); /* Slightly transparent white */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            margin-top: 60px; /* To avoid overlap with the fixed header */
        }

        h1, h2 {
            margin: 0 0 1em;
        }

        .points-table {
            margin: 2em 0;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin: 1em 0;
            text-align: center;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 0.5em;
        }

        th {
            background-color: #333;
            color: #fff;
        }

        tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        .sunrising-indians {
            background: linear-gradient(to right, orange, blue);
            color: white;
        }

        .knight-mega-kings {
            background: linear-gradient(to right, purple, blue);
            color: white;
        }

        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #333;
            color: #fff;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>GPL - Gully Premier League</h1>
    </header>
    <main>
        <section class="points-table">
            <h2>Points Table</h2>
            <table>
                <thead>
                    <tr>
                        <th>Position</th>
                        <th>Team</th>
                        <th>Played</th>
                        <th>Won</th>
                        <th>Lost</th>
                        <th>Tied</th>
                        <th>Points</th>
                        <th>NRR</th>
                    </tr>
                </thead>
                <tbody>
                    <tr class="sunrising-indians">
                        <td>1</td>
                        <td>Sunrising Indians</td>
                        <td>4</td>
                        <td>4</td>
                        <td>0</td>
                        <td>0</td>
                        <td>10</td>
                        <td>+1.25</td>
                    </tr>
                    <tr class="knight-mega-kings">
                        <td>2</td>
                        <td>Knight Mega Kings</td>
                        <td>4</td>
                        <td>0</td>
                        <td>4</td>
                        <td>0</td>
                        <td>4</td>
                        <td>+0.95</td>
                    </tr>
                </tbody>
            </table>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 GPL - Gully Premier League</p>
    </footer>
</body>
</html>
