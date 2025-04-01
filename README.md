<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>UP Board 10th Class Exam Result</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 100px;
    }
    h1 {
      font-size: 36px;
      color: red;
    }
    .input-box {
      font-size: 20px;
      padding: 10px;
      width: 300px;
    }
    .submit-button {
      font-size: 24px;
      padding: 10px 20px;
      background-color: green;
      color: white;
      border: none;
      cursor: pointer;
    }
    .submit-button:hover {
      background-color: darkgreen;
    }
    .hidden {
      display: none;
    }
    .prank-message {
      font-size: 40px;
      color: blue;
      font-weight: bold;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <h1 id="form-title">UP Board 10th Class Exam Result</h1>

  <div id="form-section">
    <form id="result-form">
      <input class="input-box" type="text" id="roll-number" placeholder="Enter Roll No." required><br><br>
      <input class="submit-button" type="button" value="Submit" onclick="showPrankMessage()">
    </form>
  </div>

  <div id="prank-section" class="hidden">
    <h1 class="prank-message">Chirag bhai tera popat ban gya hamesha ki tarah kyuki tu pagal hai</h1>
  </div>

  <script>
    function showPrankMessage() {
      // Hide the form and show the prank message
      document.getElementById('form-section').style.display = 'none';
      document.getElementById('prank-section').style.display = 'block';
    }
  </script>
</body>
</html>
