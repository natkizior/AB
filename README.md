<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Air Brakes Test</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Air Brakes Test</h1>
        <form id="quizForm">
            <div class="question">
                <p>1. When is it OK to leave your truck unattended without applying the parking brakes and chocking the wheels?</p>
                <label><input type="radio" name="q1" value="A"> Never</label><br>
                <label><input type="radio" name="q1" value="B"> If you are only away for a few minutes</label><br>
                <label><input type="radio" name="q1" value="C"> If you are conducting a pre-trip inspection</label>
            </div>
            <!-- Add other questions here following the same structure -->
            <button type="button" onclick="checkAnswers()">Submit</button>
        </form>
        <div id="result"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>
