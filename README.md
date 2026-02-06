<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tableau des Employés</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 20px auto;
            font-family: Arial, sans-serif;
        }
        th, td {
            border: 1px solid #333;
            padding: 12px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
            font-weight: bold;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
    </style>
</head>
<body>
    <table>
        <thead>
            <tr>
                <th>N°</th>
                <th>Nom et prénom</th>
                <th>Fonction</th>
                <th>Salaire</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Koffi gervais</td>
                <td>informaticien</td>
                <td>850 000</td>
            </tr>
            <tr>
                <td>2</td>
                <td>koffi ange</td>
                <td>juriste</td>
                <td>900 000</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Koffi ariane</td>
                <td>sage femme</td>
                <td>750 000</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
