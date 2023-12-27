### Hi there 👋

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* Add some basic styling */
    body {
      font-family: 'Arial', sans-serif;
      font-size: 2em;
      text-align: center;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <div id="name"></div>

  <script>
    // Your name
    const name =Hi 👋! My name is Amira Mohamed and I'm a Flutter developer  ;

  
    function displayLetters(index) {
      if (index < name.length) {
        document.getElementById('name').innerHTML += name.charAt(index);
        index++;
        setTimeout(() => displayLetters(index), 1000); // Adjust the delay as needed
      }
    }

    // Start the animation
    displayLetters(0);
  </script>
</body>
</html>
