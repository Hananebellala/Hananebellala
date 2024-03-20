

# Hey there, I'm Hanane Bellala 👋

I’m a computer science student, passionate about mobile development and data science.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Visitor Counter</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
    }
    .container {
      width: 300px;
      margin: 100px auto;
      text-align: center;
    }
    .counter {
      font-size: 36px;
      font-weight: bold;
      color: #ff6a00;
    }
    .label {
      font-size: 18px;
      color: #555;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="counter">0</div>
    <div class="label">Visitors</div>
  </div>

  <script>
    // Function to update the counter
    function updateCounter() {
      // You can fetch the visitor count from an API here
      // For demonstration, let's just increment the count by 1
      let counter = document.querySelector('.counter');
      let count = parseInt(counter.innerText);
      counter.innerText = count + 1;
    }

    // Update the counter on page load
    window.onload = updateCounter;
  </script>
</body>
</html>


<!---
Hananebellala/Hananebellala is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
