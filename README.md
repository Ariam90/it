<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Symptom Checker</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Symptom Checker</h1>
    </header>

    <section id="symptomInput">
        <label for="symptoms">Enter your symptoms:</label>
        <textarea id="symptoms" rows="4" cols="50"></textarea>

        <div id="suggestions">
            <!-- Suggestions will appear here -->
        </div>
    </section>

    <button onclick="checkSymptoms()">Check Symptoms</button>

    <section id="resultSection">
        <h2>Result:</h2>
        <p id="result"></p>
    </section>

    <script src="script.js"></script>
</body>
</html>
