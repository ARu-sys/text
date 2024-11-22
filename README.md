<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled Headings</title>
  <style>
    body {
      font-family: 'Times New Roman', Times, serif; /* Serif font */
      background-color: #f9f9f9; /* Light background for better contrast */
      margin: 0;
      padding: 20px;
      display: flex;
      flex-direction: column;
      align-items: center; /* Center align the content horizontally */
      justify-content: center; /* Center align the content vertically */
      height: 100vh; /* Full screen height */
    }

    h1 {
      font-size: 2.5em;
      color: black;
      text-shadow: 2px 2px 3px pink;
      text-decoration: underline;
      border: 2px solid black;
      padding: 10px;
      display: inline-block;
      font-weight: bold; /* Matches the boldness of the font */
      margin-bottom: 20px; /* Add spacing between headings */
    }

    h2 {
      font-size: 2em;
      font-style: italic;
      color: black;
      padding: 10px;
      display: inline-block;
      background-color: white;
      border: 3px solid yellow;
      box-shadow: inset 0 0 0 3px black; /* Inner black border */
      margin-bottom: 20px; /* Add spacing between headings */
    }

    h3 {
      font-size: 1.5em;
      font-style: italic;
      color: black;
      text-decoration: underline;
      margin-top: 20px;
      font-weight: normal;
    }
  </style>
</head>
<body>
  <h1>This is heading 1</h1>
  <h2>This is heading 2</h2>
  <h3>This is heading 3</h3>
</body>
</html>
