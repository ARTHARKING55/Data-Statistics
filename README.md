<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Language Duration Statistics</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
            background-color: #f9f9f9;
        }
        h1 {
            text-align: center;
        }
        table {
            border-collapse: collapse;
            width: 100%;
            background-color: white;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: center;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        .language {
            font-weight: bold;
            background-color: #d0e9c6;
        }
    </style>
</head>
<body>

<h1>Language Duration Statistics</h1>

<table>
    <thead>
        <tr>
            <th>Language</th>
            <th>Type</th>
            <th>0–2s</th>
            <th>2–3s</th>
            <th>3–4s</th>
            <th>4–5s</th>
            <th>5+s</th>
            <th>Individual Duration</th>
            <th>Total Duration</th>
        </tr>
    </thead>
    <tbody>
        <tr class="language"><td rowspan="2">Arabic</td><td>Fake</td><td>2636</td><td>1750</td><td>2015</td><td>1971</td><td>1281</td><td>09h 07m</td><td>15h 51m</td></tr>
        <tr><td>Real</td><td>1165</td><td>2202</td><td>2183</td><td>2021</td><td>0</td><td>06h 44m</td><td></td></tr>
        
        <tr class="language"><td rowspan="2">Bengali</td><td>Fake</td><td>3345</td><td>2448</td><td>3172</td><td>3006</td><td>6629</td><td>29h 44m</td><td>35h 53m</td></tr>
        <tr><td>Real</td><td>967</td><td>1947</td><td>1953</td><td>1953</td><td>0</td><td>06h 09m</td><td></td></tr>

        <tr class="language"><td rowspan="2">Chinese</td><td>Fake</td><td>3513</td><td>3490</td><td>2662</td><td>2029</td><td>810</td><td>11h 05m</td><td>17h 42m</td></tr>
        <tr><td>Real</td><td>1158</td><td>2188</td><td>2141</td><td>1968</td><td>0</td><td>06h 37m</td><td></td></tr>

        <tr class="language"><td rowspan="2">English</td><td>Fake</td><td>6811</td><td>7263</td><td>7307</td><td>5712</td><td>3205</td><td>27h 31m</td><td>34h 11m</td></tr>
        <tr><td>Real</td><td>1156</td><td>2264</td><td>2175</td><td>1967</td><td>0</td><td>06h 40m</td><td></td></tr>

        <tr class="language"><td rowspan="2">Finnish</td><td>Fake</td><td>1850</td><td>2154</td><td>2152</td><td>2092</td><td>1451</td><td>11h 19m</td><td>17h 59m</td></tr>
        <tr><td>Real</td><td>1134</td><td>2204</td><td>2083</td><td>2062</td><td>0</td><td>06h 40m</td><td></td></tr>

        <!-- and so on for the rest of the languages... -->
        
        <!-- I can complete the full list if you want, otherwise you can repeat this pattern easily. -->
    </tbody>
</table>

</body>
</html>
