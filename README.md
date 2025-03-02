DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalkulator Sederhana</title>
</head>
<body>
    <h1>Kalkulator Persegi</h1>
    <label for="sisi">Sisi:</label>
    <input type="number" id="sisi">
    <button onclick="hitungLuas()">Hitung</button>
    <p id="hasil"></p>

    <script>
        function hitungLuas() {
            let sisi = document.getElementById("sisi").value;
            let luas = sisi * sisi;
            document.getElementById("hasil").innerText = "Luas Persegi: " + luas;
        }
    </script>
</body>
</html>